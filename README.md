# JSEpisodeOne-Demo

[Slides](https://docs.google.com/presentation/d/1P8MPXUktK_viz0AO2Vqu4WKPrCiWLh7CGbiKrTztLcU/edit#slide=id.g43fb029fa7_0_5)

---

### Code Blocks (If-Statement)

// ========================= BLOCK 01 (MANUAL)

    let number = 5;
    console.log("ODD")

// ========================= BLOCK 02 (IF)

```javascript
let number = 5;

if (number % 2 !== 0) {
    console.log("ODD");
}
```
// ========================= BLOCK 03 (IF-ELSEIF)
let number = 5;

if (number % 2 === 0) {
    console.log("EVEN");
} else if (number % 2 !== 0) {
    console.log("ODD");
}

// ========================= BLOCK 04 (IF-ELSEIF-ELSE)
let number = 5;

if (number % 2 === 0) {
    console.log("EVEN");
} else if (number % 2 !== 0) {
    console.log("ODD");
} else {
    console.log("IMPOSSIBRU!!!");
}

// ========================= BLOCK 04 (WITHOUT BRACES)
let number = 5;

if (number % 2 === 0)
    console.log("EVEN");
else if (number % 2 !== 0)
    console.log("ODD");
else
    console.log("IMPOSSIBRU!!!");
