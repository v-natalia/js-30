---
layout: post
title:  "Lessons learnt when transition from Ruby to Python"
date:   2019-05-20 09:22:08 +0200
moment: 20th May
categories: programming
permalink: /posts/lessons-Py
bg: you got.jpg
---


Python.
Yes, now I'm learning Python, because I want to improve my atractiveness as a potential employee, and Python is sexy and everybody knows that.
Even if many people says that the transition from my former language (Ruby) to Python it's smooth I've found some pitfalls that I will keep updating here as I found them:

#1 Indentation is key.
While in Ruby an indentation issue is just mess and could make you lose your time looking for the "end" that you forgot to write, in Python a mistake in the indentation is an error and your program will not run. So, indent or die.

#2 You are not allowed to interpolate strings and assign them to a variable.
In Ruby you could write:
`variable = "Hello" + " " + "world"`
But in Python, you will get a *funny* Error: 'str' object does not support item assignment.
What does that mean ? Strings are inmutable on Python so to do the same as you did in Ruby, you should write 5 lines of code to append every string to a List ( or array in Ruby `[]`) and then join the whole thing and put it in the variable you wanted. (That's one way of solution)
