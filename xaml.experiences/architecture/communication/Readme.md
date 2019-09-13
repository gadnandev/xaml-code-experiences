# Communication is **key**
One of the most common use cases while working with a client that has many parts, is agreeing on how they should 
communicate between each other. This might be an easy task when you are working alone, but very important when 
working with others.

A fairly large project can very fast turn into a big pile of spaghetti if one does not agree on a common way of doing it.

One of the most important aspects for me is that the way they communicate should be loosely coupled. This is because it can very fast become a circular dependency hell! 

Loosely coupled communication can be achieved in different ways. In this category I want to highlight the different ways I, together with my teams, have been doing it. 


## Application flow in examples
In each of the projects, this should be the purpose of the application:

![applicationMock]

[applicationMock]:applicationMock.png

A simple master-detail view where changing the hair color of a friend should force another part of the application to
 reevaluate how many friends that have black hair.

Here is a demonstration of the application without communication in place:
 
 ![demonstration]
 
 [demonstration]:applicationskeleton/gifs/demonstration.gif 

[This](applicationskeleton/) is the code skeleton for the projects.  