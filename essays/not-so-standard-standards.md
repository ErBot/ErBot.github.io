---
layout: essay
type: essay
title: Not So Standard Standards
# All dates must be YYYY-MM-DD format!
date: 2019-09-25
labels:
  - Software Engineering
  - Learning
---

I’ve noticed ESLint with IntelliJ minimizes the lines of code I’ve had to write. Getting the code to meet the green checkmark requirements initially seems like it would be a pain, however, IntelliJ gives the option to automatically make changes. The prompt comes up, you click on the option that fits what you’re trying to accomplish, and it all gets fixed automatically. These prompts for automatic fixes stretch beyond simple formatting corrections. IntelliJ will prompt to run “npm install” or install local copies of libraries if it detects new files or scripts. IntelliJ also provides a seamless transition between writing code and uploading it to GitHub. 

ESLint not only helps with readability and functionality, but it also can help learn a coding language. For example, I was doing an exercise to fix bad code using ESLint, and in doing so I learned a new way to write function parameters. The function I was fixing had a variable in the parameter and then declared it again with a default value. The second instance of that variable was marked as redundant and I learned that Javascript had a way to set default values for parameters. By assigning a value to the variable within the parameter parenthesis, the variable would take that default value if either a “null” value or no value is passed. 

Going beyond the formatting standards of ESLint, there should be stringent standards on commenting on blocks of code. When I learned Java, our instructor made it a requirement to create a comment box above each function, detailing its purpose, parameters, and output. Not only did this break up the blocks of code into easily identifiable sections, but it helped me reuse my old code months later. I was able to import old code into new programs without having to manually go through and figure out all the parameters of the functions I wanted to use. 

The only thing harder to use than your old (uncommented) code is someone else’s uncommented code. There have been many instances where I’ve had to either fix or reference someone else’s uncommented code and it was a very unpleasant experience. What should have taken a few minutes ended up taking hours. Instead of having clear direction, I had to manually decode the person’s algorithms and figure out how to adjust accordingly. Comments seem to be severely underrated, and I for one, am not opposed to adding those requirements to ESLint. 
