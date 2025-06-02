# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(string):
    index = int(input())
    return string[:index] + string[index+1:]
user_string = input()
result = remove(user_string)
print(result)
```
## Output
![p9](https://github.com/user-attachments/assets/9f110a2e-9774-403b-bc54-7720f8f58fbd)

## Result
The program was executed successfully. It accepts a string and removes the character at the specified index, then outputs the modified string.
