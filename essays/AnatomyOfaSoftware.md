---
layout: essay
type: essay
title: "Anatomy of a Software"
# All dates must be YYYY-MM-DD format!
date: 2024-05-09
published: true
labels:
  - Software Engineering  
  - Configuration Management
  - Functional Programming 
    
---
<img width="700px" height ="400px" class="rounded float-start pe-4" src="./mywebsite.jpg">





## What I had Imagined 

This webpage "Shops Near Campus" looks simple enough. It resembles a Post-it notes stuck on a board. Prior to learning Software engineering, I would have imagined a single page of codes behind this page. 


<img width="700px" height ="400px" class="rounded float-start pe-4" src="./ListShops.jpg">


## So Many Directories and Subdirectories 

My assumption was correct to an extent- ListShops.jsx, shown just below the webpage does code for the page. However this file alone is not enough. To the left, we see a list of directories, subdirectories and files. This looked nothing but overwhelming for most of my semester. After 10 weeks of staring at them, I've started to appreciate them. The organization started to make sense. If you are intimidated by coding, this is an example that you should code anyway. 

## Translating Real world into Code 

In the real world, replicating "Shops Near Campus" is much easier. I would find a large board.  We would write and draw the information of the stores on post-its. However,there is a significant feature the code version affords; when any user adds a shop, this change is reflected to all users viewing this page. 
  ```
  const subscription = Meteor.subscribe(Shops.userPublications);
  ```
Like a 
## AI Use In this Essay

ChatGPT was only used to check spelling and grammar. 
