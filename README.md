# CPU-Task-Scheduler
CPU Task Scheduler in Python

A Python program that simulates CPU scheduling algorithms:
First-Come, First-Serve (FCFS)
Round Robin (RR)
Non-Preemptive Priority Scheduling

This project allows users to input tasks and run different scheduling strategies to see how processes are executed.

📜 Features

Input multiple tasks with:
Name
Burst Time
Priority

Supports 3 scheduling algorithms:

FCFS – Executes tasks in arrival order.

Round Robin – Executes tasks in fixed time slices (quantum).

Priority Scheduling – Executes tasks based on priority (lower number = higher priority).

Displays start time and finish time for each task.

Menu-driven interface for easy navigation.

🛠 Technologies Used

Python 3.x

collections.deque (for Round Robin queue)

Run the script:

python scheduler.py
Enter the number of tasks and their details.
Choose the scheduling algorithm from the menu.

📌 Example Run
Enter the number of tasks: 3  
Enter name for Task 1: A  
Enter burst time for A: 5  
Enter priority for A (lower number = higher priority): 2  
Enter name for Task 2: B  
Enter burst time for B: 3  
Enter priority for B (lower number = higher priority): 1  
Enter name for Task 3: C  
Enter burst time for C: 4  
Enter priority for C (lower number = higher priority): 3  

Choose a Scheduling Algorithm:  
1. First-Come, First-Serve (FCFS)  
2. Round Robin (RR)  
3. Priority Scheduling (Non-Preemptive)  
4. Exit  
Enter your choice (1-4): 1  

Running First-Come, First-Serve (FCFS) Scheduling:  
A: start at 0, finish at 5  
B: start at 5, finish at 8  
C: start at 8, finish at 12  

🚀 Future Enhancements

Add Preemptive Priority Scheduling.

Add Shortest Job First (SJF) algorithm.

Visualize execution with Gantt charts.

Include average waiting time and turnaround time calculation.
