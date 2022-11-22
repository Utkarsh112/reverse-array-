# reverse-array-
import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())

    arr = list(map(int, input().rstrip().split()))
for i in range(0,n-1):
    for j in range(n-1,0):
        temp=arr[j]
        arr[j]=arr[i]
        arr[i]=temp
        
print(arr)
