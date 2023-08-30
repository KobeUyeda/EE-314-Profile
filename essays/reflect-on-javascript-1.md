---
layout: essay
type: essay
title: "Reflecting on Javascript 1"
# All dates must be YYYY-MM-DD format!
date: 2023-08-29
published: true
labels:
  - Engineering
  - Javascript
---
<h1>Reflecting on Javascript 1</h1>
<div style="background-color:#0A0A22; overflow: hidden">
<img width="50%" style="float: left;" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"/>
<img width="50%" src="https://design-style-guide.freecodecamp.org/downloads/fcc_primary_small.jpg"/>
</div>

<p>Javascript some people hate it and some people love it. I personally am not a huge fan of plane javascript. When first using javascript back in high school I did not like the feeling of the language. That may seem very vague, but considering I had no way to express the issues I was experiencing with javascript that was the best way I could put it at the time. Now a days I can express I lot of what I hate about javascript. I find it weird in javascript that the basic equal operator <code>==</code> does not really do its job. For example:</p>

<code>1 == '1'</code> vs <code>1 == 1 </code>

<p> Between the two code snippets which one should return true? Left or Right? If you were to say right is true and left should return false, you would be correct for any other language, but not Javascript. Then you may be wondering well how do you make sure othe left option returns false for certain occasions. Well in that case you use a strict equal operators which looks like this <code>===</code>. You see there are many inconsistancies that the base javascript has that I personally am not a fan of. To continue off of that route one huge issue that I have with javascript is the type safty, or the lack their of. Almost every language has some form of a type check safty to protect coders from feeding wierd types of data. A feature that makes development more easier does not exist in javascript. Now I know their are alternatives to these problem such as typescript, but the fact that this is not just baked in, and its not even true type safty is what makes me feel like javascript is a worse programming language than others out their.</p>

<p> As I re-explored javascript through Free Code Camps curriculum I did not have much fun doing much of the problems. Mainly due to the fact that I have gotten use to using typescript over plain javascript. Much of the content that exist in this guide wasn't entirely new to me so this was really just a overview of many things that I have learned from previously working on personal projects. ES6 in my eyes makes plain javascript bearable, but that still does not take away from the many issues that exists through out the language.</p>

<p>The issue is also that for us to use ES6 you have to use the babel library to compile it down to plain js which kind of sucks, because now when doing stuff like practice WODs we have to use plain JS since that is what the browser supports. While these excersizes was a great refresher to JS I don't think I will ever fully love all the kwirks of Javascript.</p>
