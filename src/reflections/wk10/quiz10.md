# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is designed for providing a way to keep one set of names separate from another. The class names declared in one namespace does not conflict with the same class names declared in another.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are value types while classes are reference types. Structs can be instantiated without using a new operator. A struct cannot inherit from another struct or class, and it cannot be the base of a class
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
the access modifier is public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
that it is data type string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
prevents the inheritance of a class or certain class members that were previously marked virtual
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It modifies the method Start() and would allow it to be overridden in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
 private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only code in the same class
```