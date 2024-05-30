# CodeWars JS Solutions

---

## No zeros for heros

Numbers ending with zeros are boring.

They might be fun in your world, but not here.

Get rid of them. Only the ending ones.

1450 -> 145
960000 -> 96
1050 -> 105
-1050 -> -105
Zero alone is fine, don't worry about it. Poor guy anyway

---

### Given Code


```js
function noBoringZeros(n) {
  // your code
}
```

---

### My Solution 


```js
function noBoringZeros(n) 
{
  let newN = String(n);
  while(newN.endsWith(0))
  {
    newN = newN.slice(0, newN.length - 1);
  }
  return Number(newN);
}
```


---

