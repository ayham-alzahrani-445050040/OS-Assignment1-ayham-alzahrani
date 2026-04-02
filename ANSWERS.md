# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**
a process is a running program with its own memory and thread is a smaller part inside the process and shares memory , processes are slower and use more resources , threads are faster and easier to use , that is why threads were used in this assignment.

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**
if a process does not finish in its time quantum , it stops and goes back to the queue and then it waits for its next turn this helps all processes to get there chance.

Example from my output:
```
▶ P2 executing quantum [2000ms]  
⏸ P2 completed quantum 2000ms  
↻ P2 yields CPU for context switch   


```

**Explanation of example:**
 P2 did not finish so it stopped after the time quantum then it was added again to the ready queue using addProcessToQueue()  it will run again when its turn comes.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

1. **New**: P1 is new when it is created with new thread(process).

2. **Runnable**: P1 becomes runnable when currentThread.start(); is called.

3. **Running**: P1 is running is the run() method is executing.

4. **Waiting**: P1 is waiting when Thread.sleep(stepTime); is used and the main thread waits using currentThread.join();.

5. **Terminated**: P1 is terminated when remainingTime <= 0 and the process finishes.
---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Game]

**Description**: 
 In a game, you can play and hear sound at the same time.  
**Why Round-Robin works well here**: 
each task gets a short time to run this keeps the game smooth and the sound clear
### Example 2: [Web Browser]

**Description**: 
 A browser can open many tabs at the same time without any delay
**Why Round-Robin works well here**: 
 every tab gets time to run this keeps all tabs working and not slow this happens so fast you won't even notice.
---

## Summary

**Key concepts I understood through these questions:**
1. 
2. 
3. 

**Concepts I need to study more:**
1. 
2. 
