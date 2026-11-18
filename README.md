
# Threads and Multithreading Laboratory

## Student Information
- **Name:** Princess Nashema M. Macasero
- **Section:** B186
- **Date:** November 18, 2026

## Laboratory Description

This laboratory demonstrates thread creation, multithreading, thread coordination, and shared-resource management using Python.

## Learning Outcomes

- Create and execute threads.
- Demonstrate concurrent execution.
- Explain thread coordination.
- Apply locks to protect shared resources.

## VII. Guide Questions and Answers

**1. What is the difference between a process and a thread?**

A process is a program that is currently running, while a thread is a smaller unit of execution inside a process. A process can have multiple threads.

**2. What are the advantages of using multithreading?**

Multithreading allows a program to perform multiple tasks concurrently. It can improve application responsiveness and resource utilization.

**3. How does multithreading improve application responsiveness?**

It allows a program to perform other tasks while one thread is busy. For example, an application can still respond to user input while downloading a file.

**4. What is the difference between concurrency and parallelism?**

Concurrency means handling multiple tasks by switching between them, while parallelism means executing multiple tasks at the same time.

**5. Why is a lock necessary when multiple threads access shared data?**

A lock prevents multiple threads from modifying shared data at the same time. It helps avoid race conditions and incorrect results.

**6. What might happen if a thread is not properly synchronized?**

It may cause race conditions, incorrect results, or unexpected program behavior.

**7. Can multiple threads execute simultaneously on a single-core processor? Explain.**

They can run concurrently but not truly simultaneously. The processor switches between threads quickly, making it appear that they run at the same time.

**8. How does the operating system manage kernel-level threads?**

The operating system manages kernel-level threads by scheduling them, assigning CPU time, and controlling their execution.

## Program Execution Screenshots

### Task 1 – Single Thread
[View Task 1 Screenshot](<img width="1540" height="878" alt="task1_single_thread" src="https://github.com/user-attachments/assets/f5051358-b1af-44ed-a89f-eec46799d4e1" />
)

### Task 2 – Multiple Threads
[View Task 2 Screenshot](<img width="1522" height="912" alt="task2_multiple_threads png" src="https://github.com/user-attachments/assets/4a145ddd-2242-4cfe-8138-9f0944467ea8" />
)

### Task 3 – Thread Synchronization using join()
[View Task 3 Screenshot](<img width="1525" height="764" alt="task3_thread_synchronization" src="https://github.com/user-attachments/assets/89bac011-ca11-4588-9e59-a7ac8d0dc7ae" />
)

### Task 4 – Shared Resource Management using Lock()
[View Task 4 Screenshot](<img width="1529" height="753" alt="task4_thread_lock" src="https://github.com/user-attachments/assets/4d06088d-9be9-492d-bcf0-0bc18af48789" />
)
