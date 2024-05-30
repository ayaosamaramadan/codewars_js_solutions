# CodeWars JS Solutions

---

## Remove First and Last Character

It's pretty straightforward. Your goal is to create a function that removes the first and last characters of a string. You're given one parameter, the original string. You don't have to worry about strings with less than two characters.

---

### Given Code


```js
function removeChar(str){
 //You got this!
 
};


```

---

### My Solution 


```js
function removeChar(str)
{
  let arrstr=[];
  let str1=str.split('');   
  for (let i =0; i<str1.length; i++)
  {
    if (i==0 || i==str1.length-1)
    {}
    else
    {
      arrstr.push(str1[i]);
    }
  }
  return arrstr.join('');
}
```


---

