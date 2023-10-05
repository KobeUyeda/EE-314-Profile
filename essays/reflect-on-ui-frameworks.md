---
layout: essay
type: essay
title: "Reflecting on UI Frameworks"
# All dates must be YYYY-MM-DD format!
date: 2023-10-04
published: true
labels:
  - Web Dev
  - Bootstrap
  - UI Frameworks
---



<img width="100%" class="rounded float-start pe-4" src="https://cdn.hackr.io/uploads/posts/attachments/1679326591WjFOoim2eQ.png">

## UI Frameworks are cool
There are many benefits of having a a UI framework like Bootstrap. One of the main benefits that any UI framework has is the fact that you don’t have to think to much on the design of the website. The UI framework has done all the heavy lifting so you don’t have to think much about it. One of the other benefits that UI frameworks offer is that most of the time it simplifies the packets being sent to the end user. With CSS you will create classes for certain parts of your application, but what happens when an update has to occur for the look of the site. Well in that case many would delete the classes and ids they defined in the CSS, but that is not always the case. Many times people will just create a new class, and in doing so keep the old class defined in the CSS. Now the issue lies when you are shipping all this to the client. As your CSS file continues to grow so does the complexity and size of the file, increase wait times. Due to this UI frameworks offer a fresh breath of air only shipping the classes that you used in your site.

Now that does not mean UI frameworks are all the same or that they all follow these rules. For example in Bootstrap many things are predefined their is not much customization that exists. That is unless you want to also implement a CSS file. While other UI framework such as Tailwind takes a completely different route than Bootstrap, where Bootstrap everything is kind of predefined already, Tailwind has way more customizability. The best way to describe how Tailwind feels is like you are using inline styles. There are even UI frameworks that build off of other UI frameworks such as DaisyUI which builds off of tailwind and creating classes like button which will implement all the Tailwind classes that will make it look like a button.

## My Favorite UI Framework
I have played around with my fair share of UI frameworks. I have used React based UI frameworks and regular UI frameworks, and I have to say so far my favorite has to be Tailwind. I love how intuitive the class naming is, and how I get all the benefits of of a UI framework while also still having control of the customizability of certain components. If I want classes similar to Bootstraps btn class I can pick on a wide range of other frameworks that build off of tailwind.

## My Issues with bootstrap
I have noticed while using Bootstrap that their are classes like nav or container, which adds an abstraction to the CSS. Their are many CSS lines that exists for these classes, making them less intuitive. For example I use a container class sometimes, and then for some reason my padding is no longer working. I then have to click on inspect or look at Bootstraps documentation to see what is being abstracted and to figure out why it didn’t work.

Which brings up a whole new issue I have with the container class. Why does the container class exist. You may say well dont you want to implement a grid system in certain cases, and the answer is yes. In some cases I want to have a grid system, but why do we need a container class, row class, and a col class. In CSS they have a display property called grid which does all this for us. Why not just implement that system instead. While Bootstraps grid feature does offer one new benefit of having a responsive grids, it is very restrictive. With Bootstraps grid system you only have 12 cols. With CSS grids I can have any amount of cols I want, and I can just use CSS responsive system to readjust it accordingly to the page size.

That is not my only issue with Bootstap though, to add on to it I don’t like how they have classes such as w-100, p-4, etc. Now you may be saying what is the issue with these classes well my main issue with them is lets say I want a width that is not 100%, but 90%. In theory if I was to follow with the same logic I could just do w-90, or something along those lines. You would be wrong in assuming this though. I have a select amount of options that I can pick from, and if I want a certain width then I have to go back into the CSS. The fact that I have to involve CSS and Bootstrap to get my desired effect, what is the point of Bootstrap in this case. I am in the end adding complexity to the code, and I am still having to think on how I can transform their default button into the desired button look. Why not at that point just code all of it in CSS since I have the same complexity amount I would have had either way, but at least I wont constantly be trying to figure out if the styling issue lies with my CSS or Bootstrap.

