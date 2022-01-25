# VotingRules
Voting Rules Algorithm implementation in Python

Let us consider an election with n voters (0 ≤ n ≤ 100) and m candidates (0 ≤ m ≤ 5). We assume that :
• The preferences of each voter are given as a linear order on the set of candidates
• All the preferences (of the n voters) are contained in an Excel file or a csv file.
This work aims at computing in python language the four voting rules introduced in Chapter 3. You can use the examples of this
chapter to test your functionalities, especially the following example where m = 4 candidates {a, b, c, d} and n = 27 :

###### 5 voters : a > b > c > d
###### 4 voters : a > c > b > d
###### 2 voters : d > b > a > c
###### 6 voters : d > b > c > a
###### 8 voters : c > b > a > d
###### 2 voters : d > c > b > a
```
1. Compute a function MajorityRule returning the result of a simple majority rule voting, between two candidates.
2. Compute a function Plurality returning the result of a plurality voting.
3. Compute a function PluralityRunoff returning the result of a plurality Runoff voting (plurality with two rounds).
4. Compute a function CondorcetVoting returning the result of the application of the Condorcet principle (the existence of the
Condorcet winner).
5. Compute a function BordaVoting returning the result of the application of the Borda principle.
```
