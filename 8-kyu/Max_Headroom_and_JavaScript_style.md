
# CodeWars JS Solutions

---

## Max Headroom and JavaScript style

Shouldn't the two functions getMax1 and getMax2 be equivalent and return the same value? Can you spot a problem and fix it? Can you learn something about JavaScript style in this kata?


---

### Given Code


```js
function getMax1()
{
  var max = 
  {
   name: 'Max Headroom'
  }
  return max;
}

function getMax2()
{
  return
  {
    name: 'Max Headroom'
  }
}
```

---

### My Solution 


```js
const getMax1=getMax2=()=>({name:'Max Headroom'});

```


---

