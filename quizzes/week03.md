# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
encapsulation and message passing
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
console.log(property)?
staff.property?
return property?

staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
The method of creating layers within your code which you can either make private or public along with how our code is manipulated. We can make certain parts of code unchangeable so it doesn't effect our code.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility principle 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
the class is the parent that has unchangeable data and an instance of a class is the ability to make adjustments without effecting the overall data and its action.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a fake stand in object for the real object
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
to help us create clean code(help us arrange our code a similar way, we can build bigger applications and have a nice order.)
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller is the waiter who comes and takes our order and gives it to the cooks aka service. takes in user input.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service is the cook who goes into freezer to get the ingredients (takes away from the contents). performs business logic.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
what the data inside the appstate is supposed to look like i.e what does the data have... name,price, quantity.
```
