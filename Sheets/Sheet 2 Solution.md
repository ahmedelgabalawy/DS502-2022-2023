# convert the following if=else statment to their equivalent short hand if else 

## Question 1:

```python
a = 500
b = 300
if a == b:
    print('a=b')
elif a> 50 :
    print('a>50 & a!=b')
else:
    print('a<=50 & a!=b')
```
``` python
a = 500
b = 300
print('a=b') if a == b else  print('a>50 & a!=b') if a> 50 else print('a<=50 & a!=b')
```

## Question 2:
``` python
i = 10 
if i < 15:
    print("i is less than 15") 
```
#### solution -1 
``` python
i = 10 
print("i is less than 15") if i < 15 else print("i is'not less than 15") 
```
#### solution -2
``` python
i = 10 
if i < 15 : print("i is less than 15") 
```
## Question 3:
``` python
i = 10 
if i < 15 :
    print(True)
else: 
    print(False) 
```
#### solution
``` python
i = 10 
print(True) if i < 15 else print(False) 
```
_____
# Convert the following loops to its list comprehension form:
## Question 4:
``` python
x= [1,2,3,5,6]
y= []
for i in range(len(x)):
    y.append(x[i])

    y[i:]=[]
print(y)
```
#### solution
``` python
x= [1,2,3,5,6]
y= []
y = [x[i] for i in range(len(x))]
print(y)
```
## Question 5:
``` python 
x= [1,2,3,5,6]
y= ['a','b','c','d','e']
z = []
for i in range(len(x)):
    for j in range(len(y)):
        if i == j :
            z[i:] = [(x[i],y[j])]
print(z)
```
#### solution
``` python 
x= [1,2,3,5,6]
y= ['a','b','c','d','e']

z = [(x[i],y[j]) for i in range(len(x)) for j in range(len(y)) if i == j ]

print(z)
```

## Question 6:
``` python 
x = [1, 2, 3, 5, 6]
y = ['a', 'b', 'c', 'd', 'e']
z = []
k = 0

for i in range(len(x)):
    for j in range(len(y)):
        if i == j :
            z[k:]=[(x[i],y[j])]
        else:
            z[k:]=[(y[j],x[i])]
        k=k+1
print(z)
```
#### solution
``` python 
x = [1, 2, 3, 5, 6]
y = ['a', 'b', 'c', 'd', 'e']
k = 0

z = [ (x[i],y[j]) if i == j else (y[j],x[i]) for i in range(len(x)) for j in range(len(y)) ]

print(z)
```
## Question 7:
``` python 
x = [1, 2, 3, 5, 6]
y = ['a', 'b', 'c', 'd', 'e']
z = []
k = 0

for i in range(len(x)):
    for j in range(len(y)):
        if i == j :
            z[k:]=[(x[i],y[j])]
        elif i == 2 :
            z[k:]= [(2,2)]
        else:
            z[k:]=[(y[j],x[i])]
        k=k+1
print(z)
```
#### solution
``` python 
x = [1, 2, 3, 5, 6]
y = ['a', 'b', 'c', 'd', 'e']
z = []
k = 0

z = [(x[i],y[j]) if i == j else (2,2) if i == 2 else (y[j],x[i]) for i in range(len(x)) for j in range(len(y))]

print(z)
```
## Question 8:
``` python 
x = [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12]]
y = []

for i in range(len(x)):
    z = []
    for j in range(len(x[i])):
        z[j:] = [x[i][j]]
    y[i:] = [z]

print(y)
```
#### solution
``` python 
x = [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12]]
y = [[x[i][j] for j in range(len(x[i]))] for i in range(len(x)) ]
print(y)
```
# what is the output of the following :
## Question 9:
``` python 
x = [1, 2, 3, 5, 6]
y = [x[i] for i in range(len(x))]
print(y)

# output : [1, 2, 3, 5, 6]
```
## Question 10:
``` python 
x= [1,2,3,5,6]
y= ['a','b','c','d','e']

z = [(x[i],y[j]) for i in range(len(x)) for j in range(len(y)) if i == j ]

print(z)

# output : [(1, 'a'), (2, 'b'), (3, 'c'), (5, 'd'), (6, 'e')]
```
