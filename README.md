# 📘 Programming Paradigms & Java Interview Concepts

A clean and organized reference covering major programming paradigms and essential Java/OOPs concepts commonly asked in interviews.

---

## 📑 Table of Contents

1. [What are some other programming paradigms other than OOPs? Programming paradigms refers to the method of classification of programming languages based on their features.](#paradigms)
2. [How much memory does a class occupy?](#memory-class)
3. [What Is The Use Of System Class In Java?](#system-class)
4. [What Is The Difference Between A Constructor And A Method In Java?](#constructor-vs-method)
5. [What Is A Lambda Expression In Java?](#lambda)
6. [Which Class Is A Superclass Of All Classes?](#superclass)
7. [Are there any limitations of Inheritance?](#limitations-inheritance)
8. [What are the various types of inheritance?](#types-inheritance)
9. [What is meant by static polymorphism?](#static-polymorphism)
10. [Who developed the first object-oriented programming language?](#who-developed-oop)
11. [Which among the following does not show Polymorphism?](#not-polymorphism)
12. [Which functions represent the concept of Polymorphism?](#functions-polymorphism)
13. [Which feature of OOPs facilitates code reusability?](#code-reusability)
14. [Which language supports classes but not polymorphism?](#language-no-polymorphism)
15. [Which OOP feature binds data with implementation?](#binding-feature)
16. [Which was the first purely object-oriented programming language?](#first-pure-oop)
17. [True/False: A Java application can be created without OOPs](#java-oops-true-false)
18. [Name some ways to overload a method.](#overload-method)
19. [What is cohesion in OOP?](#cohesion)
20. [Compare inheritance vs mixin vs composition.](#inheritance-mixin-composition)
21. [What are the limitations of OOPs?](#limitations-oops)

---

# 🧠 MAIN CONTENT

---

<a id="paradigms"></a>
## 1. What are some other programming paradigms other than OOPs?
<details><summary>Click to expand</summary>

Programming paradigms refers to the method of classification of programming languages based on their features.  
There are mainly two types:

### Imperative Programming Paradigm
HOW to execute the program logic.

Includes:
- Procedural Programming
- Object-Oriented Programming
- Parallel Programming

### Declarative Programming Paradigm
WHAT to execute, not HOW.

Includes:
- Logical programming  
- Functional programming  
- Database programming  
</details>

---

<a id="memory-class"></a>
## 2. How much memory does a class occupy?
<details><summary>Click to expand</summary>

Classes do not consume memory.  
Objects created from the class consume memory.

</details>

---

<a id="system-class"></a>
## 3. What Is The Use Of System Class In Java?
<details><summary>Click to expand</summary>

System.out.print() is used for debugging.  
System class is `final`, so it cannot be subclassed.

</details>

---

<a id="constructor-vs-method "></a>
## 4. What Is The Difference Between A Constructor And A Method In Java?
<details><summary>Click to expand</summary>

- Constructor initializes an object.  
- Method is reusable logic that can be called multiple times.

</details>

---

<a id="lambda"></a>
## 5. What Is A Lambda Expression In Java?
<details><summary>Click to expand</summary>

A lambda expression represents block of code that can be passed like an object.  
Used to implement functional interfaces.

</details>

---

<a id="superclass"></a>
## 6. Which Class Is A Superclass Of All Classes?
<details><summary>Click to expand</summary>

`java.lang.Object` is the root of all classes.

</details>

---

<a id="limitations-inheritance"></a>
## 7. Are there any limitations of Inheritance?
<details><summary>Click to expand</summary>

- Time-consuming (deep navigation)  
- Tightly coupled classes  
- Complex to implement  
- Can cause unexpected errors  

</details>

---

<a id="types-inheritance"></a>
## 8. What are the various types of inheritance?
<details><summary>Click to expand</summary>

- Single  
- Multiple  
- Multilevel  
- Hierarchical  
- Hybrid  

</details>

---

# 🆕 NEW CONTENT BELOW (ADDED EXACTLY AS YOU GAVE)

---

<a id="static-polymorphism"></a>
## 9. What is meant by static polymorphism?
<details><summary>Click to expand</summary>

Static Polymorphism is compile-time polymorphism.  
It binds a function/operator based on values at compile time.  
Achieved through:
- Method overloading  
- Operator overloading  

</details>

---

<a id="who-developed-oop"></a>
## 10. Who developed the first object-oriented programming language?
<details><summary>Click to expand</summary>

**Alan Kay**

</details>

---

<a id="not-polymorphism"></a>
## 11. Which among the following does NOT show Polymorphism?
<details><summary>Click to expand</summary>

- Static member function ❌  
- Constructor Overloading ✔  
- Member function overloading ✔  
- Global member function ❌  

</details>

---

<a id="functions-polymorphism"></a>
## 12. Which functions represent the concept of Polymorphism?
<details><summary>Click to expand</summary>

- Class member function  
- Virtual function ✔  
- Inline function  
- Undefined function  

</details>

---

<a id="code-reusability"></a>
## 13. Which feature of OOPs facilitates code reusability?
<details><summary>Click to expand</summary>

✔ **Inheritance**

</details>

---

<a id="language-no-polymorphism"></a>
## 14. Which language supports classes but not polymorphism?
<details><summary>Click to expand</summary>

**Ada programming language**

</details>

---

<a id="binding-feature"></a>
## 15. Which OOP feature is responsible for binding data with implementation?
<details><summary>Click to expand</summary>

✔ **Encapsulation**

</details>

---

<a id="first-pure-oop"></a>
## 16. Which was the first purely object-oriented programming language?
<details><summary>Click to expand</summary>

**Smalltalk**

</details>

---

<a id="java-oops-true-false"></a>
## 17. True/False: A Java application can be created without OOPs?
<details><summary>Click to expand</summary>

**False**

</details>

---

<a id="overload-method"></a>
## 18. Name some ways to overload a method.
<details><summary>Click to expand</summary>

### ✔ 1. Changing Parameter Number  
```java
public int calculateSum(int a, int b) { return a + b; }
public int calculateSum(int a, int b, int c) { return a + b + c; }
