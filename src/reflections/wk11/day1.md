# Week 11 | Day 1 Daily Journal

Afternoon Project: Burgershack API: 

Read Foundations of C# > C# Inheritance and answer the following questions

## *What does Inheritance accomplish for us in C#?*
Inheritance allows a class to inherit the traits of another class. It allows the reuse of code from a base class or parent to the derived class, or child.

## *How does Member inheritance work in C#? Does a class inherit all members of the base class?*
It doesn't inherit the base class' constructor or finalizers. Everything else is inherited but not everything may be visible.

## *How does accessibility affect inheritance?*
Private members are not visible to child classes. BUT, private members can actually be accessed in child classes if the child class is nested in the parent class.

Protected members are visible only in child classes, which means they're supposed to be used in inheritance. Internal members are visible in derived classes located in the same assembly as the parent class. Inherited public members are not only accessible, they're part of the public interface of the child class.




