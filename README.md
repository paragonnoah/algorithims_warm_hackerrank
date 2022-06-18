# algorithims_warm_hackerrank
hackerrank data structure and algorithm fast work
Given an array of integers, find the sum of its elements.
for example

if the array, arr = [1, 2, 3], 1+2+3 so return 6

function discription
_Complete the simpleArraySum function in the editor below. It must return the sum of the array elements as an integer.

simpleArraySum has the following parameter(s):

ar: an array of integers

input format
The first line contains an integer,n , denoting the size of the array.
The second line contains space-separated integers representing the array's element
_

solutions
// bin/python3
import math
import os
import random
import re
import sys

we define a function to return an interger
def simpleArraySum(ar):
# Write your code here
x=0
for i in range(0,ar_count):
x += ar[i]
return x
if name == 'main':
fptr = open(os.environ['OUTPUT_PATH'], 'w')

ar_count = int(input().strip())

ar = list(map(int, input().rstrip().split()))

result = simpleArraySum(ar)

fptr.write(str(result) + '\n')

fptr.close()
