# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Used to organize code into groups when you are using multiple libraries
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value type whereas Classes are reference type
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
string
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
it is an indication of what start should be returning
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract is preventing the ability to modify this instance of the class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
because car is abstracted, virtual is used to allow it to be override
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be visible within that method or class.
```