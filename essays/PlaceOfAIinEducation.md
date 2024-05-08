---
layout: essay
type: essay
title: "A Place of AI in Education"
# All dates must be YYYY-MM-DD format!
date: 2024-05-078
published: true
labels:
  - Software Development
  - Artificial Intelligence
  - ChatGPT
  - Pedagogy
---
<img width="700px" height ="300px" class="rounded float-start pe-4" src="AITeacher.jpeg">





## I. Introduction 
 
My intial exposure to AI took place last year, when I consulted chatGPT for my Physics homeowork problems. I was intially impressed as chatGPT explained step by step on how it calculated the magnetic filed change of a rotating motor. However, I was quickly dismayed when I realized all of its answers were incorrect. Furthermore, when I asked the questions again, it gave different answers. I was unimpressed, but fascinated on how it came to its wrong answers. 

This spring I took a course called Information and Computer Sciences 314: Software Engineering, at the University of Hawaii at Manoa. This course emphasizes hands on coding experience, culminating in a group project to develop a web application. ChatGPT has played a major role for me in this course, proving to be a reliable source of help. 


## What is a Problem?

All problems are not necessarily interesting. For example, I am currently writing a app that shows the price of an food ingredient in the local area. I want all users to be able to update the prices they see in any given store. The challenge and art of programming is how to translate what I would tell a human intern "I want you to take  all information about prices of a tomato, and the store it was foound. Show this list of everytime when someone asks about tomatoes. Now do the same for all ingredients please." 


## I have no clue...would design patterns give me any?

Without design patterns, my first instict would be to find a code that acomplishes a similar task. I would then modify it. This is arguably not an original work of code. For a newbie programmer to advance in programming, he might need to solve this problem from the ground up. I'll attempt to solve this problem by proposing which patterns to consider in solving this problem. 

## The obvious ones

Some deisgn patterns may present themselves as obvious ingredients of the solution. First are the behvior patterns of observer and iterator. Everytime an entry for the price and location of an ingredient is inputted, we need that and all previous entries to be visible to the users. Observer is the concept of subscription- where an update listed is always published. The iterator concept would then comb through the updated list, and display relevant information. 

## Fuller Pciture 

These give us a game plan to execute a required task. We could embed a filed to submit a price tag, with information on where and how much. That price tag is added to the collection of price tag. To display all the price tags, we publish the list, and an iterator displays desired fields of "price" and "location". 

## AI Use in this Piece

ChatGPT was only used to check spelling and grammar. 
