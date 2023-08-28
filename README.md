**The Gang of Four Design Patterns**

**CREATIONAL PATTERNS**:
These patterns deal with object creation mechanisms, trying to abstract the instantiation process and make it more flexible and dynamic.
Singleton: Ensures that a class has only one instance and provides a global point of access to it.
Factory Method: Defines an **interface** for creating objects, but lets subclasses decide which class to **instantiate**.
Abstract Factory: Provides an **interface** for creating **families** of related or dependent objects without specifying their **concrete** classes.
Builder: **Separates** the construction of a **complex** object from its **representation**, allowing the **same construction process** to create **various **representations**.
Prototype: **Specify** the kinds of objects to create using a prototypical instance, and then create new objects by **copying this prototype**.

**STRUCTURAL PATTERNS**:
These patterns are concerned with object **composition** to form larger structures while keeping these structures flexible and efficient.
Adapter: Allows **objects with **incompatible interfaces*** to work together by providing a **wrapper** that **converts** one interface into another.
Decorator: **Dynamically** adds **responsibilities** to objects by **wrapping** them with **additional behaviors**.
Bridge: **Decouples** an **abstraction** from its **implementation** so that both can **vary independently**.
Composite: **Composes** objects into **tree structures** to represent **part-whole hierarchies**, allowing **clients** to *treat individual objects and compositions uniformly*.
Facade: Provides a ***unified** interface* to a **set of interfaces** in a **subsystem**, making it easier to use.
Flyweight: Shares **objects** to **support** a **large number** of **fine-grained objects** efficiently.
Proxy: Provides a **surrogate** or **placeholder** for another object to **control access** to it.

**BEHAVIORAL PATTERNS**:

These patterns focus on **communication** between objects, defining the **interactions** and **responsibilities** between them.
Chain of Responsibility: **Passes** a request along a **chain** of **handlers**, allowing **more than one object** to **process the request**.
Command: **Turns** a **request** into a **standalone object**, ***containing all the information*** *about the request.*
Interpreter: Provides a *way* to **evaluate** **language grammar or expressions.**
Iterator: Provides a way to **access** the **elements** of an **aggregate object** ***sequentially*** *without exposing* its *underlying representation*.
Mediator: **Reduces direct connections** between objects by introducing a mediator object that **coordinates interactions** between them.
Memento: Allows an object's **state to be captured** and **restored** *without exposing its internal structure*.
Observer: Defines a **dependency** between objects so that when one object **changes state,** all its ***dependents** are **notified** and **updated** **automatically**.*
State: Allows an object to **change its behavior when its internal state changes**.
Strategy: Defines **a family of algorithms,** **encapsulates each one**, and **makes them interchangeable**.
Template Method: Defines the **structure of an algorithm**, **allowing its steps to be overridden** by subclasses.
Visitor: Lets you **add further operations to objects** ***without having to modify them***.
