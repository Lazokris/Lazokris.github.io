---
layout: essay
type: essay
title: Recognizing Patterns Can Be Beneficial
# All dates must be YYYY-MM-DD format!
date: 2021-12-02
labels:
- Computer Science
- Software Engineering
- Design Patterns
- Learning
---
<body style="background-color: floralwhite">
<h1 style="text-align: center">What Are Patterns?</h1>
<p style="font-family: monospace;">
There are patterns everywhere! Patterns are part of our daily lives; it helps us better comprehend the world by showing us how things are connected and organized. Successful Financial Analysis makes more money by being able to recognize patterns in a stock price chart, and Mathematicians use it to understand mathematical relationships and form generalizing theories. Similarly, Software Engineers also use pattern recognition to help them with their work of building softwares. In fact, after reading and learning about spoken language pattern recognition in a book called A Pattern Language by Christopher Alexander. It inspired a group of scientists called 'Gang of Four' to create a book called Design Patterns, which influence how software systems are designed today. 
</p>
<h1 style="text-align: center">Patterns In Software Development</h1>
<p style="font-family: monospace;">
Design Pattern is a general reusable solution to software development problems. It is a model/template that Software Engineers use in many different situations. It can help new and experienced Engineers speed up the development process by providing a proven development model obtained by trial and error of preceding Senior Engineers. Numerous design patterns have been produced since the creation of the Design Pattern, giving Engineers options to implement software designs. A good object-oriented design pattern has a meaningful descriptor that specifies its nature. It describes what the pattern does and when to apply the pattern, how the class and object structure solves that problem, and the trade-offs of using the pattern. Some popular Design Patterns are Creational Design Patterns; these design patterns create a suitable object for the problem. Structural Design Patterns; these design patterns are used to define objects' collections to obtain new functionality. Behavioral Design Patterns that deal with object interactions and Composite Design Patterns are described as partitioning design patterns.
</p>
<h1 style="text-align: center">An Example of Design Pattern <br/> (Factory Type)</h1>
<p style="font-family: monospace;">
The Factory Method Pattern is a Creational Pattern that creates objects without exposing the underlying logic. The method defines a class, but it uses subclasses to decide instantiations. Some advantages of the Factory Method are returning objects from different classes, returning multiple objects, and creating/building additional objects that can be hidden. Its trade-off is that it is more complicated to implement than an Object-Oriented constructor. Back in my Freshman year of college, my Classmate and I created a catch pokemon game in Java where the system would randomly generate Pokemon for users to catch. Our implementation used some similarities to Factory Method Pattern. We had an abstract parent class called Pokemon, which held the logic of representing the power, level, color, height, etc., of the Pokemon. And multiple extended children classes that are being instantiated.
</p>
<h1 style="text-align: center">An Example of Design Pattern <br/>(M-V-C)</h1>
<p style="font-family: monospace;">
The Model-View-Controller Pattern MVC is an example of a Composite Pattern. It separates the representation of information into three groups; view (The user interface), model (The data), and controller (The logic). MVC is popular in web development because it is a great structure for delegating work efficiently; interface specialists can handle the view, while DataBase experts can work on the model. Both usually handle the controller. As aspiring Software Engineers, my Classmate and I  in ICS 314 (Software Engineering 1) have learned how to implement Model-View-Controller Pattern to create a simple web application for a roommate finder. The App had multiple functioning pages, like Create Profile, Edit Profile, My Profile, etc. For this project, I have ensured the connection between view and model by creating logic that accesses the database whenever the users click on a designated button.
</p>
</body>
