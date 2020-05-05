# STRINGS 

- they're used for holding text
- 3 different ways to create strings in JS:
  - single quotes ''
  - double quotes ""
  - back ticks ``

```javascript
const name = 'Bilbo';
const last = "Baggins";
const fam = `Frodo`;
```

best is use the back ticks because you do not have to escape characters

you can use the back ticks when you are putting strings on multiple lines 

```javascript 
const song = `no way

to live a

LIVE! `
```
it's extremely helpful for when you want to make html 

```javascript 
const html = `
<div>
    <h2></h2>
</div>
`
```
with back ticks it's very easy to concatenate and interpolate. 
/ concatenation = 2 or more strings are combined into 1
  interpolation = when you put a variable inside of a string
/  

```javascript 
const hello = 'Hi, my name is ' + name + '. Nice to meet you.';
const hello2 = `Hi, my name is ${name}. Nice to meet you.`;
```

### number + string = string

with back ticks interpolation you can do  math
```javascript
const age = `I'm ${30 + 4} years old`;
```