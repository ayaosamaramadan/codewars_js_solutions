# CodeWars JS Solutions

---

## Welcome to the City


Create a method that takes as input a name, city, and state to welcome a person. Note that name will be an array consisting of one or more values that should be joined together with one space between each, and the length of the name array in test cases will vary.

Example:

['John', 'Smith'], 'Phoenix', 'Arizona'
This example will return the string Hello, John Smith! Welcome to Phoenix, Arizona!


---

### Given Code


```js
function sayHello( name, city, state ) {
}
```

---

### My Solution 


```js
function sayHello( name, city, state ) 
{
     let newname= name.join(' ');
   return "Hello, "+ newname +"! "+"Welcome to " +city+", " +state+"!";

}
```


---