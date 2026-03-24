# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if line and line[0] != 'T':
            count += 1
print("Count:", count)
```
## Result
<img width="383" height="171" alt="Screenshot 2026-03-24 082116" src="https://github.com/user-attachments/assets/b740a9e2-e216-4cff-824b-dec05b6b8c5f" />

## Result
Thus, the Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is executed successfully.
