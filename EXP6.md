# Ex.No: 6 To check whether the string is Palindrome and generate test cases.
### DATE:17-09-2024                                                                       
### REGISTER NUMBER : 212222040121
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def Palindrome(string):
    for i in range(0, int(len(string) / 2)):
        if string[i] != string[len(string) - i - 1]:
            return False
    return True

s = input("Enter a string: ")
c = 1

for i in s:
    if not i.isalpha():
        c = 0
        break  # Exit the loop if a non-alpha character is found

if c == 0:
    print("Enter a valid string")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
    else:
        print("The given string is not a palindrome")
```
### Output:

![373508087-4d40e2fd-9d07-4020-a52a-2bdafc502ee5](https://github.com/user-attachments/assets/d2608f35-0d25-41be-beff-b0ad26940ba5)


### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
