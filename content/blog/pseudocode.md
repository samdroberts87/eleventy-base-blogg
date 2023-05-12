---
title: Pseudocode blog post
description: This is a post on My Blog about pseudocode
date: 2023-12-05
tags:
  - pseudocode
---
Today we learned about pseudocode. 

I was asked to provide pseudocode for the following task:

Fix start

Create a function called fixStart. It should take a single argument, a string, and return a version where all occurrences of its first character have been replaced with ‘*****’, except for the first character itself. You can assume that the string is at least one character long. For example:


fixStart('babble'): 'ba**le'

fixStart('turtle'): 'tur*le'


Here's what i came up with

/* 
Create Function with the name fixStart
  function will take a single argument, a     string
  initial feature of the function will       identify and store the value of the first character of the string as the variable named firstCharacter
Once the first charagter has been identified, the loop will begin to look for each further identical iteration of the first character
all further identical matches will be replaced with "*"
Loop will end once all remaining identical characters have been replaced
console log result
*/