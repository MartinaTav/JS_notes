# Functions - Parameters & Arguments

```javascript
function calculateBill(billAmount, taxRate) {
    const total = billAmount * (1 + taxRate);
    return total;
}

const myTotal = calculateBill(100, 0.2);
```
Data passed to the functions at declaration are calling _paremeters_ and when you run it then the real values are called _arguments_.

We can pass variables to the functions as a arguments.

```javascript
const table5Total = 500;
const table5VAT = 0.2;
function calculateBill(billAmount, taxRate) {
    const total = billAmount * (1 + taxRate);
    return total;
}

const myTotal5 = calculateBill(table5Total, table5VAT);
```

```javascript
function sayHiTo(firstName) {
    return `Hello ${firstName}`;
}

const greeting = sayHiTo('Bilbo');
```

## Passing Expressions
```javascript
const myTotal = calculateBill(50+ 20+ 30, 0.2)

function doctorize(name) {
    return `Dr. ${name}`;
}

function yell(name) {
    return `HEY ${name.toUpperCase()}`;
}

yell(doctorize('Bilbo'));
// HEY DR. BILBO
```
## Dafault Values

```javascript 
function yell(name = 'Silly Goose') {
    return `HEY ${name.toUpperCase()}`;
}