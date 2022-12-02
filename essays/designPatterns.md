---
layout: essay
type: essay
title: "The Hitchhikers book to design patterns for humans"
# All dates must be YYYY-MM-DD format!
date: 2022-12-01
published: true
labels:
  - design patterns
--- 
<h2> Great beginnings </h2>
<div>
<img src="https://media.tenor.com/OywDv9lFQaYAAAAC/start-bugs-bunny.gif" width="200" style="float:left; margin: 10px">
Lets get right into the grove of things, in general a design pattern is a simple solution to a common problem in software design. It really isn't a finished product that can be completely translated into code, but instead think of it as a sort of template or skeleton to solve problems in different situations. 
</div>

<br>
<h2> The GANG of Design Patterns </h2>
In the term of software engineering, there are three different types of design patterns:

* Creational Design Patterns
  * This patterns provides various mechanisms which will increase flexibility and reusable code
* Structural Design Patterns
  * this shows how to create objects and classes into larger structures, while keeping these structures efficient and flexible
* Behavioral Design Patterns 
  * this pattern is concerned with algorithm and the assignment of responsibilities.

    
Now that we have a basic grasp on what the types Design Patterns are, lets now briefly explain what each method does.

Starting with **Creational Design Patterns**
* **Abstract Factory**
  * This is the creation of instances of multiple families of classes
* **Builder**
  * This separates object construction and its representation
* **Factory Method**
  * This creates an instance of several derived classes
* **Prototype**
  * This is a fully initialized instance that is copied or cloned
* **Singleton**
  * Simply its a class where there is only one single instance

**Structural Design Patterns**
* **Adapter**
  *  This matches the interfaces of different classes
* **Bridge**
  *   This separates an objects interface from its implementation
* **Composite**
  * This is a trees structure of simple and composite objects
* **Decorator**
  * This adds responsibilities to objects dynamically
* **Facade**
  * This is a single class that represents a entire subsystem
* **Flyweight**
  * an instance that is used for efficient sharing
* **Private Class Data**
  * This restricts accessor/mutator access
* **Proxy**
  * Basically an object just representing another object

**Behavioral Design Patterns**
* **Chain of Responsibility**
  * a way of passing a request between a chain of objects
* **Command**
  * enclose a command request as an object
* **Interpreter**
  * a way to include language elements in a program
* **Mediator**
  * this is the communication between classes
* **Null Object**
  * this is a default value of an object
* **Observer**
  * the way of notifying change to classes
* **State**
  * Alter an object's behavior when its state changes
* **Strategy**
  * this encloses an algorithm inside a class
* **Template Method**
  * this defers the exact steps of an algorithm to a subclass
* **Visitor**
  * This would defines new operation to a class without a change

<h2> Actual food for thought </h2>

<center><img src="https://thumbs.gfycat.com/WhimsicalOpulentAruanas-size_restricted.gif" width="400" style="margin: 10px; align-items: center"> </center>

Im not too sure if its just me, but I can envision some design patterns relating to food. In the terms of Abstract Factory I can envision it being used for a custom meal planner. In general we want to create families of Diets with their own behavior for generating things like grocery lists and other stuff without specifying a class. Another example would be with Proxy, it could be used in a Food Bank Donation Processor, the food bank processor could use an off the shelf system for accepting food donations, but we want to access this system while maintaining the same interface, so in this case we would use a proxy to log the use of resource and prevent certain items from being donated.

<h2> Exposing the Truth </h2>
Sadly before doing the research and writing this essay I was not too sure what Design Patterns were. I initially thought it was similar to coding standards and the thought of it being templates to solutions flew right over my head.

After doing the research I was able to get a good grasp on what design patterns are and what they are used for. Through this research I can gladly say I have done some of these methods while my time as a programmer. In my sophomore year I took a OOP (Object Oriented Programming) class and for my final project we had to create a game using C++. In this case we used the Factory Method to create different types playable classes (mage, warrior, theif) from a base character class.

