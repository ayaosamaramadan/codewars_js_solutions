# CodeWars JS Solutions

---

## Find numbers which are divisible by given number

Complete the function which takes two arguments and returns all numbers which are divisible by the given divisor. First argument is an array of numbers and the second is the divisor.

Example(Input1, Input2 --> Output)
[1, 2, 3, 4, 5, 6], 2 --> [2, 4, 6]


---

### Given Code


```js
function divisibleBy(numbers, divisor){
}
```

---

### My Solution 


```js
 function divisibleBy(numbers, divisor)
{
return numbers.filter((x)=>x%divisor===0);
}
```


---

