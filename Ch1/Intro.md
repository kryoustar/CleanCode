# Ch1. Clean Code Intro

Code Review Time : Continuous Development

Committing one small code can be devastating. 

At least one code reviewer should agree on your code.

Work is very important as well as Theory. 

It should be easily edit-able.

what is **good code** / **bad code**

## Bad Code

- Good code really matters
- Bad code can even bring a company down
    - Bugs cannot be easily repaired
    - Release cycles stretch
    - Load times grow and crashes increase
    - As more and more features are added, the code gets worse and worse
- Why do we write bad code?
    - We always want to go fast and are in a rush
    - We manage to make the program work, but do not clean up the code
    - We say we’ll go back and clean it up later, but ***“Later equals never”***

## The Cost of Bad Code

The productivity goes down when the code goes messier and messier

It becomes very hard to understand and, therefore, change the code

- Eventually, the development team demands a **redesign**
    - However, the new system also becomes a mess
- Why does good code rot into bad code?
    - The requirements change
    - The schedules are too tight
    - Stupid managers and intolerant customers
- No. The fault is in ourselves (i.e.,programmers)
    - Because we are unprofessional
    - It is our job to defend the code against managers and customers

## The Primal Conundrum

- All developers know that previous messes slow them down
- Yet, all developers feel the pressure to make messes in order to meet deadlines
- However, you will not make the deadline by making the mess
    - The mess will slow you down instantly, and force you to miss the deadline
- The only way to make the deadline
    - To keep the code as clean as possible at all times

## What is Clean Code?

- Bjarne Stroustrup
    
    Inventor of C++ and author of “The C++ Programming Language”
    

> *I like my Code to be **elegant** and **efficient**.
The logic should be **straightforward**.
The dependencies are **minimal** to ease maintenance.
Error handling is **complete**
Clean code does not tempt people to make the code messy with unprincipled optimizations.
Clean code does **one** thing well.*
> 
- Grady Booch
    
    Creator of the Unified Modeling Language(UML) and author of “Object Oriented Analysis and Design with Applications”
    

> *Clean code is **simple** and **direct.**
Clean code reads like **well-written** prose.
Clean code never obscures the designer’s intent but rather is full of **Straightforward** lines of control*
> 
- “Big” Dave Thomas
    
    Founder of Object Technology International (OTI), gotfather of the Eclipse strategy
    

> *Clean code can be read, and enhanced by a developer **other than** its original author.
It has unit and acceptance **tests**.
It has **meaningful** names.
It provides **one** way for doing one thing.
It has **minimal** dependencies.
It provides a clear and minimal API.
Code should be **literate**.*
> 
- Michael Feathers
    
    Author of “Working Effectively with Legacy Code”
    

> *Clean code always look like it was written by someone who **cares**.
There is nothing obvious that you can do to make it better.
All of those things were thought about by the code’s author.*
> 
- Ron Jeffries
    
    Founder of the Extreme Programming(XP), and author of “Extreme Programming Installed” and “Extreme Programming Adventures in C#”
    

> *In priority order, clean code:
- Runs all the **tests**
- Contains **no duplication***
(거의 비슷한 부분이 반복 된다면, 그 부분이 바뀌면 다른 곳도 다 바꾸어야함. ⇒ 함수로 만들 생각을 해야함!)
*- **Expresses** all the design ideas that are in the system
- **Minimizes** the number of entities such as classes, methods, functions, and the like*
> 
- Ward Cunningham
    
    Inventor of Wiki, Fit, and Extreme Programming (XP), the godfather of all those who care about code
    

> *You know you are working on clean code when each routine you read turns out to be pretty much what you **expected**.
You can call it beautiful code when the code also makes it look like the language was made for the problem.*
>
