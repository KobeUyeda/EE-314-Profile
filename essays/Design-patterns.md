---
layout: essay
type: essay
title: "Design Patterns and Their Uses"
# All dates must be YYYY-MM-DD format!
date: 2023-11-28
published: true
labels:
  - Engineering
  - Software Design
---

<img width="100%" class="rounded float-start pe-4" src="https://m.media-amazon.com/images/I/51uxEj502bL._AC_UF1000,1000_QL80_.jpg">

# What is a Design Pattern

Coding for the web kind of sucks due to repetitive tasks. It also sucks if you are working on a team where everyone has their coding style. Suppose a bug is introduced that comes from someone else then have fun looking through all their code. Setting standards for approaching a problem would be the best way to fix this problem. This is where design patterns step in to solve this problem. Design patterns are templates/standards to follow that have been tested and proved to accomplish the task that was given.

A good way to demonstrate design patterns is to think about it like a template. When people draw faces they usually start with drawing an oval and finding the center of the face. From there they add eyes around the middle part, create eyebrows around the eyes, draw a mouth lower on the face in the center, erase the center lines you created, and continue from there. This is a good example of a design pattern that artist use to create faces in their artwork. In the example, a methodology was developed that has been a proven way to draw faces.

## Software Examples

A good example of this would be libraries that have been developed to build websites like Laravel, Django, meteor, NextJS, etc. Almost all libraries have a design pattern you have to follow to use their toolset. The reasons why they have these design patterns can vary from speed to readability. Meteor follows along the lines of using the same design pattern React has which is functional. Each view is its component and you can define a component by creating a function and rendering the view by using a return statement on the function. Then to add to that meteor structures its directories having a page directory, server directories, and more. This kind of gives a structure on what kind of files are going to be stored in each area, making it simpler to figure out what going on, and where it is happening. These design patterns then make it super easy to debug problems even if you have multiple people working on a project.

If we were to go beyond just website development though we can see design patterns in other things we code as well. The best way to illustrate this is by looking at object-oriented programming, If we were to create a shape class we can set base values that all shapes have like a name, dimensions, and so on. Other objects then can inherit from shape and these objects also have to follow the standards that shape has. This makes it predictable on functions that all shapes should have as well.

# Personal Projects I Have Used Design Patterns

In our final project alone for ICS 314 just by using React, Bootstrap, ESLint, and Meteor, we were introduced to many design patterns that were used to make the code more readable, easier to diagnose problems, and easier to navigate. Though these libraries made us use their design patterns does not mean that we can not add our own to this. A good example of this is when you create a component in React you are creating a standard way to display a part of your site. These components can take in parameters that force you to use certain types of values. With this, you are creating a design pattern that future people can use on their sites as well. Which is something we also did on our own site. While I may not have been a fan of some the design patterns of these other libraries they proveded a good structure in developing a website with many people

Another use of design patterns I implemented has to be when I was created a website for my job. Laravel is a php library that is used to create websites, and one of the things it does is use APIs. The issue is when your API behaves very differently depending on the permissions a user has the file can get very confusing. This is why I created my own design pattern in Laravel to use a directory type of routing like they have in NextJS. This allowed me to break up the file so its more readable, and it allowed me to make a standard for other people if they want to create an API in the future as well.

# Final Remarks

I feel like if you develop any time of software you will eventually create a design pattern. You could use other frameworks libraries, but in doing so you will most likely be using their design pattern. Since design patterns are just a templated methodology that was created to solve a problem you will see a lot of design patterns in any thing you do for programming. If you where to just look at networking alone their are a bunch of design patterns of how data is sent from one device to another.