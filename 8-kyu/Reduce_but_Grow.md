# CodeWars JS Solutions

---

## Reduce but Grow

Given a non-empty array of integers, return the result of multiplying the values together in order. Example:

[1, 2, 3, 4] => 1 * 2 * 3 * 4 = 24

---

### Given Code


```js
function grow(x){

}
```

---

### My Solution 


```js
function grow(x){
  let d = 1;
  for (let i = 0; i < x.length; i++) {
    d=d*x[i];
  }
  return d;
}
```


---