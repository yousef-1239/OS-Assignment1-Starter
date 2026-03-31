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

### Entry 1 - [March 27, 2026, 3:00 PM]
**What I did**: Started the assignment and ran the code

**Details**: 
- Opened the project and ran it for the first time  
- Tried to understand how Round-Robin works in the code  
- Focused on how processes are added to the ready queue  

**Challenges**: 
Was confused about how threads represent processes  

**Solution**: 
Reviewed the code step by step and understood that each process runs as a thread  

**Time spent**: 1 hour

---

### Entry 2 - [March 28, 2026, 6:00 PM]
**What I did**: Started implementing Priority feature  

**Details**: 
- Added priority variable in Process class  
- Modified constructor  
- Tried to print priority in output  

**Challenges**: 
Was not sure where to display priority exactly  

**Solution**: 
Placed it inside addProcessToQueue() next to process name  

**Time spent**: 1.5 hours

---

### Entry 3 - [March 29, 2026, 7:30 PM]
**What I did**: Implemented Context Switch counter  

**Details**: 
- Added contextSwitchCounter variable  
- Tried different places to increment it  

**Challenges**: 
Didn’t know where exactly to increment the counter  

**Solution**: 
Placed it before currentThread.start() after testing  

**Time spent**: 1 hour

---

### Entry 4 - [March 30, 2026, 8:00 PM]
**What I did**: Implemented Waiting Time feature  

**Details**: 
- Added readyQueueEnterTime and waitingTime variables  
- Added setter/getter methods  
- Calculated waiting time before execution  

**Challenges**: 
Got confused where to place:
process.setReadyQueueEnterTime()  

**Solution**: 
Placed it inside addProcessToQueue() before creating the thread  

**Time spent**: 2 hours

---

### Entry 5 - [March 31, 2026, 9:00 PM]
**What I did**: Debugging and fixing issues  

**Details**: 
- Fixed waiting time calculation  
- Fixed output format for summary table  
- Verified all features (priority, context switch, waiting time)  

**Challenges**: 
Output formatting and aligning values  

**Solution**: 
Used printf to organize output properly  

**Time spent**: 1.5 hours 

---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: Approximately 10 hours  

**Most challenging part**:  
Understanding where to place waiting time calculations and context switch logic  

**Most interesting learning**:  
Seeing how processes move in the ready queue and how Round-Robin actually works  

**What I would do differently next time**:  
Plan feature implementation better and test each part separately before combining everything 
