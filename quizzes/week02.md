# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A subprogram that performs a specific task when you invoke it.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility principle- a class should have one and only one reason to change.
open closed principle- objects should be open for extension but closed for modifications.
liskov substitution principle-every subclass or derived class should be substitutable for their base or parent class.
interface segregation principle- clients shouldnt be forced to rely on methods they dont use.
dependency inversion principle-depend on abstractions.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
fruit[2]
I know because array positions start at 0 and go up in count
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(...them);
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
an if statement is a conditional. an if statement is a block of JS code to be ran if the condition is true.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
this statement runs every time after the code block has been executed
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document object model- it accesses the document/html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitive, boolean, null, undefined, number, BigInt, string, symbol, and objects.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the names created in the function definition.
Arguments are the values the function receives by each parameter when the function is invoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are immutable(unable to be changed)

reference values are able to me manipulated(they can be changed)

```