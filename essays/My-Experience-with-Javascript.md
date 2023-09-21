---
layout: essay
type: essay
title: "My Experience with JavaScript"
# All dates must be YYYY-MM-DD format!
date: 2023-08-29
published: true
labels:
  - Engineering
  - JavaScript
---
<h1>My Experience with JavaScript off to a Rocky Start</h1>
<div style="background-color:#0A0A22; overflow: hidden">
<img width="50%" style="float: left;" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"/>
<img width="50%" src="https://design-style-guide.freecodecamp.org/downloads/fcc_primary_small.jpg"/>
</div>

<p> JavaScript some people hate it and some people love it. I personally am not a huge fan of plain JavaScript. When first using JavaScript back in high school I did not like the feeling of the language. That may seem very vague, but considering I had no way to express the issues I was experiencing with JavaScript that was the best way I could put it at the time. Nowadays I can express a lot of what I hate about JavaScript. I find it weird in JavaScript that the basic equal operator <code>==</code> does not really do its job. For example:</p>

<code>1 == '1'</code> vs <code>1 == 1 </code>

<p> Between the two code snippets which one should return true? Left or Right? If you were to say right is true and left should return false, you would be correct for any other language, but not JavaScript. Then you may be wondering, well how do you make sure the left option returns false for certain occasions? Well in that case you use strict equal operators which looks like this <code>===</code>. You see there are many inconsistencies that the base JavaScript has that I personally am not a fan of. To continue off of that route one huge issue that I have with JavaScript is the type safety, or the lack thereof. Almost every language has some form of a type check safety to protect coders from feeding weird types of data. A feature that makes development easier does not exist in JavaScript. Now I know there are alternatives to these problems such as typescript, but the fact that this is not just baked in, and it's not even true type safety is what makes me feel like JavaScript is a worse programming language than others out there.</p>

<p> As I re-explored JavaScript through the Free Code Camps curriculum I did not have much fun doing much of the problems. Mainly due to the fact that I have gotten used to using typescript over plain JavaScript. Much of the content that exists in this guide wasn't entirely new to me so this was really just an overview of many things that I have learned from previously working on personal projects. ES6 in my eyes makes plain JavaScript bearable, but that still does not take away from the many issues that exist throughout the language.</p>

<p>The issue is also that for us to use ES6 you have to use the babel library to compile it down to plain js which kind of sucks, because now when doing stuff like practice WODs we have to use plain JS since that is what the browser supports. While these exercises were a great refresher to JS I don't think I will ever fully love all the quirks of JavaScript.</p>
