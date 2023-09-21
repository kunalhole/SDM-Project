## 1.DRY (Don't Repeat Yourself)
### The DRY principle stands for "Don't Repeat Yourself." It's a fundamental concept in software design and programming. The principle is centered on reducing the repetition of software patterns, replacing duplications with abstractions, and ensuring that every piece of knowledge or logic has a single, authoritative, unambiguous representation within a system


## 2.HOLLYWOOD
### The basic idea of the HOLLYWOOD is that the user or developer provides some customization (like overriding methods or implementing interfaces), and the framework itself decides when and how to call or use these customizations. It helps in inverting the control flow: instead of the developer deciding when to perform an action, the framework decides.


## 3.SOLID:
## S : Single Responsibility Principle
## O : Open for extension, close for modification 
## L : Likove's Substitution Principl
## I : Interface Segregation Principle 
## D : Dependency Inversion Principle
### DRY Software Design Principle

Default (GPT-3.5)

User
Dry principal of software design 

ChatGPT
The DRY principle stands for "Don't Repeat Yourself." It's a fundamental concept in software design and programming. The principle is centered on reducing the repetition of software patterns, replacing duplications with abstractions, and ensuring that every piece of knowledge or logic has a single, authoritative, unambiguous representation within a system.

In practical terms, following the DRY principle means:

Avoiding duplicate code by abstracting out common functionality.
Using data normalization to prevent redundant data.
Reducing the risk of introducing bugs because there's less code to maintain and fewer places for errors to hide.
Making the codebase easier to understand and maintain.
By adhering to the DRY principle, developers can create more flexible, maintainable, and scalable software.




User
Hollywood 

ChatGPT
Hollywood is a neighborhood in the central region of Los Angeles, California, most notable for its role as the entertainment industry's historical hub. It has various iconic landmarks and associations, such as:

**



User
Hollywood principal in software 

ChatGPT
Ah, I see the confusion. You're referring to the "Hollywood Principle," which is a design principle in software. It's often summarized as "Don't call us, we'll call you."

The Hollywood Principle is commonly used in frameworks and libraries. The basic idea is that the user or developer provides some customization (like overriding methods or implementing interfaces), and the framework itself decides when and how to call or use these customizations. It helps in inverting the control flow: instead of the developer deciding when to perform an action, the framework decides.

The most common application of the Hollywood Principle is in the Inversion of Control (IoC) containers and Dependency Injection, which are fundamental to many modern software frameworks.

By following this principle, systems can become more modular and easier to manage, as the high-level code is decoupled from the low-level code, making it easier to modify one without affecting the other.




User
Solid 

ChatGPT
"SOLID" is an acronym that represents five design principles intended to make software designs more understandable, flexible, and maintainable. They are foundational principles in object-oriented design and programming. Here's a brief overview:

S - Single Responsibility Principle (SRP): A class should have only one reason to change. This means a class should have only one job or responsibility.

O - Open/Closed Principle (OCP): Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification. This suggests that the behavior of a module can be extended without modifying its source code.

L - Liskov Substitution Principle (LSP): Subtypes must be substitutable for their base types. This means that objects of a derived class should be able to replace an object of the base class without affecting the correctness of the program.

I - Interface Segregation Principle (ISP): Clients should not be forced to depend on interfaces they do not use. This means that a class shouldn't be forced to implement interfaces it doesn't use. Instead of one fat interface, many small and specific interfaces are preferred.

D - Dependency Inversion Principle (DIP): High-level modules should not depend on low-level modules. Both should depend on abstractions. This principle inverts the typical design pattern of high-level modules depending on the implementation of low-level modules.
