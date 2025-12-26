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
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)
```

## Output
<img width="848" height="171" alt="Screenshot 2025-12-26 211225" src="https://github.com/user-attachments/assets/f84beca9-f565-45aa-949e-ded80140fa8c" />

## Result
Thus the program has been executed successfully
