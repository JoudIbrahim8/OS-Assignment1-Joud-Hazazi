# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.
> 
| Field | Your Answer |
|---|---|
| **Full Name** | Joud Ibrahim Hazazi |
| **Student ID** | 445052049 |
| **University Email** | 445052049@std.psau.edu.sa |
| **GitHub Username** | JoudIbrahim8 |
| **Repository Link** | https://github.com/JoudIbrahim8/OS-Assignment1-Joud-Hazazi |


---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 7, 2026]
**What I did**: Set up the project and connected GitHub with the required development tools.


**Details**: 
- Opened GitHub and accessed the assignment repository.
- Connected the repository with the required development tools.
- Prepared the project environment to start working on the assignment.


**Challenges**: I needed to understand how the required tools and the GitHub repository worked together.

**Solution**:I followed the setup instructions and checked that I could access the project files.

**Time spent**: Approximately 2 hours.

---

### Entry 2 - [ October 9, 2026]
**What I did**: Implemented the required scheduling features and uploaded the changes to GitHub.

**Details**:
 - Implemented Feature 1: Process Priority.
- Implemented Feature 2: Context Switch Counter.
- Implemented Feature 3: Waiting Time.
- Created separate commits for the features and pushed the changes to GitHub.
**Challenges**: Understanding the existing scheduler code and making the required changes.

**Solution**: Reviewed the code, implemented the features, and used Git to save and upload the changes.


**Time spent**: Approximately 4 hours.

---

### Entry 3 - [October 10, 2026]
**What I did**: Reviewed the project and worked on the technical answers.

**Details**:
- Reviewed the Round-Robin scheduling concepts.
- Worked on explaining the ready queue behavior.
- Reviewed the Java thread lifecycle states.
- Checked the project documentation before submission.

**Challenges**: Understanding the differences between thread states and explaining how they relate to the code.

**Solution**: Reviewed the relevant methods, including `Thread.start()`, `Thread.sleep()`, and `Thread.join()`.

**Time spent**: Approximately 3 hours.

---

### Entry 4 - [October 10, 2026]
**What I did**: Reviewed the project implementation and checked the final documentation.

**Details**:
- Reviewed the three implemented features.
- Checked the development log entries.
- Reviewed the technical answers for clarity.
- Prepared the project for final submission.

**Challenges**: Making sure the project documentation was complete and consistent.

**Solution**: Reviewed the project files and checked the required submission items.

**Time spent**: Approximately 2 hours.

---

### Entry 5 - [October 10, 2026]
**What I did**: Completed the final review of my assignment and prepared it for submission.

**Details**:
- Reviewed the development log.
- Checked the technical answers.
- Reviewed the GitHub repository and commit history.
- Checked the remaining submission requirements.

**Challenges**: Making sure all required assignment components were completed before submission.

**Solution**: Reviewed the assignment checklist and checked the project files.

**Time spent**: Approximately 1 hour.

---

### Entry 6 - [October 10, 2026]
**What I did**: Verified that the project changes were saved and uploaded to GitHub.

**Details**:
- Checked the Git status to confirm that the working tree was clean.
- Reviewed the development log entries.
- Verified that the local branch was synchronized with the remote repository.

**Challenges**: Making sure all changes were committed and pushed successfully.

**Solution**: Used Git status and checked the repository synchronization.

**Time spent**: Approximately 1 hour.


---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

