# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

In this assignment, I learned how multithreading works in practice, not just in theory. I understood how threads are created using `new Thread()` and how they start execution using `start()`. I also learned about different thread states such as New, Runnable, Running, Waiting, and Terminated, and how a thread moves between these states during execution. One important thing I noticed is how threads can simulate multiple processes running at the same time. The use of `Thread.sleep()` helped me understand how execution time can be controlled. Overall, this assignment made the concept of concurrency much clearer to me.

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

The most challenging part of this assignment was implementing the waiting time feature. It was difficult to figure out where exactly to calculate the waiting time in the code. At first, I placed it in the wrong location, which gave incorrect results. Also, understanding how the process moves in and out of the ready queue made it more confusing. Another challenge was making sure that the waiting time accumulates correctly after each cycle. This required careful tracing of the program execution. Overall, it took time to fully understand how to track time properly.

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

To overcome the challenges, I started by breaking the problem into smaller parts. I focused on understanding one feature at a time instead of trying to solve everything at once. I carefully read the code and followed the execution step by step to understand how the scheduling works. I also tested the program multiple times after each change to make sure everything works correctly. When something didn’t work, I checked the logic and adjusted the code gradually. This step-by-step approach helped me solve the problems and understand the concepts better.

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

Multithreading is widely used in real-world applications. For example, web browsers use multiple threads to load web pages, images, and scripts at the same time. This makes browsing faster and more responsive. Another example is in games, where different threads handle graphics, user input, and background processes simultaneously. Mobile applications also use threads to perform tasks like downloading data without freezing the user interface. From this assignment, I understood how threads improve performance and allow systems to handle multiple tasks efficiently.

---

## Additional Reflections

### What would you like to learn more about?

I would like to learn more about synchronization between threads and how to avoid issues like race conditions. I am also interested in learning about more advanced scheduling algorithms and how they compare to Round-Robin in real systems.

---

### How confident do you feel about multithreading concepts now?

I would say I am at an intermediate level. I understand the basic concepts of threads, scheduling, and execution flow. However, I still need more practice with advanced topics like synchronization and thread safety. With more practice, I believe I can become more confident.

---

### Feedback on the assignment

The assignment was very helpful in understanding how operating system concepts work in real code. It was a bit challenging at first, especially with tracking waiting time, but it helped me learn a lot. I think it is a good balance between theory and practice. It would be helpful if more examples were provided for the features, but overall it was a valuable learning experience.
