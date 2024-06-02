## Object Oriented Programming Interview Prep

> What is Object Oriented Programming?

> What is Class?

Class is the code describes an entity

> What is Object?

the actual instance of Object

An **instance** is a specific realization of any object in object-oriented programming.

> Members

The members of a type include all methods, fields, constants, properties, and events. In C#, there are no global variables or methods as there are in some other languages. Even a program's entry point, the Main method, must be declared within a class or struct (implicitly when you use top-level statements).

The following list includes all the various kinds of members that may be declared in a class, struct, or record.

- Fields
- Constants
- Properties
- Methods
- Constructors
- Events
- Finalizers
- Indexers
- Operators
- Nested Types

> Data Members

The data that the class manages

- each object has its own copy of the data member except static

> Methods or Member functions

The operations that can be performed on an object of this type.

- are called with an object("the calling object", "the caller")


> Fields

> Access Modifiers | Privileges | Accessibility

Some methods and properties are meant to be called or accessed from code outside a class or struct, known as **client code.** Other methods and properties might be only for use in the class or struct itself. It's important to limit the accessibility of your code so that only the intended client code can reach it. You specify how accessible your types and their members are to client code by using the following access modifiers:

- public
- protected
- internal
- protected internal
- private
- private protected.

> Constructor

> Types of Constructor

> Copy Constructor

Allow us to define how my object will be copied

> this

is the pointer refers to the calling object or current instance of the class.

> Pillars of OOP

> What is Encapsulation?

Encapsulation is sometimes referred to as the first pillar or principle of object-oriented programming. A class or struct can specify how accessible each of its members is to code outside of the class or struct. Methods and variables that aren't intended to be used from outside of the class or assembly can be hidden to limit the potential for coding errors or malicious exploits. For more information, see the Object-oriented programming tutorial.


Hiding the internal state and functionality of an object and only allowing access through a public set of functions.


**OR**

Encapsulation refers to bundling data with methods that can operate on that data within a class.



> What is Inheritance?

Inheritance enables you to create new classes that reuse, extend, and modify the behavior defined in other classes. The class whose members are inherited is called the base class, and the class that inherits those members is called the derived class. A derived class can have only one direct base class. However, inheritance is transitive. If ClassC is derived from ClassB, and ClassB is derived from ClassA, ClassC inherits the members declared in ClassB and ClassA.


> Types of Inheritance

> Base Class

> Child Class | Derived Class

> What is Polymorphism?

Polymorphism is the ability to treat different kind of objects as same.
Example: We want to hold and manage objects of either type with having them differently (e.g. Person and student, Dog and cat)

**OR**

Polymorphism is a Greek word that means "many-shaped" and it has two distinct aspects:

- At run time, objects of a derived class may be treated as objects of a base class in places such as method parameters and collections or arrays. When this polymorphism occurs, the object's declared type is no longer identical to its run-time type.

- Base classes may define and implement virtual methods, and derived classes can override them, which means they provide their own definition and implementation. At run-time, when client code calls the method, the CLR looks up the run-time type of the object, and invokes that override of the virtual method. In your source code you can call a method on a base class, and cause a derived class's version of the method to be executed.

> Types of Polymorphism

> Virtual functions

> Pure Virtual functions

> What is Abstraction?

> What are Abstract Classes


> What are static members and static methods 

> What are Generics


### Tricky Part

> OOP vs functional

> Class VS Object

> Shallow vs deep copy

> Method VS function

> Inheritance VS composition

> Run time VS compile time Polymorphism

> Abstract Class VS interface

> Interface VS class

> Member VS Field VS Method

> Static Vs Non Static

> Pass by value VS pass by reference

> mutable VS immutable


### Advance

> Design Patterns

> SOLID Principles in depth

> Singleton Pattern

> Template recurring pattern

> Proxy pattern

> Builder Pattern

> Factory Pattern
 

### Key Terms

> Single Responsibility

A class should only have a single responsibility.

> Public 

Accessed by anyone

> Protected

Only Accessed by it self and derived class

> Private

Only Accessed by the class it self


> Rule of zero

> Duck typing
