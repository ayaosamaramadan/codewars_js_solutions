# CodeWars JS Solutions

---

## Double Char

Given a string, you have to return a string in which each character (case-sensitive) is repeated once.

Examples (Input -> Output):
* "String"      -> "SSttrriinngg"
* "Hello World" -> "HHeelllloo  WWoorrlldd"
* "1234!_ "     -> "11223344!!__  "

---

### Given Code


```js
function doubleChar(str) {
  // Your code here
}
```

---

### My Solution 


```js
function doubleChar(str) 
{
      return str.split('')
      .map(function (c) 
      {
        return c + c;
      }
      ).join('');
}
```


---

