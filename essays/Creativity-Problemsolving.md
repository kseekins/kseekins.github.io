---
layout: essay
type: essay
title: "Data Types: Problem Solving and Creativity"
# All dates must be YYYY-MM-DD format!
date: 2024-01-17
published: true
labels:
  - Engineering
---



*How Many Programmers are needed to Wallpaper an Entire Room?*

My favorite answer is, depends on how thinly you slice them. This is an example of lateral thinking. We assume programmers provie labor to wallpaper the room- not becoming the raw material to cover the wall. In Java when we write a function, a data type of each parameter is specified. But in Javascript, it's not. How does that affect the product? Could a program act in unexpected ways? And if it does, would it be chaos or something fresh and innovative?

## Convenience 

This code from freeCodeCamp is a function that simulates the casino game Black Jack.

let count = 0;

function cc(card) {

  switch (card) {
  
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
    count++;
      break;
    case 10:
    case "J":
    case "Q":
    case "K":
    case "A":
      count--;
      break;
  }
  if (count > 0) {
    return count + " Bet";
  } else {
    return count + " Hold";
  }

}

cc(2); cc(3); cc(7); cc('K'); cc('A');

This code would be much harder to write if data types of parameters need to be set.  Converting "J" to a numerical value is easy, but how do we even get to that step? For example, if we were to specify cc (int card) like in Java, error will be thrown when cc(Q); is entered. It shows how Java does not operate like the human mind- it does not have a latitude of thinking that programmers could, at least theoretically, be used to wallpaper the entire room. 

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

  This code would work only if 7, 8 or 9, but no other choices were made for the parameter. My assumption was that the string msgDisplay would retrieve the values for variables count and call was only correct when it's declared. Once it was declared the string was static. The code was like a broken clock that was accurate twice a day- it would always return "0 Hold" no matter what. This is an example of an error when a programmer writes as if a compiler is human.  After writing all the lines about when to count up or down, I forgot that strings were immutable. 
  
## Error Message or...

   If a function is such that different data types can work, the behavior of the program will be harder to predict. There will be more opportunities to make wrong assumptions. A rudimentary example is the +. It can add numbers but it can also concatenate strings. In a way, programming can show us how WE are rigid. In my non-type specific parameters: a short horror story, programmers are sent to  wallpaper a room... If we're lucky, the compiler might just throw an error. 
  
## Reference

freeCodeCamp Challenge Guide: Counting Cards
Camperbot et al.
https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-counting-cards/16809
