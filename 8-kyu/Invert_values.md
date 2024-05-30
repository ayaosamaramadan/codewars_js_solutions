# CodeWars JS Solutions

---

## Invert values

Given a set of numbers, return the additive inverse of each. Each positive becomes negatives, and the negatives become positives.

[1, 2, 3, 4, 5] --> [-1, -2, -3, -4, -5]
[1, -2, 3, -4, 5] --> [-1, 2, -3, 4, -5]
[] --> []
You can assume that all values are integers. Do not mutate the input array.

---

### Given Code


```js
function invert(array) {
   return ;
}
```

---

### My Solution 


```js
function invert(arr)
{
      let newarr = [];
      for(let i=0; i < arr.length; i++)
      {
        if (arr[i] > 0) 
        {
          newarr.push(-arr[i]);
        } 
        else 
        {
          newarr.push(-arr[i]);
        }
      }
      return newarr;
}
```


---

