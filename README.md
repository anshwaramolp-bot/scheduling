Non-preemptive priority CPU scheduling is a scheduling algorithm in which each process is assigned a priority, and the CPU is allocated to the process with the highest priority among the arrived processes. In this method, once a process starts execution, it continues until completion without interruption.
In this program, processes are provided with their Process ID, Arrival Time (AT), Burst Time (BT), and Priority (PR), where a higher numerical value indicates a higher priority. The scheduler selects the highest-priority process from the ready queue at the current time. If multiple processes have the same priority, the one with the earlier arrival time is selected.
The program calculates:
Waiting Time (WT) = Turnaround Time − Burst Time
Turnaround Time (TAT) = Completion Time − Arrival Time
It also computes the average waiting time and average turnaround time for all processes. If no process is available at a given time, the CPU remains idle until the next process arrives.
