# CodeWars JS Solutions

---

## Array plus array

I'm new to coding and now I want to get the sum of two arrays... Actually the sum of all their elements. I'll appreciate for your help.

P.S. Each array includes only integer numbers. Output is a number too.

### Given Code


```js
function arrayPlusArray(arr1, arr2) {
  return arr1 + arr2; //something went wrong
}
```

---

### My Solution 


```js
function arrayPlusArray(arr1, arr2)
 {
  let sum1=0;
  let sum2=0;
  for (let i=0; i<arr1.length; i++) 
  {
    sum1 += arr1[i];
  }
  for (let k=0; k<arr2.length; k++) 
  {
    sum2 += arr2[k];
  }
  return sum1 + sum2;
}
```


---

