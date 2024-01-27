---
layout: essay
type: essay
title: "Javascript and Genetics"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Engineering
---



## Class-Based versus Prototype-based Objects

Information and Computer Sceince (ICS) majors at University of Hawaii at Manoa (UHM) are taught Java in the beginning. We are then introduced to Javascript. I've always wondered why it was so. I wished that they would teach Python instead of Java, since much of the machine learning research uses Python. So far, I finshied the 3rd week of ICS 314: Software Engineering. It has focued on Javascript so far. Now I suspect that we were taught Java first to highlight the differences programming languages can have. 

## Tangled yarnball 

Courtesy is important to me. I joke that even though I'm not fully Japanese, I'm more Japanese than most Japanese by being sometimes overly polite.  That has helped me in hotels and patient care. The  downside is that I could assume others value courtesy as much as I do.  Jeff Bigler's [tact filters](https://www.mit.edu/~jcb/tact.html) was enlightening as it never occured that "tact" could be applied in the incoming direction. It's acutally quite ingenious- theoretically no words could bother you when you add "...but they really didn't mean that".  Once in a Java class, I had a classmate review my Pokemon code as "a big tangled yarn ball- you need to straighten this put". Thinking of it now, it's funny and it makes sense. At the time, I was livid. 

## Exhibit Smart 

In stackoverflow, I looked for posts tagged with Javascript with highest score- indicating high approval from users, who can wither downvote or upvote a post. [This](https://stackoverflow.com/questions/208105/how-do-i-remove-a-property-from-a-javascript-object) was one of them: short, sweet and to the point. They ask:


Given an object:

```javascript
let myObject = {
  "ircEvent": "PRIVMSG",
  "method": "newURI",
  "regex": "^http://.*"
};
```
How do I remove the property regex to end up with the following myObject?
```javascript
let myObject = {
  "ircEvent": "PRIVMSG",
  "method": "newURI"
};
```
To be fair, this question could be too simple such that googling or chatGPT is more suitable. However, there is no ambiguity about what the inquirer needs. It does not presume a particular solution either. The community has come up with multiple answers that can satisfy their requirements. 



## Exhibit Stupid

Stupid questions could still get answers. In this example, the [inquirer asks](https://stackoverflow.com/questions/77883878/different-outputs-in-node-event-loop): "I have a few questions. Why do files have different order of promise output if they are written the same way? The second question is, why does my VSC display this order in the second file, if according to the rules and documentation the order should be completely different? Sometmes Immediate 1 is below DNS. And lastly, please write which order in both options would be correct and why. I watched dozens of videos, there are different explanations everywhere, I don’t offer documentation, I’m still too inexperienced for it." 


The last part of the question assumes a hacker is willing to answer all of the questions. It's as if he's a professor writing an exam, or a paying client. His questions are painfully long to read. In addition, they fail to pinpoint which rule and documentation contradicts the varying order of outputs. As a result, the community just tells them that it's just the way it is; there is no reason for each asynchronous operation take the same duration for every execution. The inquirer is still very much left in the dark.  

