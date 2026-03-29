# for-loop-problems.pyth
1 Sum of numbers — Find the sum of all numbers from 1 to N
N=int(input("enter the nth number: "))

total=0
for i in range(1,N+1):
    total=total+i
    
print("sum is:",total)

2 Multiplication table — Print the multiplication table of a given number.
for i in range(1,11):
    for j in range(1,11):
        print(i,"x",j,"=",i*j)
------------------------------------------------------------------------------------------------------------
3 Count vowels — Count the number of vowels in a given string.
string=input("word: ")
count=0
for word in string:
    if word in "aeiouAEIOU":
        count +=1
        
print(" the count ovels in the word:",count)
 
