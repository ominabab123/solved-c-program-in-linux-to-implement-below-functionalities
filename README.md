Download Link: https://assignmentchef.com/product/solved-c-program-in-linux-to-implement-below-functionalities
<br>
5/5 - (1 vote)

Write a C program in Linux to implement the following functionalities



Declare a global variable usr_interrupt=1

Write a signal handler function

void reset_signalvaluezero ()

When a SIGALRM signal arrives this function will be called in which variable will be set

sig_atomic_t usr_interrupt = 0;

Write a signal handler function

void Increment_signalvalue ()

When a SIGINT signal arrives this function will be called in which variable will be incremented theusr_interrupt by 1.

Write a main function

int main (void)

Handle two Signals SIGALRM and SIGINT.

Set the alarm for 10 sec

Parent process will sit in tight loop by keeping check on usr_interrupt variable once this variable will be 5 parent process will print some ENDING message and will exit.