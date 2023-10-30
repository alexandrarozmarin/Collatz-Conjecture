# Collatz-Conjecture
Asks the user for an integers and runs the Collatz Conjecture on the integer, reporting various information; Python

## The Collatz Conjecture
The Collatz Conjecture is a mathematical conjecture that has been proved up to 2^68. The conjecture starts with a positive integer. If the integer is even, it gets divided by two. If the integer is odd, it is multiplied by 3 and then added to 1. The same rules are then applied to the resulting integer until, eventually, the resulting integer is 1. 


This program validates user input by only accepting a positive integer, then asks the user if they would like to put the program in silent mode. If the user responds "y", the conjecture will run but not display to the user. If the user responds "n", the proccess of the conjecture will display to the user. Regardless, two data points from the conjecture will print to the user: the period (the amount of steps it took for the integer to reach 1) and the highest number produced during the conjecture as a resulting integer. 
