# Ex.No: 07  Sorting

### DATE: 24-09-2024                                                                   
### REGISTER NUMBER : 212222040128

### AIM:  
Write a python program for sorting and inspect for failures

### Algorithm:
1. Start the program.
2. Get the number of elements from user
3. Get the elements to be sorted
4. Traverse the array and sort the elements one by one
5. Print the sorted array
6. Stop the program. 
### Program:
```
n=int(input("Enter the number of elements:"))
arr=[]
try:
 for i in range(n):
 a=float(input("Enter the element:"))
 arr.append(a)
 for i in range(n):
 for j in range(n):
 if(arr[i]<arr[j):
 temp = arr[i]
 arr[i] = arr[j]
 arr[j] = temp
 print(“The array after sorting: ”)
 for i in range(n):
 print(arr[i],end=’ ’)
except ValueError:
 print(“Enter a valid number”)
```
### Output:

![image](https://github.com/user-attachments/assets/3801cad7-9307-4307-8f87-5cf541118013)



### Result:
Thus, a program to check sorting has been written and test cases have been written and verified
successfully.
