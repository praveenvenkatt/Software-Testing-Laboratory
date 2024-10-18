# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                      
### REGISTER NUMBER : 212222040095

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

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
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

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

### iv.) if else

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

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```
## Output:
![1](https://github.com/user-attachments/assets/d36709f3-f3f3-48f8-9e11-d65ade8f4f6c)
![2](https://github.com/user-attachments/assets/69e5b8a2-800f-40e5-9d6c-0786da687e31)
![3](https://github.com/user-attachments/assets/da60dae5-9272-4726-bf9f-6ead3a9d9afe)
![4](https://github.com/user-attachments/assets/d2aafe75-f498-4acb-b9a3-939d4c776d61)
![5](https://github.com/user-attachments/assets/08c2e992-2c72-49d3-b713-8859c20ec2bf)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
