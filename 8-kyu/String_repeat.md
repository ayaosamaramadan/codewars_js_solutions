# CodeWars JS Solutions

---

## String repeat

Write a function that accepts an integer n and a string s as parameters, and returns a string of s repeated exactly n times.

Examples (input -> output)
6, "I"     -> "IIIIII"
5, "Hello" -> "HelloHelloHelloHelloHello"

---

### Given Code


```js
function repeatStr (n, s) {
  return '';
}
```

---

### My Solution 


```js
  function repeatStr (n, s) 
{
  let strings= "";
  for(let i = 0; i < n; i++) 
  {
    strings +=s;
  }
  return strings;
}
```


---

