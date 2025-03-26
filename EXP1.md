# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 19.03.2025                                                                            
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
do…while:
```
def display():
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
while True:
start=int(start)
end=int(end)
print(start,end=‘ ‘)
if start<end:
start+=1
else:
break
else:
print("Enter a valid positive number.")display()
```
while…do
```
start=input("Enter a positive value for START: ")end=input("Enter
a positive value for END: ")
if start.isnumeric() and end.isnumeric():
start=int(start)
end=int(end)
while start<end:
print(start)
start+=1
else:
print("Enter a valid positive number.")
```
switch
```
def switch():
switcher={
0:"even",
1:"odd"
}
n=input('Enter a value for N: ') try:
n=int(n)
print(switcher[n%2])
except ValueError:
print("Enter a valid number.")
switch()
```


.) if else
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
print(“Enter a valid number.”)
```

for
```
def iterate():
string=input("Enter a string: ")for
i in string:
print(ord(i),end=" ")
```













### Output:
 ![Screenshot 2025-03-26 091403](https://github.com/user-attachments/assets/0d61f2ce-a99a-419d-8720-9e3b528476f1)
 ![Screenshot 2025-03-26 091330](https://github.com/user-attachments/assets/4c4bf30e-0076-4655-b1c8-2a2b6bdfbf45)
![Screenshot 2025-03-26 091310](https://github.com/user-attachments/assets/83a13f3c-b950-4a51-a34f-e3340d022778)
![Screenshot 2025-03-26 091241](https://github.com/user-attachments/assets/7abfd41b-dca7-4eda-8800-71b854bc3a8d)
![Screenshot 2025-03-26 091216](https://github.com/user-attachments/assets/98045c38-6205-478f-94ae-c0b500be99f2)








### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


