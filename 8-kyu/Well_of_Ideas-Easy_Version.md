# CodeWars JS Solutions

---

## Well of Ideas - Easy Version

For every good kata idea there seem to be quite a few bad ones!

In this kata you need to check the provided array (x) for good ideas 'good' and bad ideas 'bad'. If there are one or two good ideas, return 'Publish!', if there are more than 2 return 'I smell a series!'. If there are no good ideas, as is often the case, return 'Fail!'.

---

### Given Code


```js
function well(x){

}
```

---

### My Solution 


```js
function well(x)
{
  let theFilter = x.filter(i => i === 'good').length;
  return theFilter==0?
  'Fail!':
  theFilter<=2 ?
  'Publish!': 
  'I smell a series!';
}
```


---