# CodeWars JS Solutions

---

## MakeUpperCase

Write a function which converts the input string to uppercase.

---

### Given Code


```js
function makeUpperCase(str) {
  // Code here
}
```

---

### My Solution 


```js
function makeUpperCase(str)
{
  
  return arrStr=str.split("").map(x => x.toLowerCase()? x.toUpperCase():x).join("");
}
```


---

