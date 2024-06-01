# CodeWars JS Solutions

---

## Barking mad

Teach snoopy and scooby doo how to bark using object methods. Currently only snoopy can bark and not scooby doo.

snoopy.bark(); // return "Woof"
scoobydoo.bark(); // undefined
Use method prototypes to enable all Dogs to bark.
P.S. Each array includes only integer numbers. Output is a number too.

### Given Code


```js
function Dog (breed) {
  this.breed = breed;
}

var snoopy = new Dog("Beagle");

snoopy.bark = function() {
  return "Woof";
};

var scoobydoo = new Dog("Great Dane");

```

---

### My Solution 


```js
function Dog (breed) {
  this.breed = breed;
}

var snoopy = new Dog("Beagle");
Dog.prototype.bark = function() {
  return "Woof";
};

var scoobydoo = new Dog("Great Dane");


```


---

