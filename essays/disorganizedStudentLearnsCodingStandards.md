---
layout: essay
type: essay
title: "A Disorganized Student Learns Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: false
labels:
  - Engineering
  - ADHD
---



*Why Is Everything a Mess?*

Today we had an in class exam that involved: 1) coding a function that returns true when 'love' is in a string; 2) complying with ES lint coding standards. Despite preparing for the exam and liking the subject, I failed. I'm slower in doing things in general- in another example, I would almost always be the last student to be done in organic chemistry lab. It makes me wonder if there are other forms of intelligence beyond completing a given task quickly. If we could display our minds in console windows, would more academically successful students have easier to read code then mine?

## Notes

My closest experince outside of coding to coding standards is note taking. I noticed how I tend to write in big letters. I would often cross out words and write a correction. This is the one the more organized notes I have: 

<img class="img-fluid" src= "./IMG_1005.jpeg">
## It's not how it works

So far this freedom of parameters seem like a blessing. It mirrors our reality better, in which we can accomdate and accept that J can mean 11 when we play a card game. But where is the trade off? Let's look at the code I wrote for the previous prompt.

let count = 0;

function cc(card) {
  var call = "Hold";
  var msgDisplay = count + " " + call;
  switch (card) {
    case 2:
    case 3: 
    case 4:
    case 5: 
    case 6:
      count++;
      break;
    case 10:
    case 'J':
    case 'Q':
    case 'K':
    case 'A': 
      count--;
      break; 
  }
  if (count > 0){
    call = "Bet";
    return msgDisplay;
  } else {
   

  return msgDisplay ;
  }

  cc(2); cc(3); cc(7); cc('K'); cc('A');
}

  This code would work only if 7, 8 or 9, but no other choices were made for the parameter. My assumption was that the string msgDisplay would retrieve the values for variables count and call. This was only correct when it was declared. Once it was declared the string was set in stone. The code was like a broken clock that was accurate twice a day- it would always return "0 Hold" no matter what. This is an example of an error when a programmer writes as if a compiler is human.  After writing all the lines about when to count up or down, I forgot that strings were immutable. 
  
## Error Message or...

   If a function is such that different data types can work, the behavior of the program will be harder to predict. There will be more opportunities to make wrong assumptions. A rudimentary example is the +. It can add numbers but it can also concatenate strings. In a way, programming can show us how WE are rigid. In my non-type specific parameters: a short horror story, programmers are sent to  wallpaper a room... If we're lucky, the compiler might just throw an error. 
  
## Reference

freeCodeCamp Challenge Guide: Counting Cards
Camperbot et al.
https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-counting-cards/16809
