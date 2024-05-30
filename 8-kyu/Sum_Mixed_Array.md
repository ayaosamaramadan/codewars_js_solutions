# CodeWars JS Solutions

---

## Sum Mixed Array

Given an array of integers as strings and numbers, return the sum of the array values as if all were numbers.

Return your answer as a number.

---

### Given Code


```js
function sumMix(x){

}
```

---

### My Solution 


```js
function sumMix(x){
  return x.map((x)=> x==x.toString()?Number(x):x).reduce((acc , cur)=>acc+cur);
    
}
```


---

