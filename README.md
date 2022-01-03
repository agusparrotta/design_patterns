# Design Patterns
Design Patterns is the most essential part of Software Engineering, as they provide the general repeatable solution to a commonly occurring problem in software design.

Types:
1. Creational
2. Structural
3. Behavioral

## 1. Creational
Provides essential information regarding the **Class** instantiation or the **Object** instantiation. Class Creational Pattern and the Object Creational pattern is the major categorization of the Creational Design Patterns. **Class-creation** patterns use **inheritance** effectively in the instantiation process, and **object-creation** patterns use **delegation** effectively to get the job done.

- Factory
- Abstract factory
- Builder
- Prototype
- Singleton

### 1.1. Factory
Allows an interface or a class to create an object, but lets subclasses decide which class or object to instantiate.

- Best way to create an object.
- Objects are created without exposing the logic to the client (same common interface).

### 1.2. Abstract factory
Allows you to produce the families of related objects without specifying their concrete classes.

- Easiest way to produce a similar type of many objects.
- It provides a way to encapsulate a group of individual factories. Basically, here we try to abstract the creation of the objects depending on the logic, business, platform choice, etc.

### 1.3. Builder
Aims to separate the construction of a complex object from its representation so that the same construction process can create different representations.

- Allows you to construct complex objects step by step. Using the same construction code, we can produce different types and representations of the object easily.
- Provides flexibility to the solutions to various object creation problems.

### 1.4. Prototype
Aims to reduce the number of classes used for an application. It allows you to copy existing objects independent of the concrete implementation of their classes. Generally, here the object is created by copying a prototypical instance during run-time.

- Highly recommended to use it when the object creation is an expensive task in terms of time and usage of resources and already there exists a similar object.
- Provides a way to copy the original object and then modify it according to our needs.

### 1.5. Singleton
It is a way to provide one and only one object of a particular type. It involves only one class to create methods and specify the objects.

- Example: Database connectivity. When each object creates a unique Database Connection to the Database, it will highly affect the cost and expenses of the project. So, it is always better to make a single connection rather than making extra irrelevant connections.

## 2. Structural
Are about organizing different classes and objects to form larger structures and provide new functionality while keeping these structures flexible and efficient. Mostly they use Inheritance to compose all the interfaces. It also identifies the relationships which led to the simplification of the structure.

- Composite
- Decorator
- Proxy
- Adapter
- Bridge

## 3. Behavioral
Are about identifying the common communication patterns between objects and realize these patterns. These patterns are concerned with algorithms and the assignment of responsibilities between objects.

- Iterator
- Observer
- Visitor
- Strategy
- Chain of responsibility


# References
See [this post](https://www.geeksforgeeks.org/python-design-patterns/) for more information.