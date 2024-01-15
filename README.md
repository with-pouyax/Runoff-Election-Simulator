# Runoff Election Simulator
This C program simulates a runoff election using ranked-choice voting. In a runoff election, voters rank candidates in order of preference, and the program determines the winner through an instant runoff process.

### Getting Started
#### Prerequisites
Ensure you have a C compiler installed (e.g., GCC).
#### Installation
Clone the repository:


#### Usage
Enter the number of voters.
For each voter, rank the candidates in order of preference.
The program will simulate the runoff election and print the winner.
#### Features
##### Simulates Ranked-Choice Runoff Elections:
The program implements a ranked-choice voting system to simulate runoff elections accurately.
##### Handles Ties:
The program correctly handles tied elections and determines the winner based on ranked preferences.

### Rules for Runoff Election

#### Ranked-Choice Voting:

Voters rank candidates in order of preference.
Each voter's ballot includes their first, second, third, and subsequent choices.

#### Majority Requirement:

A candidate must receive more than 50% of the total votes to be declared the winner.
If a candidate achieves this majority in the initial count, they are declared the winner.


#### Instant Runoff:

If no candidate has a majority in the initial count, an instant runoff occurs.
The candidate with the fewest votes is eliminated, and their votes are redistributed to the next preference on each ballot.

#### Recount Process:

The recount process continues until a candidate achieves a majority, or until a tie-breaking rule is applied.

#### Tie-Breaking Rules:

In case of a tie between two or more candidates during the recount, tie-breaking rules may be applied.
Common tie-breaking rules include looking at the number of first-preference votes, and if still tied, considering other factors like random selection or predetermined criteria.
Elimination of Candidates:

#### Eliminated candidates are no longer eligible to receive votes.

Once a candidate is eliminated, their votes are transferred to the next preferred candidate on each ballot.

#### Print Winner:

Once a candidate achieves a majority, they are declared the winner, and the election process concludes.
If a tie is declared, all tied candidates may be declared winners.

#### Handling Invalid Votes:

The system may include checks to ensure that votes are valid, and any invalid votes are not counted.
An invalid vote could result from ranking the same candidate multiple times or ranking candidates outside the provided options.

