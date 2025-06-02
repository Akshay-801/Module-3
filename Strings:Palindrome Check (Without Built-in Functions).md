# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
n=input()
m=n
a=n[::-1]
if(m==a):
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output
![p10](https://github.com/user-attachments/assets/933db23e-9932-4d19-802a-2f596c8b3d76)

## Result
The program was executed successfully. It checks whether the string "google" is a palindrome or not without using any built-in palindrome checking functions, by manually comparing characters.
