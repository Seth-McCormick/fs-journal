# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
to define the project you are working on so it can see it's scope
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class is a reference type - reference types are allocated on the heap and garbage-collected

struct is a value type -  value types are allocated either on the stack or inline in containing types and deallocated when the stack unwinds or when their containing type gets deallocated
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void 
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
 the thing being modified has a missing or incomplete implementation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
the purpose is that the keyword is used to modify a method declaration and allow for it to be overridden in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, internal, and private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the body of that class or method 
```