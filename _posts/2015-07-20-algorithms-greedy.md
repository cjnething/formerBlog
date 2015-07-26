---
layout: post
title: "Algorithms: Greedy Algorithm"
date: 2015-07-20
---

As I wrote in my "Toy Problem Tools" post, I love algorithms. The best part about doing algorithms is being forced to look at a problem in more than one way in order to reach the most efficient solution. One such approach is using a "greedy algorithm," and it is extremely useful in solving problems in Project Euler and the like.

# What are Greedy Algorithms?
Greedy algorithms are algorithms in which you make the best choice available at each new value in the data set, so that by the last step (the last value in the array, for example) you have the best choice for the entire data set.

This will probably make more sense with some examples.

## Making Change
Let's say that you want to pay for a $56 sale with the least amount of bills possible. How would you approach this problem? Assuming that we are using American dollars, the bills less than $56 are: $1, $5, $10, $20, and $50. Using a greedy algorithm means that we would start with making the best choice possible at each step.

Steps:
1. At the first step, we have paid $0 and we have $56 left to pay. We want to use the fewest number of bills possible, so the best choice at this stage is to pay the most amount of money with a single bill. The highest bill under $56 is $50, so we will pay a $50 bill.


This was just an introduction to using greedy algorithms, and hopefully it was useful to you. If you have any questions, or if you have any tips for me, please leave a comment or send me an email at cjnething@gmail.com!