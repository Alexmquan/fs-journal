# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace is used to set a scope that contains a set of related objects. It is at the head of every C# document.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
The difference between a class and a struct are that structs have more limitations.
Structs are value types where a class is a reference type. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
A void method returns an instance of a class and no return type.
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
The access modifier of the Start() method is public.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the string is the return type value.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
'abstract' is preventing other objects from being created from the class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The purpose of virtual is to allow the method to be overridden.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
The four types of access modifiers in C# are public, private, internal, and protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The only thing that can access a class or method that is set to private are within the class in which they are declared.
```