# CSA04 – Operating Systems: Practical Programs

Register Number: 192565083

This folder contains all 40 lab programs for CSA04 – Operating Systems.

## Structure

For every experiment `N` (1–40):
- `N.txt` — Aim, Algorithm, full copy-paste-ready C program, sample input value(s), and sample output (plain text, easy to copy).
- `N_output.png` — Terminal-style screenshot of the sample output, for embedding in reports/GitHub.

## How to use

1. **Copy the code:** open `N.txt`, copy everything between the `PROGRAM (copy-paste ready):` divider lines into a `.c` file, then compile:
   ```
   gcc N.c -o N
   ./N
   ```
2. **Copy the input:** the `SAMPLE INPUT VALUE(S):` section in the same file lists exactly what to type at the prompts when you run the program.
3. **Output image:** `N_output.png` shows the expected output in a terminal-style screenshot — use it directly in reports or commit it alongside the code on GitHub.

## Uploading to GitHub

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cp PRACTICAL/*.txt PRACTICAL/*.png <your-repo>/PRACTICAL/
cd <your-repo>
git add PRACTICAL/
git commit -m "Add CSA04 OS practical programs (code + output screenshots)"
git push
```

## Experiment Index

 1. Process Creation using fork(), getpid(), getppid()
 2. File Copy using System Calls
 3. FCFS CPU Scheduling
 4. SJF Scheduling (Smallest Execution Time)
 5. Priority Scheduling (Highest Priority Next)
 6. Preemptive Priority Scheduling
 7. Non-Preemptive SJF Scheduling (with Arrival Times)
 8. Round Robin Scheduling
 9. IPC using Shared Memory
10. IPC using Message Queue
11. Multithreading using C
12. Dining Philosophers Problem
13. Memory Allocation Strategies (First/Best/Worst Fit combined)
14. Single Level Directory
15. Two Level Directory Structure
16. Random Access File Processing (Employee Details)
17. Banker's Algorithm (Deadlock Avoidance)
18. Producer-Consumer Problem using Semaphores
19. Process Synchronization using Mutex Locks
20. Reader-Writer Problem using Semaphores
21. Worst Fit Memory Allocation
22. Best Fit Memory Allocation
23. First Fit Memory Allocation
24. UNIX System Calls for File Management
25. I/O System Calls (fcntl, lseek, stat, opendir, readdir)
26. File Management Operations
27. Simulation of `ls` Command
28. Simulation of `grep` Command
29. Classical Process Synchronization Problem (Sleeping Barber)
30. Thread Concepts: create, join, equal, exit
31. FIFO Page Replacement
32. LRU Page Replacement
33. Optimal Page Replacement
34. Sequential File Allocation Strategy
35. Indexed File Allocation Strategy
36. Linked File Allocation Strategy
37. FCFS Disk Scheduling
38. SCAN Disk Scheduling
39. C-SCAN Disk Scheduling
40. File Access Permissions and Users in Linux
