# Question 1:
###   Write a python program to input an alphabet and check whether it is
### vowel or consonant. 
###    Note: Vowel alphabets are: {a, e, o, u, i}
   ### All other alphabets are consonant
``` python
vowel = {'a','e','o','u','i'}
a = input("write letter")
print(f'char {a} is vowel') if a.lower() in vowel else print(f'char "{a}" is not vowel')
```
# Question 2:
### Write a python program that prompts the user to input a number. The
### program should then output this number and a message saying whether
### it is even or odd
``` python
n = int(input("enter number :"))
print(f"number {n} in even") if n%2 == 0 else print(f"number {n} in odd")
```
# Question 3:
### Write a python program to input a character from user and check whether
### the given character is alphabet, digit or special character
``` python
n = input("enter character :")
if n.isdigit(): print(f"'{n}' is digit")
elif n.isalpha(): print(f"'{n}' is alphabet")
else : print(f"'{n}' is special character")
```
# Question 4:
###    Write a python program that prompts the user to input a number. The
### program should then output this number and a message saying whether it
###    is positive, negative, or zero
``` python
n = int(input("Enter number : "))
if n > 0 : print("Number is Postive")
elif n < 0 : print("Number is negative")
else: print("Number is zero")
```
# Question 5:
### Write a python program of a four-function calculator.
### The program should ask the user to enter a number, an operator, and another number.
###    It should then carry out the specified arithmetical operation: adding, subtracting,
###    multiplying, or dividing the two numbers.
``` python
def myfunc(num1 ,operation , num2):
    if operation == '+':
        print(f"{num1} {operation} {num2} = {num1 + num2}")
    elif operation == '-':
        print(f"{num1} {operation} {num2} = {num1 - num2}")
    elif operation == '*':
        print(f"{num1} {operation} {num2} = {num1 * num2}")
    elif operation == '/':
        print(f"{num1} {operation} {num2} = {num1 / num2}")
    else :
        print("Error no operation")
        
n1 = int(input("Enter frist number : "))
op = input("operation : ")
n2 = int(input("Enter second number : "))
myfunc(n1 , op , n2)
```
# Question 6:
### Write a python program that will prompt the user to input 5 integer values
### to be stored in a list.
``` python
l = []
for x in range(5):
    l.append(int(input("Enter Number :")))

print(l)
```
# Question 7:
### Write a python program that print the values of a list.
``` python
l = ["python", "java" , "C++" , "PHP"]

for x in l:
    print(x)
```
# Question 8:
### Write a python program that print the values of a list in a reverse order
``` python
l = [1,2,3,4,5]
for x in l[::-1]:
    print(x)
```
# Question 9:
### Write a python program that will prompt the user to input a list of 5
### integer values. Then it print their summation and average.
``` python
l = []
for x in range(5):
    l.append(int(input("Enter Number : ")))

print(f"list : {l}")
print(f"summation is : {sum(l)}")
print(f"average is : {sum(l)/5}")
```
# Question 10:
###  Write a python program that will prompt the user to input a list of 5
###    integer values. Then it print the summation and average of its contained
### even numbers.
``` python
l = []
for x in range(5):
    num = int(input("Enter Number : ")) 
    if num%2 == 0 : 
        l.append(num)

print(f"summation is : {sum(l)}")
print(f"average is : {sum(l)/len(l)}")
```
# Question 11:
### Write a python program that will prompt the user to input a list of 5
### integer values. Then it print its maximum and minimum values.
``` python
l = []
for x in range(5):
    l.append(int(input("Enter Number : ")))

print(f"maximum : {max(l)}" )
print(f"minimum : {min(l)}")
```
# Question 12:
###    Write a python program that will prompt the user to input a list of 5
   ### integer values. Then it ask the user to enter a number to check whether or
   ### not this number is found in the list or not.
``` python
l = []
for x in range(5):
    l.append(int(input("Enter Number : ")))

n = int(input("enter number to check :"))
if n in l :
    print("the number is in the list")
else :
    print("the number not is in the list")
```
# Question 13:
### Write a python program that will prompt the user to input an index of a list to print its value.
lang = ["python", "java" , "C++" , "PHP"]

x = int(input("Enter index : "))

print(lang[x])
# Question 14:
### Write a python program that will prompt the user to input a list of 5
### integer values. Then it count the number of occurrence of the given
### number in such list
``` python
l = []
for x in range(5):
    l.append(int(input("Enter Number : ")))

for x in set(l):
    print(f"{x} : {l.count(x)}")
```
# Question 15:
### Write a python program that merge two lists.
``` python
lang1 = ["python", "java" ]
lang2 = [ "C++" , "PHP"]
lang3 = lang1 + lang2
print(lang3)
```
# Question 16:
### Write a python program that will prompt the user to input a list of 5
### integer values. Then it splits the list into two lists; the first will contains
### even numbers while the other will contain odd numbers
``` python
l = []
odd = []
even = []

for x in range(5):
    num = int(input("Enter Number : "))
    if num %2 :
        even.append(num)
    else :
        odd.append(num)

print(f"even {even}" )
print(f"odd {odd}" )
```
# Question 17:
### Write a python program that asks the user to enter an integer number then it prints its factorial
### Note: factorial(n) = n*(n-1)*(n-2)*(n-3)*(n-4).......*3*2*1
``` python
num = int(input("enter Number : "))
x = 1 
n = num
while n > 0 :
    x *= n
    n -= 1 
else :
    print(f"factorial of {num} is {x}")
```
# Question 18:
### Write a python program that asks the user to enter two integer numbers, a
### and b, then it prints a power b
### Note: a power b= a *a *a .... ( b times)
``` python
a = int(input("Enter Number : "))
b = int(input("Enter Power : "))

## solution 1
z = 1
for x in range(b):
    z *= a

print(z)

## solution 2
print(a**b)
```


