# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

A process is a program that is currently running and it has its own memory and system resources. Each process works independently from other processes. On the other hand, a thread is a smaller unit inside a process and it shares memory with other threads in the same process.

Threads are faster and easier to manage compared to processes because they use fewer resources. In this assignment, we used threads instead of processes because we wanted to simulate CPU scheduling without creating heavy system overhead. Threads made it easier to run multiple tasks and control their execution.
---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

In Round-Robin scheduling, if a process does not finish during its time quantum, it is moved to the end of the ready queue. This allows other processes to get CPU time and keeps the system fair.


Example from my output:
```
[P3 yields CPU for context switch
P3 (Priority: 3) added to ready queue]
```

**Explanation of example:**
Here, process P3 did not finish its execution within the time quantum. As a result, it gave up the CPU and was placed back at the end of the ready queue. This allows other processes to execute before P3 gets another turn.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

In my program, each process goes through several thread states during execution.

1. **New**:  
P1 is in the New state when the thread is created using `new Thread(process)` before calling `start()`.

1. **Runnable**:  
After calling `start()`, P1 becomes ready to run and waits for the CPU.

1. **Running**:  
P1 starts running when the CPU executes the `run()` method.

1. **Waiting**:  
P1 goes into waiting when `Thread.sleep()` is used to simulate execution time.

1. **Terminated**:  
After finishing execution, P1 enters the Terminated state.

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: Web Server Handling Requests

**Description**: 
A web server handles multiple user requests at the same time, like loading web pages or processing data.

**Why Round-Robin works well here**: 
Round-Robin ensures that every request gets a fair share of CPU time, which keeps the system responsive and prevents any single request from blocking others.

### Example 2: Operating System Scheduling

**Description**: 
Operating systems manage multiple programs running at the same time, such as browsers, apps, and background tasks.

**Why Round-Robin works well here**: 
Round-Robin gives each process a fair chance to run, which improves system performance and ensures all applications stay responsive.

---

## Summary

**Key concepts I understood through these questions:**
1. Difference between threads and processes  
2. How Round-Robin scheduling works  
3. Thread lifecycle and states

**Concepts I need to study more:**
1. Advanced scheduling algorithms  
2. Synchronization between threads
