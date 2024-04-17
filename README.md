# Shortest Job First (SJF) Scheduling Algorithm

<ins>_**Experiment name:**_</ins> Implementation of the Shortest Job First (SJF) Scheduling Algorithm.

<ins>_**Description:**_</ins> The code is intended to implement the Shortest Job First (SJF) scheduling algorithm, a non-preemptive scheduling algorithm that chooses the waiting process with the shortest execution time to run next. The program uses the burst times of a group of processes to calculate the waiting time and turnaround time.The program begins by creating arrays for storing burst times, process IDs, waiting times, and turnaround times. It also defines variables for loop control, total time calculation, sorting, and storing average values. The user is then asked to enter the number of processes and the burst times for each one.After gathering the input, the program uses the selection sort algorithm to sort the burst times and corresponding process Id’s in ascending order. Next, the program computes the waiting time for each process by adding the burst times of all previous processes. It also calculates the total waiting time and then the average waiting time.

Similarly, the program calculates each process's turnaround time by combining its burst and waiting times. The total turnaround time is then determined, followed by the average turnaround time.Finally, the program shows a table with the process ID, burst time, waiting time, and turnaround time for each process.



<ins>_**Input:**_</ins>
The input required for this Shortest Job First (SJF) scheduling algorithm code consists of the following steps:
The number of processes: The user needs to input the total number of processes they want to schedule. This value should be an integer.
Enter burst times: After entering the number of processes, the user is prompted to enter the burst times for each process. Burst time represents the amount of time a process requires to complete its execution. The burst times should be entered one by one for each process.

<ins>_**Output:**_</ins>
The output of the provided  shortest Job First (SJF) Scheduling  code will display the turnaround time and waiting time for each process  and the final result:
![Picture4](https://github.com/simoon06/SJF/assets/139492391/ab15fa50-b760-46a8-9d15-b122098bbdcd)

