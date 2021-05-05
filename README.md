ans1
GEEKS HAPPINESS 
Given an array nums of n integers. Delete a subsequence of length k (where k = n/3)  from the array. Let's call the array B after deleting the subsequence. Now Geek will be happy if the array B can be divided into 2 subarray of equal length such that difference between sum of elements of first subarray and sum of elements of second subarray is minimum possible. Geek asked you to make him happy.
Note: It is guaranted that n is divisible by 3.








ans 2.
MAX SCORE
N boxes are arranged in a straight line on a table. Each box has an integer label on it and also contains an integer value inside it. You are also given two integers cost1 and cost2. The score of a sequence of boxes is calculated as follows: 
1.    If there are no boxes on the table, then the score is 0. Otherwise, the initial score is the product of cost1 and the integer contained inside the first box from left. 
2.    For every box left on the table(traverse from left to right) except the first box from the left, we add 

a.    The product of cost1 and the integer inside the current box to the score, if the labels on the current box and the box present to its left are different.
b.    The product of cost2 and the integer inside the current box to the score, if the labels on the current box and the box present to its left are the same.

Geek wants to remove some boxes (possibly Zero or all) so that the score is maximum possible.