I learned that multithreading allows a program to execute tasks using separate threads. I learned that the Runnable interface defines the task that a thread will perform. The Thread.start() method starts a new thread, while Thread.join() makes one thread wait for another thread to finish. I also learned that Thread.sleep() pauses a thread temporarily. In this assignment, I explored how threads represent processes in a CPU scheduling simulation. I understood that threads can have different states during execution. I found it interesting to learn how thread execution is managed by the program.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was understanding the existing Java code and how the scheduler worked. At first, it was difficult to understand how threads represented processes and how the ready queue managed them. I also needed time to understand how the different methods worked together. Implementing the three required features without affecting the existing code was another challenge. I worked through the project step by step to understand its structure. This assignment showed me the importance of understanding existing code before making changes. Completing the features helped me become more familiar with Java and CPU scheduling.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame the challenges by working through the assignment one step at a time. I reviewed the project instructions and examined the existing Java code to understand its structure. I implemented the required features separately instead of changing everything at once. I used the terminal and Git to manage the project and save my changes. I checked the results after making changes to identify potential problems. When I did not understand a step, I reviewed the instructions and asked for help. This approach helped me organize my work and make progress.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful in many real-world applications because it allows different tasks to run concurrently. For example, a web browser can handle user interactions while performing background tasks. A music player can continue playing music while the user browses the application. Mobile applications can use background threads to perform operations without freezing the user interface. Games can also use multiple threads to process game logic and load resources. These examples relate to the assignment because the scheduler manages processes and their execution. Understanding multithreading helps developers build applications that are more responsive and efficient.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is an independent program with its own memory space, while threads are units of execution that can share memory within the same process. Creating separate operating-system processes generally requires more resources and has more communication overhead than using threads. In this assignment, the Process class represents a simulated process, while a real Java thread executes it. The addProcessToQueue() method uses new Thread(process) to create a thread for the simulated process.
## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process does not finish within its time quantum, it returns to the end of the ready queue. In my program, P3 has a burst time of 8766ms and the time quantum is 4000ms. P3 was re-queued two times before finishing, with 4766ms remaining after the first quantum and 766ms after the second quantum. It then ran for the remaining 766ms and finished. Re-queueing improves fairness because other processes get a chance to use the CPU between P3's turns.
Example from my output:
```
P3 executing quantum [4000ms]
Remaining time: 4766ms
P3 yields CPU for context switch
P3 added to ready queue

P3 executing quantum [4000ms]
Remaining time: 766ms
P3 yields CPU for context switch
P3 added to ready queue

P3 executing quantum [766ms]
Remaining time: 0ms
P3 finished execution!
```

**Explanation of example:**
P3 uses its first 4000ms time quantum but has 4766ms remaining, so it returns to the ready queue. After its second 4000ms quantum, it has 766ms remaining and is re-queued a second time. On its third turn, P3 uses the remaining 766ms and finishes execution. This shows how Round-Robin allows other processes to use the CPU between P3's turns, improving fairness.
## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1's thread is in the New state after `new Thread(process)` creates it in `addProcessToQueue()`, before `start()` is called.
   

2. **Runnable**: P1 becomes Runnable when the scheduler calls `start()`; it is ready to run and waits for CPU time.


3. **Running**:  P1 runs when the scheduler gives its thread CPU time and its `run()` method executes. In Java, Running is included in the `RUNNABLE` state.

4. **Waiting**: While P1 calls `Thread.sleep()`, its thread is technically in `TIMED_WAITING`; separately, the main thread waits for P1 when it calls `join()`.

5. **Terminated**: P1's thread becomes Terminated when its `run()` method finishes and the thread exits.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling Among Ready Processes


**Description**:
An operating system can use Round-Robin scheduling to share CPU time among ready processes.
Each process receives a short time quantum, and a context switch lets the next process run when the quantum ends.

**Why Round-Robin works well here**:
It gives processes turns in the ready queue, so one process cannot keep the CPU indefinitely.
This improves fairness and responsiveness, especially when many programs are running.

### Example 2: A Server Handling Client Requests

**Description**:
A server can take turns running tasks for multiple client requests using worker threads.
Each task gets a short time quantum, and a context switch lets another task make progress.
**Why Round-Robin works well here**:
It prevents one long request from holding up all the others.
This can make the service feel more responsive when many clients are active.
## Summary

**Key concepts I understood through these questions:**
1.Threads have a lifecycle, and method calls such as `start()`, `sleep()`, and `join()` affect thread states.
2.Round-Robin scheduling gives processes turns using a fixed time quantum.
3.Re-queueing and context switching help share CPU time among processes.

**Concepts I need to study more:**
1.The exact Java thread states and how they differ from conceptual states such as Running.
2.How operating systems choose time quanta and handle context-switching overhead.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
