# OOPS


What are some other programming paradigms other than OOPs?

Programming paradigms refers to the method of classification of programming languages based on their features. There are mainly two types of Programming Paradigms:

Imperative Programming Paradigm
Declarative Programming Paradigm
Now, these paradigms can be further classified based:

1. Imperative Programming Paradigm: Imperative programming focuses on HOW to execute program logic and defines control flow as statements that change a program state. This can be further classified as:
a) Procedural Programming Paradigm: Procedural programming specifies the steps a program must take to reach the desired state, usually read in order from top to bottom.
b) Object-Oriented Programming or OOP: Object-oriented programming (OOP) organizes programs as objects, that contain some data and have some behavior.
c) Parallel Programming: Parallel programming paradigm breaks a task into subtasks and focuses on executing them simultaneously at the same time.

2. Declarative Programming Paradigm: Declarative programming focuses on WHAT to execute and defines program logic, but not a detailed control flow. Declarative paradigm can be further classified into:
a) Logical Programming Paradigm: Logical programming paradigm is based on formal logic, which refers to a set of sentences expressing facts and rules about how to solve a problem
b) Functional Programming Paradigm: Functional programming is a programming paradigm where programs are constructed by applying and composing functions.
c) Database Programming Paradigm: Database programming model is used to manage data and information structured as fields, records, and files.





How much memory does a class occupy?

Classes do not consume any memory. They are just a blueprint based on which objects are created. Now when objects are created, they actually initialize the class members and methods and therefore consume memory.


What Is The Use Of System Class In Java?

Answer: This question is among the most common Java interview questions for freshers. Java System class is one of the core classes. One of the easiest ways to log information for debugging is System.out.print() method. System class is final so we can’t subclass and override its behavior through inheritance.


What Is The Difference Between A Constructor And A Method In Java?

Answer:  A constructor is a special method that is used to create and initialize an object of a class. A method is a block of code that can be called multiple times within a class.


What Is A Lambda Expression In Java? 

A lambda expression in Java is a concise way to represent a block of code that can be passed around, like an object, and executed later. It provides a way to create anonymous functions, which can be used to implement functional interfaces, often replacing anonymous classes.


Which Class Is A Superclass Of All Classes?

Answer: Java.lang.The object is the root class for all the java classes and we don’t need to extend it. Every other java classes fall back under the object. All the different non-primitive types including arrays are inherited directly or indirectly from this class.



 Are there any limitations of Inheritance?

Yes, with more powers comes more complications. Inheritance is a very powerful feature in OOPs, but it has some limitations too. Inheritance needs more time to process, as it needs to navigate through multiple classes for its implementation. Also, the classes involved in Inheritance - the base class and the child class, are very tightly coupled together. So if one needs to make some changes, they might need to do nested changes in both classes. Inheritance might be complex for implementation, as well. So if not correctly implemented, this might lead to unexpected errors or incorrect outputs.



What are the various types of inheritance?

The various types of inheritance include:

Single inheritance
Multiple inheritances
Multi-level inheritance
Hierarchical inheritance
Hybrid inheritance


What is meant by static polymorphism?

Static Polymorphism is commonly known as the Compile time polymorphism. Static polymorphism is the feature by which an object is linked with the respective function or operator based on the values during the compile time. Static or Compile time Polymorphism can be achieved through Method overloading or operator overloading.


Who developed the first object-oriented programming language?   Alan Kay


Which among the following does not show or cannot be used, to show Polymorphism?
Static member function
Constructor Overloading
Member function overloading
Global member function

Which among the following functions represent the concept of Polymorphism?
Class member function
Virtual function
Inline function
Undefined function

Which feature of OOPs facilitates code reusability?
Abstraction
Encapsulation
Polymorphism
Inheritance


Which language among the following supports classes, but does not support the concept of Polymorphism?
C++ programming language
Java programming language
Ada programming language
C# programming language


Is the feature of OOPs which is responsible for binding data with their implementation as a single entity?
Polymorphism
Inheritance
Abstraction
Encapsulation

_______ was the first language to be developed as a purely object-oriented programming language?
Smalltalk

State true or false: A Java application can be created without implementing the OOPs concept.   -> false




Name some ways to overload a method.

1. Changing Parameter Number -> this method involves altering the number of parameters in different method signatures.

Here is an example in Java:

public int calculateSum(int a, int b) { // Two parameters
    return a + b;
}
public int calculateSum(int a, int b, int c) { // Three parameters
    return a + b + c;
}

2. Adapting Parameter Order -> Another overloading technique involves rearranging the order of parameters in methods to create unique signatures.
public double calculateArea(double length, double width) { // Length, then width
    return length * width;
}

public double calculateArea(double radius) { // Just radius for a circle
    return Math.PI * radius * radius;
}

3. Varying Parameter Type - You can define methods with different types of parameters to enable overloading.
public void printDetails(String name, int age) {
    System.out.println("Name: " + name + " , Age: " + age);
}

public void printDetails(int id) {
    System.out.println("ID: " + id);
}

public void printDetails(double salary) {
    System.out.println("Salary: " + salary);




What is cohesion in OOP?

Cohesion in OOP refers to how closely the methods and data within a single class are related to one another. A highly cohesive class is focused on a specific task or responsibility, making it easier to maintain, understand, and ensure reliability.
High cohesion is a desired attribute because it means that methods and properties within a class work together in a unified manner. In contrast, low cohesion indicates that a class has multiple, often unrelated responsibilities, making it harder to understand and maintain.



Compare inheritance vs. mixin vs. composition.

Inheritance, mixins, and composition are all techniques in object-oriented programming that deal with code reuse and the relationship between objects or classes.

Inheritance - > 
Definition: A class (subclass) inherits properties and behaviors from another class (superclass).
Relationship: "is-a" (e.g., a Car is a Vehicle).
Pros: Direct way to reuse code; establishes intuitive relationships.
Cons: Can lead to complex hierarchies; potential for over-generalization.

Mixin ->
Definition: A class that offers methods to other classes without being a standalone entity. Common in languages without multiple inheritance, such as Python.
Relationship: "kind-of-a" or "can-do-this" (e.g., a Helicopter can fly like a Bird).
Pros: Reuses code across classes; avoids deep inheritance issues.
Cons: Method source can be unclear; potential name clashes.

Composition ->
Definition: Building objects by combining simpler ones. Emphasizes a "has-a" relationship.
Relationship: "has-a" (e.g., a Car has an Engine).
Pros: Encourages modular design; components can be easily swapped.
Cons: May need more design upfront; can require more boilerplate code.
Many modern OOP design guidelines, like the composition over inheritance principle, suggest that unless there's a clear "is-a" relationship, it's often better to use composition as it's more flexible and leads to a more modular and maintainable design.



What are the limitations of OOPs?
Not suitable for solving small problems.
Without the proper class documentation, it is hard to understand the code.
Requires a lot of time to solve problems.
Required intensive testing.
The programmer should think of solving a problems in terms of objects.
