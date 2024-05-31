# CodeWars JS Solutions

---

## Remove duplicates from list

Define a function that removes duplicates from an array of non negative numbers and returns it as a result.

The order of the sequence has to stay the same.

Examples:

Input -> Output
[1, 1, 2] -> [1, 2]
[1, 2, 1, 1, 3, 2] -> [1, 2, 3]


---

### Given Code


```js
function distinct(a) {
  return [];
}
```

---

### My Solution 


```js
function distinct(a) 
{
  let arr = [];
  for (let i = 0; i <a.length; i++) 
  {
    if (arr.indexOf(a[i])===-1) {  arr.push(a[i]);
    }
  }
  return arr;
}
```


---