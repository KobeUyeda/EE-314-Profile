---
layout: essay
type: essay
title: "Smart Questions or Not Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: true
labels:
  - Engineering
  - Forums
  - Stack Overflow
---

<h1>What is a Bad Question</h1>
<img width="100%" src="https://i.stack.imgur.com/IxkIq.jpg"/>
When you ask a question on the internet how do you write out your question? Does it go along the lines of, “I don’t know what is wrong my computer just stopped working” or something along the lines of “My code just does not work.” In both cases were you praised for asking this question or were you downvoted into oblivion?

I would expect in both cases you were downvoted, and if you were using Stack Overflow you may have been banned from asking any more questions for a while. When asking questions on a forum it is imperative the question you ask is smart.

Now what is a smart question, you may ask? Is it a question that only very smart people can answer, or is it a question that is very technical and that only people in a community can answer? The answer is no, smart questions are just questions that are formatted in a way that best explains the problem so that whoever may be helping you diagnose the issue can figure out what is going on.

A good example of a smart question would be this stack overflow forum question labeled <a href="https://stackoverflow.com/questions/27928372/react-router-urls-dont-work-when-refreshing-or-writing-manually">React-router URLs don't work when refreshing or writing manually</a>. In this forum, we can see that the title tells us what the problem is they are having. We know that this forum is going to talk about the user's issues with React-router URLs library when they manually refresh the page. This allows us to narrow down what library he may be having issues with, and the issue he is having with the library.

In the forum, he then iterates what the goal is of the code. He is trying to route users to the correct page depending on the URL for a single-page website. He then continues explaining the error he is receiving and the steps to reproduce this. He tells us when he does a hard refresh of the web page he gets an error of “Cannot GET /joblist”. Finally, at the end of the forum, he tops it off by giving us a code snippet of the section he is experiencing issues with.

This is considered a good question for many reasons. First off he didn’t just say there is a bug in the code. He explained the issue he was having, what library he was having the issue with, and how to produce this issue, and gave us a code snippet to show us what it looked like. Now if I were to try to diagnose the issue I would probably be able to explain in good detail what is going on and why he may be receiving this issue if I knew the library he was using.

This is why once you scroll down another person doesn’t have to keep asking questions about the issue he was experiencing. The person helping this person was able to give a really good detailed response to what was going on. They were able to explain what the difference is between client-side routing and server-side routing. From there they were able to explain what the library did (React-router is a client-side routing library), and why when he tried doing a hard refresh it didn’t work (This would lead to server-side routing which his code didn’t do). He then explained how if he wanted to solve this he would have to integrate a server-side routing system in tandem with React-router.

Now you may be saying what is a bad example of asking questions then? Well here is another forum post that I would say is a bad example <a href="https://stackoverflow.com/questions/77048427/developing-a-large-multi-course-website-with-react-js">Developing a large multi course website with React.js [closed]</a>. Now you may be saying what is bad about this question. Well, to start off the title does not help us figure out what we may be expecting when we are trying to solve this problem. While this does explain what he is trying to do and what library he may be using, it does not explain what issues he may be having.

Now if you then were to continue to read this forum he does not explain what the issue is, and we have no context of what he is explaining. He just states that he is trying to develop a lessons website with React, and he thinks he is structuring the project wrong, but does not tell us what the structure of the site even looks like. He just says he wants the site to host thousands of lessons but does not want a bunch of JavaScript files.

Now if I were to try to answer this problem, I don’t even know where to start. I know he is using React, but have no context of how the project is structured, what the page should look like, what backed library he may be using for this React web page, or even what he is expecting this project's code structure to look like.

The responses to these questions very well illustrate how bad of a question this is. We have only one response, which is pretty helpful, but does not answer the question since it has been downvoted and has not been marked as helpful. We can see not many people in the community liked the question since it has also been downvoted, and someone who is ranked pretty high marked this question as closed.

From there you may be saying then how could we have better asked the question in this case? Well to start a better title for this forum could have been “How to Structure a Large Multi-Course Web Page using React (react-back end).” Within the brackets, you can list the React back-end framework they may be using. To continue from there I would outline what this website looked like. Give us a picture of what you have so far and a picture that illustrates the problem. You can then continue from there by annotating the picture to illustrate what is a component of this project.

He then could have outlined the file directory and explained what each file was in charge of, for this web page. Then he could add some more detail saying what this project stack could be. Is he using Next.JS, Meteor, or Create-React-App? Does he have a database, and if so what kind of database, and what is the structure of the tables? This would better help the user who is trying to diagnose the issue the user is having building this website. Currently, we know nothing of what this project looks like, or what he wants. This would lead to follow-up questions, and a lot of time investment delaying a good answer or just making it troublesome for anyone who wants to help in their free time.

In the end, most people who are answering these questions are doing it in their free time. When you don’t ask smart questions it can lead to bad responses, and waste a bunch of time for both parties. Be considerate to people who are taking time out of their day to help you with your project. You want to ask a question that is easy for them to understand your problem so they can answer your question as fast and timely as possible. This also does not help anyone who may have a similar problem to you. If you structure a question badly people may not understand they have a similar question, which leads to the same question being asked over and over again wasting more time. So just ask smart questions so we all can save time in the end (after all, coding projects are supposed to save you time).
