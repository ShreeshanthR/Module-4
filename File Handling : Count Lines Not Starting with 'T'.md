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
with open('story.txt', 'r') as file:
    count = 0 
    for line in file:
        if not line.lstrip().startswith('T'):
            count += 1  

print("Number of lines not starting with 'T':", count)
```

## Output
<img width="637" height="58" alt="image" src="https://github.com/user-attachments/assets/8e17e7bb-b7b5-4c4c-82cb-cc96061ec1ee" />

## Result
Thus, the Python program that counts and displays the number of lines in a file that do not start with the letter 'T' has been successfully created and executed.
