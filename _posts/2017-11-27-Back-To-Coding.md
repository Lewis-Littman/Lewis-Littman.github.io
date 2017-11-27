---
title: Back To Coding
layout: post
author: lewis.littman
permalink: /back-to-coding/
source-id: 1oGbisXStYuEaPeFP0xe9tNLesgRZwv06Swwg10QqH4c
published: true
---
<table>
  <tr>
    <td>Title</td>
    <td>Back To Coding</td>
    <td>Date</td>
    <td>27/11/17</td>
  </tr>
</table>


<table>
  <tr>
    <td>Starting point:</td>
    <td>A good understanding of how to code using Python. However, the last time I coded using Python was quite a long time ago.</td>
  </tr>
  <tr>
    <td>Target for this lesson?</td>
    <td>To recap and what I had learnt previously and make a simple AI system that I can have a small conversation with.</td>
  </tr>
  <tr>
    <td>Did I reach my target? 
(add details to "Lesson Review")</td>
    <td>Yes as I managed to create this AI system as you will see later.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Lesson Review</td>
  </tr>
  <tr>
    <td>How did I learn? What strategies were effective? </td>
  </tr>
  <tr>
    <td>This lesson I created an AI system that I managed to code so that I could have a small conversation with. The system has 5 basic questions as if I was at a restaurant. The Coding looks like this:
a=input("Hello, what is your name?")
print("Hey, " + a + ".")

answered=0
while answered !=1: #Going into loop to find out how user feels, loop stops once we have a yes or no answer.
  b=input("Are you feeling good today (yes or no)")
  if b.lower()=="yes":
    print("Cool, i am glad you are feeling good!")
    answered=1
  elif b.lower()=="no":
    print("Great, I don't care!")
    answered=1
  else:
    print("Please input a valid answer") #Do 3 more questions - multiple choice.

answered2=0
while answered2 !=1:
  c=input("What would you like to drink today? \n A) Water \n B) Coca-Cola \n C) A cup of tea \n D) Orange Juice")
  if c.lower()=="a" or "b" or "c" or "d":
    print("Good choice, now pick something to eat!")
    answered2=1
  else:
    print("Please input a valid answer")

answered3=0
while answered3 !=1:
  d=input("To eat you can have either: \n A) A Burger \n B) A Pizza \n C) A steak \n D) Fish and Chips")
  if d.lower() == "a" or "b" or "c" or "d":
    print("Nice choice!")
    answered3=1
  else:
    print("Please input a valid answer")

answered4=0
while answered4 !=1:
  e=input("Are you enjoying your meal? (Yes or No)")
  if e.lower() == "yes":
    print("That's great!")
    answered4=1
  elif e.lower() == "no":
    print("Oh no...")
    answered4=1
  else:
    print("Please input a valid answer")

The functions answered= 0 and while answered !=1 allow us to loop the following bit of code until we get the answer we want.
Variables allow us to store bits of information and pass information through different functions, like printing.
Print allows you to write out and print a message.
If, elif and else allow you to follow a sequence of function one after the other based on our response.
These are the basic commands and bits of coding that we used for this.</td>
  </tr>
  <tr>
    <td>What limited my learning? Which habits do I need to work on? </td>
  </tr>
  <tr>
    <td>I need to work on remembering to use white space/using tab to create indents when using if, elif and else and when using colons (which basically tells the code to then do this). I kept forgetting this it slowed me down a lot but next week I will remember and I will be able to work faster.</td>
  </tr>
  <tr>
    <td>What will I change for next time? How will I improve my learning?</td>
  </tr>
  <tr>
    <td>Next week I am going to work faster as I am now refreshed on how to code using Python again and I also won't forget to use white space/indents. This will improve my learning a lot as I can get through more work quicker. I will remember to use white space/indents as I will practice before next week.</td>
  </tr>
</table>


