---
layout: post
title: "Tools for Algorithms and Toy Problems"
date: 2015-06-12
---

I love algorithms.

Every morning at Hack Reactor, we complete a toy problem, which is essentially an algorithmic problem along the lines of Coderbyte, Project Euler, etc. These problems are fantastic because there are usually two ways to complete them: a brute-force method, and a clever method. The brute-force method usually will work for small/simple examples, but when you try to extend your algorithm to work for more complex examples, the method either doesn't account for edge cases, takes too much time, or is inefficient in some other way. That forces you to think of the problem at an even deeper level and keep optimizing your solution.

Project Euler is my favorite collection of algorithms, and by working through those problems, I've learned about some tools that help me use JavaScript and test better. Much thanks to David Ernst (www.dsernst.com), Wikihow, and Big.js for these tools and tips!

Also, if you want to befriend me on Project Euler, here's my friend key: **655618_43bdc123ce2e987a8e30aaf7396ef69a**.

## Building a Console in Sublime
This one is pretty easy to complete, and the results are fantastic.  

-The instructions I used are on Wikihow (http://www.wikihow.com/Create-a-Javascript-Console-in-Sublime-Text). Use Method 2 of 2 (Using Node.js), because that will allow you to run console.log() instead of debug() when you want to see your results, which is more intuitive in my opinion.

-Once you have completed those instructions, open the file in Sublime of the problem you're working on.

-Make sure you are in the correct build system (make sure that Tools -> Build System -> Node is checked off).

-At the end of your file, type in console.log(function). So, for example, if I wanted to find the fibonacci numbers for index 12 and my function is called fibonacci, I would type console.log(fibonacci(12)) on the last line of my file.

-Hit "command" + "B" keys (B is for Build). This will show your console at the bottom of your Sublime file, and the result will appear in the console.

-Every time you want to change your file, make sure to hit command + B again to save and refresh the console.

-Enjoy!

Before using this method, I would either open up a console in my browser or use repl.it to check my work. This method is much more efficient because all of my code is in the same place and I don't have to keep copying in my new functions into my console/repl.it. If you have that same problem, I highly recommend building a console in Sublime!


## Solving Problems with Large Integers
A huge problem that I had with a lot of Project Euler problems is that my algorithm would work but my intermediate or final result would be too large for JavaScript. For example, if you are trying to find 2^1000, that number is so large that JavaScript will no longer show all the digits. Thankfully, there is an npm module that solves this problem. If you use Big.js (https://www.npmjs.com/package/big.js), that will allow you to keep even your largest numbers in their expanded form where you can see all digits and perform mathematical operations on them without rounding issues. There were several Project Euler problems that I could not solve before using this module!


These were just a couple of tools/tips that have helped my algorithm workflow. If you have any questions, or if you have any tools/tips for me, please leave a comment or send me an email (cjnething@gmail.com)!


