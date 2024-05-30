# CodeWars JS Solutions

---

## Fake Binary

Given a string of digits, you should replace any digit below 5 with '0' and any digit 5 and above with '1'. Return the resulting string.

Note: input will never be an empty string

---

### Given Code


```js
function fakeBin(x){

}
```

---

### My Solution 


```js
function fakeBin(x)
{
  return x.replace(/[1-4]/g,0).replace(/[5-9]/g,1)
}
```


---

