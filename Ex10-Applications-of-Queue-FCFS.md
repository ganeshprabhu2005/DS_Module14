# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1.Start with process, burst time, and waiting time arrays.

2.Loopthrough each process from i= 0 to n-1.

3.Compute tat[i] = burst_time[i] + wait_time[i].

4.End the algorithm. 

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: GANESH PRABHU J
RegisterNumber: 212223220023
*/
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[])
 {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}
```

## Output:

<img width="591" height="356" alt="437352549-415ad69b-2c73-422b-a90b-4f1bfd2a84d3" src="https://github.com/user-attachments/assets/3d76155c-f775-423c-9a5a-823f2341c5b9" />



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
