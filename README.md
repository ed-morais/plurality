# Plurality

The Plurality program is a simple election simulation program that implements the plurality voting method. It is coded in C as a problem set of the Harvard's CS50 course. The program takes in command line arguments representing the names of the candidates running in the election and allows a user-specified number of voters to cast their votes. The program then declares the candidate with the most votes as the winner of the election.

## Getting Started
To get started, download the distribution code by executing the following commands in the terminal window of the CS50 IDE:

- `cd` to ensure you are in the home directory
- `mkdir pset3` to create a directory called pset3 in your home directory
- `cd pset3` to open that directory
- `mkdir plurality` to create a directory called plurality in your pset3 directory
- `cd plurality` to open that directory
- `wget https://cdn.cs50.net/2019/fall/psets/3/plurality/plurality.c` to download the problem's distribution code
- `ls` to verify the file plurality.c is present

The program is divided into two main parts: the vote function and the print_winner function. The vote function takes in a string representing the name of a candidate and updates the candidate's vote total if the name matches one of the candidates in the election. It returns true if the ballot is valid and false if it is not. The print_winner function is responsible for printing the name of the candidate who received the most votes in the election.

The program is designed to handle a maximum of 9 candidates, and assumes that no two candidates will have the same name.

## Running the program
To run the program, execute `./plurality [candidate1] [candidate2] [candidate3] ...` in the terminal window, where [candidate1], [candidate2], etc. are the names of the candidates running in the election.
