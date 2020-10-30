# Closures in JavaScript

## Overview 

In today's class, students will learn about closures in JavaScript, and three different methods used to implament them.

## Learning Objectives

By the end of class, students will be able to:

* Make closures that can handle basic math

* Make closures that can change style elements 

* Make "Private" closures that can share one lexical environment


## Introduction (10 min Max)
Other Programming Languages such as java have private methods that allow them to be called upon ny other methods in the same class. Today we will be learning about JavaScript closures and how to mimick those private methods.


## Instructor Demo: Closure #1 with basic math (5 min) 

* Open `ClosureDemo/ClosureDemo.html` in your browser and demonstrate Demo #1. Make sure to highlight the following. 

  * Function DivisionClosure takes in a single argument 'A' and returns a funcation that divides 'A' and another argument or variabele.

* DivClosure1 & DivClosure2 are closures that both store different lexical environments or have their own. 
 
 
 ## Student Do: Closure #1 (15 min) 

* Direct students to the activity instructions found in `/'unsolved/UnSolvedClosure1.html`


## Instructor Review: Closure #1 (15 min) 

* Open `Solved/SolvedClosure1.html` in your browser and demonstrate closure #1. Make sure to highlight the following. 

* AddClosure1 & AddClosure2 are closures that both store  lexical environments. Thats what lets us use them for basic. 
 
 
 
 
 ## Instructor Demo: Closure #2 Effecting style elements  (5 min) 

* Open `ClosureDemo/ClosureDemo.html` in your browser uncomment and demonstrate Demo #2. Make sure to highlight the following. 

  * 'document.body.style.fontSize = num + 'px';' allows us to change the selected style element  


* VAR S12, S13, S14 are all closures that store lexical environments to hold the selected style element value. 

*  'document.getElementById('S12').onclick = S12;' attaches the closure to the A tags 

 
 
 ## Student Do: Closure #2 (15 min) 

* Direct students to the activity instructions found in `/'unsolved/UnSolvedClosure2.html`


## Instructor Review: Closure #2 (15 min) 

* Open `Solved/SolvedClosure2.html` in your browser and demonstrate closure #2. Make sure to highlight the following. 

* The Margin variables are closures  




## Instructor Demo: Closure #3 (5 min) 

* Open `ClosureDemo/ClosureDemo.html` in your browser uncomment and demonstrate Demo #3. Make sure to highlight the following. 

  * Each closure shares one lexical environment 

  * Function Adjuster and Var private can not be accessed from outside the anonymous function


 
 ## Student Do: Closure #3 (15 min) 

* Direct students to the activity instructions found in `/'unsolved/UnSolvedClosure1.html`


## Instructor Review: Closure #3 (15 min) 

* Open `Solved/SolvedClosure1.html` in your browser and demonstrate closure #1. Make sure to highlight the following. 

* If statement can be used to determine which of the two outcomes should happen.

