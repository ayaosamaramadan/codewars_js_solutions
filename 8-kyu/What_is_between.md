# CodeWars JS Solutions

---

## What is between?

Complete the function that takes two integers (a, b, where a < b) and return an array of all integers between the input parameters, including them.

For example:

a = 1
b = 4
--> [1, 2, 3, 4]


---

### Given Code


```js
function between(a, b) {
  // your code here
}
```

---

### My Solution 


```js
function between(a, b) 
{
    return Array(b-a+1).fill(a).map((a,i)=>a+i);  
}
```


---