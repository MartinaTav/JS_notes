# Custom Functions

Functions are *defined* and then they are *called*.

```javascript
// function definition
function calculateBill(amount, vat) {
    const total = amount * vat;
    return total
    console.log('Running calculate bill')
}

// calling a function
const myTotal = calculateBill();
// so we can have a access to the return value from the function
```