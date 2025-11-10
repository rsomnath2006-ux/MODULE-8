# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
```
n=int(input())
records={}
for _ in range(n):
    data=input().split()
    name,scores=data[0],list(map(float,data[1:]))
    records[name]=scores
query=input()
average=sum(records[query])/len(records[query])
print(f"{average:.2f}")
```
## OUTPUT
<img width="490" height="259" alt="image" src="https://github.com/user-attachments/assets/8c556832-a719-4bd3-8963-965e9635e1c0" />

## RESULT
Thus,the program is executed successfully
