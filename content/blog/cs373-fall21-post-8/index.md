---
title: "Software Engineering: Post 8"
date: "2021-10-17"
description: "Post #8 for CS375 Software Engineering (Liskov Substitution Principle)"
---
![profile-photo](./potrait.jpg)

### What did you do this past week?
This past week, I avoided the rain, enjoyed the sun and welcomed the beginning of Fall! I also went to Garba 
this past Friday, which is a cultural celebration at the end of Navaratri that I have been looking forward to
for quite a while. All-round lots of excitement 😁.

### What's in your way? 
The fear of deathly cold weather and the onslaught of rain at 11:00 pm terrifies me. 
I was programming in my room Wednesday night and nearly jumped out of my seat when I heard thunder. 
From now on, I will walk with worry during gloomy days where clouds gather for a thunderous discharge in the form 
of rain.

### What will you do next week?
Avoid going out during rainy days and spend all day out during sunny days.

### If you read it, what did you think of the Paper #8: Liskov Substitution Principle?
LSP is an extension of the Open-Closed principle we read last week. I think LSP is more important than Open-Closed 
because it clearly defines how preconditions and postconditions should be formulated in an inheritance 
hierarchy. Good use of LSP is essential for writing APIs.

### What was your experience of comprehensions, generators, and yield?
The yield function was interesting and I would like to find creative ways to use it other than for loops or list
comprehension. 

### What made you happy this week?
Garba, sunny weather, and being able to workout all helped me stay in high spirits this week. I am thankful for 
being able to work with my friends on projects and have fun!

### What's your pick-of-the-week or tip-of-the-week?
The [Union Find algorithm](https://en.wikipedia.org/wiki/Disjoint-set_data_structure) is my new favorite algorithm and 
is a very easy way to find connected components, cycles, and minimum spanning trees of a graph. Here is how it works:

Maintain an array $p$ where $p_i$ is the set that node $i$ belongs to. $p_i=i$ in the beginning. For every edge 
$(i, j)$, we perform a *union* operation that merges the sets that $i$ and $j$ belong to. By the end, every node $i$
with the same $p_i$ value is in the same set. Easy, right!

You can find visualization and implementation of the algorithm on [HackerEarth](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/), and practice problems on [LeetCode](https://leetcode.com/tag/union-find/).

Until next week!