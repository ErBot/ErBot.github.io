---
layout: essay
type: essay
title: Newb vs WebDev Round 1
# All dates must be YYYY-MM-DD format!
date: 2019-10-10
labels:
  - Software Engineering
  - Semantic UI
---

  From an engineering perspective, Semantic UI gives us decent toolset for solving problems. We can use preset data structures such as menus or containers to quickly nest objects and engineer solutions. For example, I was able to recreate the top menu to the Tatami website by nesting a list inside a two-column grid container. Being able to quickly reference these data structures using plain English, not only does wonders for readability, but it also allows me to use data structures without having to deal with all the associated code. To be honest, if I had to figure out how to manually code a two-column grid and then put a list inside of it, I probably wouldn’t use it. I would most likely end up creating the list object and then using CSS to reposition it. By using Semeantic UI, I was able to accomplish this in only 4 lines of code, including alignment and padding. 

  Grouping using Semantic UI was as easy as typing out a <div> inside of another <div>. By placing  Semantic UI’s “item” classes inside containers or lists, formatting and alignment was automatically inherited. This helped avoid having to manually create CSS styles for each group item. Additionally, I was able to avoid using CSS by adding modifiers to the UI class field. This was huge for me because I’ve never really used CSS and I would have to spend a lot of time going through documentation for proper syntax. One problem I encountered when using modifiers was that I would sometimes use modifiers in places they weren’t supposed to go. This would break my code and it was very time consuming to debug because the code would still run with no errors. To be most efficient with modifiers, I would have to take the time to learn their proper usage. However, for our purposes, memorizing proper modifier usage would not have been worth the time. The second problem with the modifiers was that I had trouble figuring out how to reference a <div> in CSS when the <div> had had several words in the class field. After many failed attempts, I had to either reduce the number of modifiers in the class field to create an easily referenced identifier, or I would resort to using the “style” field within a <div>.

  Additional benefits of using Semantic UI include quick access to commonly used logos, such as Facebook and Twitter. While Semantic UI provided some tools to meet the standards for a modern website, it was lacking in other areas. For example, I was unable to create an image carousel, even with help from the brilliant minds of the internet. I was able to create a field to display 5-Star ratings, but I was unable to modify the shape and color of the stars. Additionally, the documentation shows that you can set the default and maximum amount of stars, but it doesn’t tell you that if you don’t set both your stars will disappear. I defaulted the ratings to 5 stars but I didn’t know that the maximum is initially 4 stars. After about 20 minutes of yelling “Why?!?!?” I was able to piece together a few examples and get it to work. 

  For a newb’s first attempt at a modern website, Semantic UI was a valuable tool. I was able to clone a website with little effort, and even improved on mistakes found in the website I was cloning. Although Semantic UI made my transition into HTML and CSS easier, it’s not enough to make want to get into web development. 
		