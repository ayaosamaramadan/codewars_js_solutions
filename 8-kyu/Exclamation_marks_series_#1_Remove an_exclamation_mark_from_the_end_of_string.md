# CodeWars JS Solutions

---

## Exclamation marks series #1: Remove an exclamation mark from the end of string

Remove an exclamation mark from the end of a string. For a beginner kata, you can assume that the input data is always a string, no need to verify it.

Examples
"Hi!"     ---> "Hi"
"Hi!!!"   ---> "Hi!!"
"!Hi"     ---> "!Hi"
"!Hi!"    ---> "!Hi"
"Hi! Hi!" ---> "Hi! Hi"
"Hi"      ---> "Hi"
---

### Given Code


```js
function remove (string) {
  //coding and coding....
  return '';
}
```

---

### My Solution 


```js
function remove (string) {
  return string.replace(/!$/, '');
}
```


---

