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
string = "google"
rev = string[::-1]

if string == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")


```

## Output
![alt text](<Screenshot 2025-10-22 155603.png>)


## Result
The program correctly identifies that "google" is not a palindrome.
