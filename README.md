# ass-2-17-02-22
#Write a program to print sum of n fibonacci numbers.
n=int(input('Enter the Fibonacci Number:'))
a=0
b=1
sum=0
for n in range(0, n):
    print(a, end = '  ')
    sum=sum+a
    c=a+b
    a=b
    b=c
print("\nThe Sum of Fibonacci Numbers=",sum)

output:
Enter the Fibonacci Number:8
0  1  1  2  3  5  8  13
The sum of Fibonacci Number=33
