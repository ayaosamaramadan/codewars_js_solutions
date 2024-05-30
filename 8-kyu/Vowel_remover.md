# CodeWars JS Solutions

---

## Vowel remover

Create a function called shortcut to remove the lowercase vowels (a, e, i, o, u ) in a given string.

Examples
"hello"     -->  "hll"
"codewars"  -->  "cdwrs"
"goodbye"   -->  "gdby"
"HELLO"     -->  "HELLO"
don't worry about uppercase vowels
y is not considered a vowel for this kata

---

### Given Code


```js
function shortcut (string) {
  return '';
}
```

---

### My Solution 


```js
function shortcut(string)
{
  arrstring = string.split("");
  newarr = [];
  for (let i = 0; i < arrstring.length; i++)
  {
    if (arrstring[i] !== "e" && arrstring[i] !== "o" && arrstring[i] !== "a" &&arrstring[i] !== "i" && arrstring[i] !== "u")
    {
      newarr.push(arrstring[i]);  
    }
  }
  return newarr.join("");
}
```


---

