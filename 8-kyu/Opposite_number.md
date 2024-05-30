# CodeWars JS Solutions

---

## Opposite number

Very simple, given a number (integer / decimal / both depending on the language), find its opposite (additive inverse).

Examples:

1: -1
14: -14
-34: 34

---

### Given Code


```js
function opposite(number) {
  //your code here
}
```

---

### My Solution 


```js
function opposite(number) {
  if (number > 0) {
    return -Math.abs(number);
  } else {
    return Math.abs(number);
  }
}
```


---

