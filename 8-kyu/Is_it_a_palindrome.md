# CodeWars JS Solutions

---

## Is it a palindrome?

Write a function that checks if a given string (case insensitive) is a palindrome.

A palindrome is a word, number, phrase, or other sequence of symbols that reads the same backwards as forwards, such as madam or racecar.

---

### Given Code


```js
function isPalindrome(x) {
  // your code here
}
```

---

### My Solution 


```js
function isPalindrome(x) 
{
  let x1=x.split("");
  let i = 0;
  let j = x1.length -1;
  while(i<j)
  {
    if(x1[i].toLowerCase() ===x1[j].toLowerCase())
    {
      i++;
      j--;
    }
    else 
    {
      return false;
    }
  }
  return true;
}
```


---

