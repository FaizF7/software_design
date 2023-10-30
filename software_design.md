
# Software Design Methodologies

## 1. What do we mean by coupling and cohesion in structured design?

Coupling is the degree of interdependence between different modules/components within a software system. In a well structure system modules should have low coupling, this makes the system more modular and easier to maintain, test and modify. If we have high coupling, then changes in one module can significantly affect other modules, making the system more complex and error-prone (especially when making changes).

Cohesion is the degree to which elements within a module/ component are related and serve a common purpose. Measures how well the responsisbilities and functions within a module are logically grouped. Well organised modules have high cohesion and are focused on a single, well defined task or responsibility (with each function contributing to the module's primary purpose). Low cohesion means that a single modules performs multiple, unrelated tasks and its elements lack a clear and common purpose.

We want low coupling and high cohesion.

## 2. Top-down vs bottom-up design

### Top-down design

Starts with a high level overview then breaking the system down into smaller parts.
Advantages:
Breaking problems into parts help us to identify what needs to be done.
At each step of refinement, new parts will become less complex and therefore easier to solve.
Parts of the solution may turn out to be reusable.
Breaking problems into parts allows more than one person to solve the problem.

### Bottom-up design

Individual components are specified in detail, this is common for OO languages such as Java or C++. Focus on data rather than procedure.
Function oriented design focuses on functions and procedures.


## 3. In which design methodology would a class diagram be most useful?

A class diagram is most useful for object-oriented design

## 4. 4 pillars of OO programming

1. Encapsulation - keeping code in modules separate from other modules by using classes.
2. Abstraction - hiding internal details or processes from the user
3. Inheritance - when a class inherits the methods and properties of another class, promotes code re-usability.
4. Polymorphism - when you have multiple methods with the same name but different implementations.

## 5. Strategy pattern in functional and object-oriented systems

The Strategy pattern is a behavioural design pattern that defines a family of algorithms, encapsulates them and makes them interchangeable. Allows the client  to choose an algorithm from a family of algorithms at runtime, wihout altering its structure.

In a functional system, The Stratgy Pattern involves defining functions or procedures as strategies. Client code may call functions based on selected strategies.

In an object-oriented system, The Strategy Pattern involves using classes and interfaces. Each strategy is encapsulated in a separate class that implements a common interface. The client code can switch between strategies by swapping objects that implement the same interface.

## 6. Design Methodology for an online payment system

I will use an Agile Design Methodology, specifically a variation of Iterative and Incremental Development. The reasons are as follows:

Adaptability: Agile methodologies are known for their adaptability to changing requirements. In a dynamic market where the payment system needs to cater to various sectors, the ability to quickly respond to changing needs is crucial.

Continuous Feedback: Agile methodologies promote continuous feedback from stakeholders, allowing the system to evolve based on actual user requirements and experiences, ensuring maximum market fit.

Incremental Delivery: By breaking the project into smaller increments or iterations, you can deliver a working product quickly and then add features incrementally, making it easier to penetrate multiple sectors without an exhaustive upfront design.

Cross-Functional Teams: Agile emphasizes cross-functional teams that can collaborate on various aspects of the system, which is beneficial for a system required to serve multiple sectors.

User-Centric Design: Agile places a strong emphasis on user-centric design and engagement. This approach helps in creating a user-friendly and sector-agnostic payment system.

By following Agile principles, the development team can remain flexible, responsive, and customer-oriented, making it the ideal choice for a payment system aiming for maximum market share across diverse sectors.