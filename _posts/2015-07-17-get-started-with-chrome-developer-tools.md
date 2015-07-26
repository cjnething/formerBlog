---
layout: post
title: "Getting Started with Chrome Developer Tools"
date: 2015-07-17
---

When I was first getting started with JavaScript, I knew absolutely nothing about Chrome developer tools.
A lot of users on Stackoverflow give answers like "just check it in the console," and I had no idea what that meant.

Now that I use Chrome developer tools on a regular basis, I hope to pass on the information that I wish I knew
when I first got started. For many people this is considered very "beginner," but everyone has to start somewhere.
Hope this helps!

# Accessing Chrome Developer Tools
- Open any webpage in Chrome (i.e. google.com)
- Right-click on the page and choose "Inspect Element"
- On the bottom of the page, there are 8 options (we will look at Elements and Console in this post)

## Console
1. Click on the "Console" tab
2. Write or paste code into the console and test. For example, if you wanted to check if your Perimeter function was working, you could paste in this code:
function perimeter(height, length) {
  return (2 * height) + (2 * length);
}
3. After you hit "enter", the console has access to your function.
4. Now, you can test your function! In this case, you can write in the console: 
   perimeter(5, 10) 
   and the console will return 30. This helps you test to make sure that your functions are working the way you think they will.

### Why use the console?
There are other ways to test code other than the console. For example, you could use the website repl.it or you could build a console in Sublime with Node.js. However, your console is great for short, on-the-fly code or code interacting with the website. For example, if you wanted to use Underscore.js, you could open your console on the Underscore.js website and then you will have access to all of the Underscore functions in your console.

## Elements
The "Elements" tab allows you to view everything in the DOM tree in that website. It also allows you to temporarily diable CSS on-the-fly to see how different CSS affects the website and see the changes. This is very useful for learning from other developers!

For example, try opening up the website oldnavy.gap.com.
Next, right-click on the "Shop by Department" option on the top-left page, and click on "Inspect Element."
Check out the "Elements" tab, and then look at the "Styles" tab on the right-hand side. 
Next to the red-letter CSS options are boxes that are checked. Un-check some of those boxes, such as 'font-size', and see how that affects the page.


This was just an introduction to Chrome Developer Tools, and hopefully it was useful to you. If you have any questions, or if you have any tips for me, please leave a comment or send me an email at cjnething@gmail.com!