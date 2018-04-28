# K1653_B41_DEEPUDEEPAK
project of os
OPERATING SYSTEM PROJECT

Name: DEEPU KUMAR.
Reg. No. : 11616204
Section : K1653
Email Id : erdeepukumar@gmail.com
GitHub Link: https://github.com/Deepudeepak76/K1653_B41_DEEPUDEEPAK
Question No. : 9

Problem:
 Design a scheduler that uses a preemptive priority scheduling algorithm based on dynamically changing priority. Larger number for priority indicates higher priority. When the process starts execution (i.e. CPU assigned), priority for that process changes at the rate of m=1.When the process waits for CPU in the ready queue (but not yet started execution), its priority changes at a rate n=2. All the processes are initially assigned priority value of 0 when they enter ready queue for the first time. The time slice for each process is q = 1. When two processes want to join ready queue simultaneously, the process which has not executed recently is given priority. I have also calculated the average waiting time for each process and my program is generic i.e. number of processes, their burst time and arrival time will be entered by user.

ALGORITHM: 

 
1. Declare a structure process (It is collection of all the necessary attribute a process contain like service time, Arrival time, Priority, Process ID, Processed flag etc.) 
2. A function processCreation() (It asked user about the number of process and enter details about it like Service time, arrival time, Process ID, and also assign initial priority to 0) 
3. A function sortProcess() (It sort all the process according to their arrival time) 
4. A function processor() (It does all the process execution, it responsible for processing or jobs displaying all the jobs and waitng time. 


Time Complexity:
O(nlogn)


Test Cases:

Process ID   Arrival Time          Service Time 
P1		 0			 4 
P2    	           	1 			 1 
P3  		2			 2 
P4 		3			 1 
Set initial priority of all the process to 0. 
Output: 
Average Waiting : 3.5

Boundary Conditions :
1.	Maximum of 10 processes can be scheduled using this code.
2.	Minimum 1 process should be there.
3.	Burst time must be greater than zero.

GitHub Link:  https://github.com/Deepudeepak76/K1653_B41_DEEPUDEEPAK  

