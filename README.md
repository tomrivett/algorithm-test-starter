# Coding Test

## Problem
In the NZ banking system, we have ATMs. ATMs are used to take physical cash out of your account. However, a problem with some ATM's is that they don't give you a useful selection of notes when you request some money. There's nothing worse than going to an ATM, requesting $200 and getting 4 x $50 notes back.

We want to create an ATM that returns a more friendly set of notes back to the user. We want to do the following:

* Give the user at least 1 note, from smallest to largest.
* Then give the remaining notes to the user using the least number of notes possible

Some examples:

The user requests $15:
* Give the user one of each of the smallest notes possible - 1 x $5 + 1 x 10

Result: 1 x $5 + 1 x $10

The user requests $10:
* Give the user one of each of the smallest notes possible - 1 x $5
* Give the user the remaining amount using the least number of notes possible - 1 x $5

Result: 2 x $5

The user requests $150
* Give the user one of the smallest notes possible - 1 x $5 + 1 x 10 + 1 x 20 + 1 x 50
* Give the user the remaining amount using the least number of notes possible - 1 x 50 + 1 x 10 + 1 x 5

Result: 2 x $5 + 2 x 10 + 1 x 20 + 2 x 50

## Your Challenge
Your challenge is implement a `getNotes` function.
* This function gets the amount of money the user requested as a number.
* You should write tests for your getNotes function

It is recommended you do this via test driven development. However, if you aren't comfortable with this, you shouln't attempt it.
The goal of the challenge is that you end up with a getNotes function with a set of useful tests


## Installation
~~~
npm install
~~~

## Test
~~~
npm run test
~~~

## Start
~~~
npm start
~~~
