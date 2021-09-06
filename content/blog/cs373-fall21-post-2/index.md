---
title: 'CS373 Fall 2021 Post 2'
date: "2021-09-05"
description: "Post #2 for CS375 Software Enginering (Makefiles)"
---
![profile-photo](./potrait.jpg)

### What did you do this past week?
This past week, I managed to cook all the new recipes I learnt from my mother. Most of those are curries and frys like
tomato curry, potato curry, chicken curry, potato fry, egg fry, etc. I hope that once I get comfortable with 
making these I do not have to stress about food for the rest of the semester, although they do take a bit of time to 
make.

Other things I have been working on is practicing some coding problems with my friends and I finished
HackerRank for project Collatz!

### What's in your way?
The stress of applying for internships is definetly taking its toll on me. I sit down to start working only to get hit
by the realization that I also have to apply to companies. It is hard to get anything done with that cloud hanging 
over my head.

### What will you do next week?
Start going to some org meetings that I think are cool, cook more instead of eating out, and finish all my class work.

### If you read it, what did you think of the Paper #2: Makefile?
The makefile looked pretty standard compared to makefiles from other projects, but having aliases for batch git
commands seems unecessary.

I think Makefiles are in general pretty neat tools that allow you to write pipelines for compiling or testing code.
However, they do look pretty complicated to work with and require much more work to learn how to setup besides just
annotating an existing makefile. I hope we go over how a makefile works in lecture sometime. 

### What was your experience of assertions, unit tests, and coverage? (this question will vary, week to week)
*Assertions* are statements in your code that check if a boolean expression is true or not and fail immediately if false. 
They make testing invariants in your algorithm easy and I use them in every project I work on. I cannot quantify how
many bugs I caught early on due to assertions.

I have used *Unit Testing* before and I think it works very well for this project. The input and output are
well-defined and creating more tests is very simple. However, it does require you to know the solution ahead of time
though.

I have never used Coverage before and am not sure it is needed for this project. I believe it is only useful in checking
if your tests are reaching every part of your codebase. I think it is only useful for very large projects that many have
dead code that does not need to be maintained. All in all, I think this is the least useful tool of the three.

### What made you happy this week?
I have been going to the gym with my roomates and I noticed some changes! I think my hard work is starting to pay off
now that I feel my posture and strength has improved. Here is to maintiaing my routine into the semester!

### What's your pick-of-the-week or tip-of-the-week?
Remember taking Operating Systems (CS439)? Remember how hard it was to fix race conditions, memory leaks, and null 
pointers? Well, it could have been all avoided if you used a new programming paradigm. Introducing 
[Rust](https://www.rust-lang.org/), a programming language that does not allow code that leads to race conditions or 
dangling pointers. It separates references into mutable and immutable references so that you can only have one mutable 
reference of an object at a time. This already avoids problems with multiple threads writing to a single memory.