---
layout: essay
type: essay
title: "Reflecting on Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2023-09-20
published: true
labels:
  - IntelliJ
  - ESLint
  - Coding Standards
  - JavaScript
---
<img width="100%" src = "https://yt3.googleusercontent.com/ytc/AOPolaQM_Ngb9zGFPhZQaYiwObi0RSD8A-9uhnNsvw74hA=s900-c-k-c0x00ffffff-no-rj"/>
<h1>Coding Standards are Needed</h1>
Creating a coding standard can be hard some say. How much spaces should my indent by? Some people only use one space, others use more. What should be my format when creating a variable? Some say you should use camel case while other rather use use an underscore for any spaces. The truth is that this should not matter as long as you stick with a standard that you pick.

Coding standards are just a way for people to format code that makes reading it easy, and makes it easy to expand upon the code if need be. If I didn’t create a standard of function names, it becomes a lot harder for any one who tries to use any of the function in the future. Even if someone understands a language very well if the coding standard is all over the place, even they will struggle using what you have written. The best coding standards are ones where even if you are new to the language you can easily tell what should be happening.

The goal of any coding standard is that once someone is able to sees your format it shouldn’t change at all. If it does this is what could lead to confusion. Now as I said as long as you stick with a standard this usually does not matter, but what if you are working with a group of people? This is when issues can arise if you don’t all adhere to the same standard as each other. What if some people in your group use a different variable format, or if they have a different indent system? Well in the best case scenario your code just becomes harder to code in, and in the worst case scenario the code does not work at all.

Example (bad coding standard):

```js
function notCorrectCode (value) {
	if (value === ‘1111’) {
	return false;
	}
return true;
}
```

Example (good coding standard):

```js
function CorrectCode (value) {
	const Code = ‘1111’
	if (value === Code) {
		return true;
	}
	return false;
}
```

As you can see from the examples the second example becomes a lot easier to read. If I was to give you the second function vs the first function you can tell what its doing just by the name of the function. Then I basically label any constant values with a variable so people can have an understanding of what the value is. From their the indents are the same through out the functions making it easy to see what should happen in this function. Now the first one does something very similar to what the second function did, but it does the opposite only returning true if the value entered is not the code. Now while these functions basically does the exact same thing, it takes a little bit more time to understand what this function may be doing. To make it worse, in the function I just put an if statement that compares the value to a constant value. If someone was to look at that they may be confused why we are comparing the value to a string of 1s. Basically a good coding standard can have a major effect to how people will read your code.

Now IntelliJ helps us out with making good coding standards by verifying we are adhering to the coding standards that are set. To do this we utilize ESLint to state our coding standards, and then if we don’t follow those coding standards then IntelliJ will highlight and warn us about breaking coding standards. Very similar to how Word, or Google docs highlights any misspellings or grammar issues in an essay.

While using ESLint in assignments and WODs I started to find out that while ESLint does help make sure we follow a standard. The issue comes when it can’t detect the libraries that you have imported from another file. In many assignments I keep getting errors that it has not clue what the underscore library comes from. This makes sense since this library is only ever imported on the HTML which does not run until we open it in a browser. So while I have not received any errors from coding standards I have received many warnings that I have not defined what the underscore library was, but when I run HTML I don’t have any issues. ESLint is very helpful and useful making sure we stick to a standard, but until we start importing the underscore library through node package manager (NPM) this error will persist which is one downside considering all the other benefits that comes with ESLint.
