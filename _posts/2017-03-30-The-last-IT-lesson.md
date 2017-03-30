---
title: The last IT lesson
layout: post
author: lewis.littman
permalink: /the-last-it-lesson/
source-id: 14ggQrRrrGd2bGxeafd9vX1rDoPGqqo8xMXiBglt-WMw
published: true
---
<table>
  <tr>
    <td>Title</td>
    <td>The last IT lesson</td>
    <td>Date</td>
    <td>30/3/17</td>
  </tr>
</table>


<table>
  <tr>
    <td>Starting point:</td>
    <td>Quite a good knowledge of python and all the different ways to use it and how to create relatively simple codes but also some difficult ones too.</td>
  </tr>
  <tr>
    <td>Target for this lesson?</td>
    <td>To complete all the tasks that Mr Keen sets us during the lesson.</td>
  </tr>
  <tr>
    <td>Did I reach my target? 
(add details to "Lesson Review")</td>
    <td>Yes as I finished all the task that Mr Keen set us and I also complete the homework which was to create this code that helps with maths.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Lesson Review</td>
  </tr>
  <tr>
    <td>What did we do today?</td>
  </tr>
  <tr>
    <td>Today we did not learn much as we were just applying our knowledge to create a code. I guess this is teaching us if we actually know the coding language. The end result is the piece of code below. This code has a bunch of functions that all do different maths calculations. This code asks for what function you want to use and then asks for the measurements needed to complete that function. It will then complete the maths and print the result.

from math import pi

def perimeter():
  perimeter = int(width) + int(width) + int(height) + int(height)
  return perimeter
  
def area():
  area = int(height) * int(width)
  return area
  
def volume():
  volume = int(height) * int(width) * int(depth)
  return volume

def circumference():
  circumference = float(pi) * (float(radius) * 2)
  return circumference
  
def areaC():
  areaC = float(pi) * float(radius) ** 2
  return areaC

def AreaP():
  AreaP = int(baseP) * int(Perpendicularh)
  return AreaP
  
print ("Welcome to the Maths Cheat")
while True:
  ans = input("What function would you like to use? \n 1: perimeter of a rectangle/square \n 2: the area of a rectangle/square \n 3: the volume \n 4: the circumference of a circle \n 5: the area of a circle \n 6: the area of a parallelogram \n 7: exit")
  if ans == "1":
    width = input("What do you want the width to be?")
    height = input("What do you want the height to be?")  
    print (perimeter())
  elif ans == "2":
    width = input("What do you want the width to be?")
    height = input("What do you want the height to be?")
    print (area())
  elif ans == "3":
    width = input("What do you want the width to be?")
    height = input("What do you want the height to be?")
    depth = input("What do you want the depth to be?")
    print (volume())
  elif ans == "4":
    radius = input("What do you want the radius to be?")
    print (circumference())
  elif ans == "5":
    radius = input("What do you want the radius to be?")
    print (areaC())
  elif ans == "6":
    baseP = input("What is the base of the parallelogram?")
    Perpendicularh = input("What is the Perpendicular height?")
    print (AreaP())
  elif ans == "7":
    print ("Thank you for using the Maths Cheat!")
    break
  else:
    print ("Please enter a valid number 1-7")
</td>
  </tr>
  <tr>
    <td>When will I next post?</td>
  </tr>
  <tr>
    <td>Due to the way our lessons work during year 8 we will be moving on to drama after the Easter holiday meaning I probably won't be posting for a while. I will most likely be back posting at the start of the next academic year.</td>
  </tr>
</table>


