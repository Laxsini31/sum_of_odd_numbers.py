lst=list(map(int,input("Enter numbers: ").split()))
s=0
for i in lst:
    if i%2!=0:
        s+=i
print("Sum of odd numbers:",s)

Output

Enter numbers: 1 2 3 4 5 6
Sum of odd numbers: 9
