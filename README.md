# FLAME-Project_Step-1
FLAMES is a popular game named after the acronym: Friends, Lovers, Affectionate, Marriage, Enemies, Sibling. This game does not accurately predict whether or not an individual is right for you, but it can be fun to play this with your friends.

Python is a multipurpose language and one can do literally anything with it. Python can also be used for game development. Let’s create a simple FLAMES game without using any external game libraries like PyGame.

There are two steps in this game:
Take the two names.
Remove the common characters with their respective common occurrences.
Get the count of the characters that are left.
Take FLAMES letters as [“F”, “L”, “A”, “M”, “E”, “S”]
Start removing letters using the count we got.
The letter which lasts the process is the result.

Example : 

Input :   player1 name : AJAY

          player 2 names: PRIYA

Output: Relationship status: Friends

Explanation: In the above given, two names A and Y are common letters that are occurring one time(common count) in both names, so we are removing these letters from both names. Now count the total letters that are left here it is 5. Now start removing letters one by one from FLAMES using the count we got and the letter which lasts the process is the result.

Counting is done in an anti-clockwise circular fashion.

FLAMES 

Counting starts from F, E is at 5th count so we remove E and start counting again but this time starts, but from S. 

FLAMS 

M is at 5th count so we remove M and counting starts from S. 

FLAS 

S is at 5th count so we remove S and counting starts from F. 

FLA 

L is at 5th count so we remove L and counting starts from A. 

FA 

A is at 5th count so we remove A. now we have only one letter is remaining so this is the final answer. 

F 

So, the relationship is F i.e. Friends.
