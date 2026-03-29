# for-loop-problems.pyth
1 Sum of numbers — Find the sum of all numbers from 1 to N
N=int(input("enter the nth number: "))

total=0
for i in range(1,N+1):
    total=total+i
    
print("sum is:",total)

