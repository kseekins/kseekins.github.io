---
layout: essay
type: essay
title: "Smart Questions, Stupid Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-01-25
published: false
labels:
  - Engineering
---



## Respect My Time

In [How to Ask Questions The Smart by Eric Raymond and Rick Moen](http://www.catb.org/esr/faqs/smart-questions.html), there is a recurring theme of time.  A question can reflect whether the inquirer values of the time of the community. When asking a question, we can take steps to aim for the least amount of hassle to answer it. When I worked in the hotel industry, I read a book about the service culture at the Imperial Hotel in Tokyo. One of the bellman interviewed said his philosophy was to anticipate and remove any forseeable hassles that guests might face. I feel this is a good instinct to have. This week I asked the class Discord to debug my code. I provided the link to the code, with line numbers on which I commented on the issues below. Luckily I got help within 20 minutes, and my code started to work.


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

