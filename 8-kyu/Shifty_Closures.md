# CodeWars JS Solutions

---

## Shifty Closures

Functional closures can get overly attached. Set them straight!

Why doesn't greetAbe() actually greet Abe?



---

### Given Code


```js

let name = 'Abe'

const greetAbe = () => 'Hello, ' + name + '!'

name = 'Ben'

const greetBen = () => 'Hello, ' + name + '!'

```

---

### My Solution 


```js

const greetAbe =() => 'Hello, Abe!'
const greetBen = () => 'Hello, Ben!'

```


---
