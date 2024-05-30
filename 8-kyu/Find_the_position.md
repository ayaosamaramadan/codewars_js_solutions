# CodeWars JS Solutions

---

## Find the position!


When provided with a letter, return its position in the alphabet.

Input :: "a"

Ouput :: "Position of alphabet: 1"

---

### Given Code


```js
function position(letter){
//Write your own Code!
}
```

---

### My Solution 


```js
function position(letter)
{
  alp="abcdefghijklmnopqrstuvwxyz";
  for(i=1;i<=alp.length;i++)
  {
    if(alp[i-1]==letter)
    {
      return `${"Position of alphabet: "+ `${i}`}`;
    }
  }
}
```


---

