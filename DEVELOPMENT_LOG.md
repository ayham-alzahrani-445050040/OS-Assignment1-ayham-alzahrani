# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:



### Entry 1 - [on Mar 29 - 9pm ]
**What I did**: 
I created a GitHub account and connected it with VS Code I also changed the student ID in the code and started understanding the assignment.

**Details**:
I read the assignment instructions and tried to understand the idea of the project I looked at the code and saw how the program works in general I also updated the student ID in the code to my own ID.

**Challenges**: 
it was my first time using GitHub and VS Code so I was a bit confused at the beginning I didn’t know how to connect them or use them .

**Solution**: 
I asked one of my friends for help and he explained some parts to me I also followed the explanation in the assignment, and that helped me understand better.

**Time spent**: 
About 2 hours

---

### Entry 2 - [on Mar 30 - 8pm]
**What I did**: 
In this step I tried to understand the given code and what it does and the main objective.

**Details**: 
The program is about CPU scheduling using round robin , each process runs for a small time then stops and lets another process run.
The program takes one process runs it for a time quantum then puts it back if it is not finished and join makes sure one process runs at a time.

**Challenges**:
At first, the code ws hard to understand I was confused about threads and how the processes run.
I also didnt understand how the queue works at the beginning.

**Solution**: 
I read the assignment and its details carefully then I divided the code into smaller parts and started reading it step by step.
I also used AI to help me understand some parts that were confusing especially the threading part.
this made it easier for me to understand the code.

**Time spent**: 
About 2-3 hours
---

### Entry 3 - [on apr 1 - 4 pm]
**What I did**:
I added the priority feature to the process.

**Details**: 
I added a new variable called priority inside the process class then I updated the constructor to receive the priority after that I generated a random priority between 1 and 5 in the main method then printed the priority when the process is added to the ready queue.

**Challenges**: 
at first I was confused about how to pass the priority value to the Process class and how to use it correctly.

**Solution**: 
I read the code carefully and checked how other variables are used I also asked AI to give me hints for help and tried step by step until it worked 
**Time spent**:
2 hours

---

### Entry 4 - [on apr 1 - 8pm]
**What I did**: 
after the break I added a counter to count context switches.

**Details**: 
I created a static variable called context_switche. This variable starts from 0 then I increased it every time a process starts running using start() and added the increment before starting the thread , at the end of the program I printed the total number of context switches.

**Challenges**: 
 I didn’t understand what context switch means. I was also confused about where to put the counter.

**Solution**: 
I read the assignment again and also checked the slides this helped me understand what context switch means. 
I also used AI for small hints and then I knew where to add the counter.

**Time spent**: 
around 2 hours

---

### Entry 5 - [on apr2 - 2 am]
**What I did**:
after anthour break I added waiting time for each process.

**Details**: 
I added two variables in the process class one for waiting time and one to store the last time the process entered the queue , I used System.currentTimeMillis() to get the time , I used LinkedList instead of ArrayList because the original code was already using it

**Challenges**: 
I didn’t understand how to calculate waiting time and where to put the code.

**Solution**: 
I read the assignment and the slides again I followed the structure of the given code and did not change it much and  added the needed variables step by step and tested the program until it worked

**Time spent**: 
about 2 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: [9 hours]

**Most challenging part**: understanding the cod and how each part works together

**Most interesting learning**: learning how Round Robin scheduling works and how processes share the CPU

**What I would do differently next time**: I would start earlier and try to understand the code faster from the beginning.
