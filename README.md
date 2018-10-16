# JSEpisodeOne-Demo

[Slides](https://docs.google.com/presentation/d/1P8MPXUktK_viz0AO2Vqu4WKPrCiWLh7CGbiKrTztLcU/edit#slide=id.g43fb029fa7_0_5)

---

### Code Blocks (If-Statement)

BLOCK 01 (MANUAL)

```javascript
let number = 5;
console.log("ODD")
```
BLOCK 02 (IF)

```javascript
let number = 5;

if (number % 2 !== 0) {
    console.log("ODD");
}
```
BLOCK 03 (IF-ELSEIF)
```javascript
let number = 5;

if (number % 2 === 0) {
    console.log("EVEN");
} else if (number % 2 !== 0) {
    console.log("ODD");
}
```
BLOCK 04 (IF-ELSEIF-ELSE)
```javascript
let number = 5;

if (number % 2 === 0) {
    console.log("EVEN");
} else if (number % 2 !== 0) {
    console.log("ODD");
} else {
    console.log("IMPOSSIBRU!!!");
}
```
BLOCK 04 (WITHOUT BRACES)
```javascript
let number = 5;

if (number % 2 === 0)
    console.log("EVEN");
else if (number % 2 !== 0)
    console.log("ODD");
else
    console.log("IMPOSSIBRU!!!");
```

---

### Code Blocks (Functions)

BLOCK 01
```javascript
function helloWorld() {
  console.log("Hello World!");
}
```
BLOCK 02
```javascript
function greet(name) {
    console.log(`Hello ${name}`);
}

function multiplyTwoNumbers(a,b) {
    return a*b;
}

// These braces are required always.
```
