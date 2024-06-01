# CodeWars JS Solutions

---

## Name Shuffler

Write a function that returns a string in which firstname is swapped with last name.

Example(Input --> Output)

"john McClane" --> "McClane john"

---

### Given Code


```js
function nameShuffler(str){
  //Shuffle It
}
```

---

### My Solution 


```js
function nameShuffler(str)
{let str1=str.split(' ').reverse().join(" ").toString(); 
   return str1;
}
```


---

