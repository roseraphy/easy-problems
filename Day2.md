```python
#6 Calculate Simple Interest
P=int(input("Enter Principal amount:"))
R=float(input("Enter annual interest rate:"))
T=int(input("Enter time(years):"))
SI= (P*R*T)/100
print("Simple Interest:",SI)
```

    Enter Principal amount: 5000
    Enter annual interest rate: 2.1
    Enter time(years): 3
    

    Simple Interest: 315.0
    


```python
#7 Check if a number is positive, negative or zero
T=int(input("Enter test cases:"))
for i in range(T):
    x=float(input("Enter a number"))
    if x>0:
        print("Positive number")
    elif x==0:
        print("The number is 0")
    else:
        print("Negative number")
```

    Enter test cases: 3
    Enter a number 3
    

    Positive number
    

    Enter a number 0
    

    The number is 0
    

    Enter a number -5
    

    Negative number
    


```python
#8 Find the remainder when one number is divided by another
a=int(input("Enter a number:"))
b=int(input("Enter another number:"))
print("Remainder when",a,"is divided by",b,"is",a%b)
```

    Enter a number: 5
    Enter another number: 3
    

    Remainder when 5 is divided by 3 is 2
    


```python
#9 Swap two variables
a=int(input("Enter a number:"))
b=int(input("Enter another number:"))
print("Before swapping: a=",a,"b=",b)
x=a
a=b
b=x
print("After swapping: a=",a,"b=",b)
```

    Enter a number: 2
    Enter another number: 3
    

    Before swapping: a= 2 b= 3
    After swapping: a= 3 b= 2
    


```python
#10 Check if a number is even or odd
T=int(input("Enter a test cases:"))
for i in range(T):
    x=int(input("Enter a number"))
    if x%2==0:
        print("Even number")
    else:
        print("Odd number")
```

    Enter a test cases: 2
    Enter a number 2
    

    Even number
    

    Enter a number 3
    

    Odd number
    


```python

```
