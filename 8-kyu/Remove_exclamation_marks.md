# CodeWars JS Solutions

---

## Remove exclamation marks

Write function RemoveExclamationMarks which removes all exclamation marks from a given string.

---

### Given Code


```js
function removeExclamationMarks(s) {
  return '';
}
```

---

### My Solution 


```js
function removeExclamationMarks(s) 
{
  let arrs=s.split("");
  for(let i=0;i<arrs.length;i++)
  {
    if(arrs[i].includes("!"))
    {
    arrs[i]="";
    }
  }
  return arrs.join("");
}
```


---

