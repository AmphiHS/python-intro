# Intro Python Assignments

You can complete the assignments below in any order. You must complete <b>3 out of the 4</b> programs to earn full credit.

## Student Questionnaire

<b>Your Task</b>: You are designing a program that will be used to get to know different students at Amphi. To do this, the program should ask the student for:

-  Their name
-  Their age
-  Their favorite safari animal
-  Choose 3 more questions of your own you'd like to ask

Once you have all of this information, you should address them by their name and tell them a positive message
For example: "Hi Kevin! Hope you have a great day!"

<b>Watch Out For</b>:

-  Watch your quotes around your strings
-  If you want to combine several strings, remember to use plus signs between them

<b>File to Edit</b>: student.py

<hr />

## Simple Calculator

<b>Your Task</b>: We are beginning the process of designing a calculator. Right now, it's going to be pretty simple - just doing basic operations. But later, as we learn more things, we'll make this calculator more useful and complex. For now, just create a calculator that asks the user for 2 numbers, then shows the result after:

-  Adding the two numbers
-  Subtracting the two numbers
-  Multiplying the two numbers
-  Dividing the two numbers
-  Taking the first number to the power of the second number (Ex: 2, 5 -> 32)
-  Finding the remainder after the first number is divided by the second number (Ex: 9, 4 -> 1)

For now, your program should print all of these answers on separate lines

<b>Watch Out For</b>:

-  Be careful about converting between strings and ints
-  If you forgot how to do exponents and remainders, look at the notes for this assignment

<b>File to Edit</b>: basic-calc.py

<hr />

## Create a Mad Lab

<b>Your Task</b>: You're going to create a Mad-Lib for the user to fill in. A Mad-Lib is like a story with some of the important information removed - for example, the character's name and location is something the user can fill in.

To create this mad-lib, you should first come up with your story. Try writing it in a google doc or on a sheet of paper. The only story requirement is it *must end with an explosion*.

Once you have a story, find places that the user can replace with their own suggestion. You'll need to make room for:

-  6 nouns
-  3 verbs
-  2 adjectives
-  2 adverbs
-  a location
-  a color

Once the user has entered all of their words, print out your story *on one line*.

<b>Watch Out For</b>:

-  Watch your syntax when you're _concatenating_ strings together

<b>File to Edit</b>: madlib.py

<hr />

## Chaos Generator

Schneider is interested in something called _Chaos Theory_, which is when you repeat a small process over and over and over again and see what happens. This idea can show up in Evolution (where small evolutionary changes lead to big results) and in how the Weather is predicted (where small random changes in atmosphere and temperature can lead to giant shifts in weather).

Schneider wants to investigate this concept in Math, specifically around this function: <b>f(x) = (x + 3)^2 - 33</b>. He's wondering what happens when you take a random number and plug it into that function, then take the _answer_ and plug it in to the function again. Here's an example:

- Start with the number 1
- f(1) = (1 + 3)^2 - 33 = -17
- Plug the answer (-17) back into the function:
- f(-17) = (-17 + 3)^2 - 33 = 163
- Keep repeating and see what happens

<b>Your Task</b>: Create a program that asks the user for a number, plugs it into the function _f(x) = (x + 3)^2 - 33_, then takes that answer and repeats this process 10 more times. When your program is done, 10 numbers should be printed to the screen.

<b>Watch Out For</b>:

-  Make sure you're using Order of Operations correctly
-  We haven't learned about loops yet, so you'll need to use copy and paste a lot for this program

<b>File to Edit</b>: chaos.py

<b>When You Finish:</b> When you test your code, you may notice that the numbers tend to get <b>very large very fast</b>. Can you find a number that, when you type it in, stays the same the entire time? This is called a <b>Fixed Point</b> because it doesn't change even as the rest of the system tends towards chaos.

<hr />
