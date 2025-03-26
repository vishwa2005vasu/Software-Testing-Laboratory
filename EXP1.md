# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 19.03.20205                                                                         
### REGISTER NUMBER : 212222040183

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
do while
```
def display():
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
while True:
start=int(start)
end=int(end)
print(start,end=' ')
if start<end:
start+=1
else:
break
else:
print("Enter a valid positive number.")
display()
```
while do
```
def display():
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
while True:
start=int(start)
end=int(end)
print(start,end=' ')
if start<end:
start+=1
else:
break
else:
print("Enter a valid positive number.")
display()
```
switch
```
def switch():
switcher={0:"even",1:"odd"}
n=input('Enter a value for N: ')
try:
n=int(n)
print(switcher[n%2])
except ValueError:
print("Enter a valid number.")
switch()
```
.if else:
```
def compare():
a=input("Enter a value for A: ")
b=input("Enter a value for B: ")
try:
a=int(a)
b=int(b)
if a>b:
print("A is greater than")
elif a<b:
print("B is greater than")
else:
print("A is equal to B")
except ValueError:
print("Enter a valid number.")
compare()
```
for
```
def iterate():
string=input("Enter a string: ")
for i in string:
print(ord(i),end=" ")
iterate()
```














### Output:



![Screenshot 2025-03-26 091403](https://github.com/user-attachments/assets/ca5c5432-7362-4f5d-8802-4890900d0a10)

![Screenshot 2025-03-26 091330](https://github.com/user-attachments/assets/e7de07a3-6fa6-4283-89cf-6b290819785e)

![Screenshot 2025-03-26 091310](https://github.com/user-attachments/assets/94255f9f-6c9e-4bee-918c-e1bacdaa0fa5)

![Screenshot 2025-03-26 091241](https://github.com/user-attachments/assets/9ba859b4-fa3d-4ece-a6a2-f7765f8f14f8)

![Screenshot 2025-03-26 091216](https://github.com/user-attachments/assets/a9eb8ef0-d270-41f9-ae27-16c700841f3f)





### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


