# CodeWars JS Solutions

---

## Unfinished Loop - Bug Fixing #1

Oh no, Timmy's created an infinite loop! Help Timmy find and fix the bug in his unfinished for loop!

---

### Given Code


```js
function createArray(number){
  var newArray = [];
  
  for(var counter = 1; counter <= number;){
    newArray.push(counter);
  }
  
  return newArray;
}
```

---

### My Solution 


```js
function createArray(number)
{
  let newArray = [];  
  for(let counter = 1; counter <= number; counter++)
  {
    newArray.push(counter);
  }
  return newArray;
}
```


---
