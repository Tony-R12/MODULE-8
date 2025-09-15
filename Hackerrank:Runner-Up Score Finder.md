# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```
l1=[]
l2=[]
for _ in range(int(input())):
 name = input()
 score = float(input())
 l1.extend([name,score])
 l2.append(l1)
 l1=[]
l3=[]
l4=[]
for i in l2:
 l3.append(i[1])
l3.sort()
for i in l2:
 if i[1]==l3[1]:
 l4.append(i[0])
l4.sort()
for i in l4:
 print(i)
```

## OUTPUT
<img width="458" height="466" alt="image" src="https://github.com/user-attachments/assets/7e5e20b5-3aad-4f46-b59f-7ac86c590a4f" />


## RESULT
Thus,the program is successfully created.
