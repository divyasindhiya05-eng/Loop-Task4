# Loop-Task4
# TASK 4: Loops & Iterations

# 1. for loop: print numbers 1 to 100
print("Numbers from 1 to 100:")
for i in range(1, 101):
    print(i, end=" ")
print("\n")

# 2. while loop: countdown timer
print("Countdown:")
count = 10
while count > 0:
    print(count)
    count -= 1
print("Time Up!\n")

# 3. break and continue example
print("Break & Continue Example:")
for i in range(1, 11):
    if i == 5:
        continue  # skip 5
    if i == 8:
        break     # stop loop at 8
    print(i)
print()

# 4. Iterate over string characters
name = "Python"
print("Characters in string:")
for ch in name:
    print(ch)
print()

# 5. Multiplication table
num = 5
print(f"Multiplication Table of {num}:")
for i in range(1, 11):
    print(f"{num} x {i} = {num*i}")
print()

# 6. range with steps
print("Numbers with step of 2:")
for i in range(0, 21, 2):
    print(i, end=" ")
print("\n")

# 7. Loop with condition
print("Even numbers between 1 to 20:")
for i in range(1, 21):
    if i % 2 == 0:
        print(i, end=" ")
print("\n")

# 8. Real-world example
print("Real-world example: Checking attendance")
students = ["Aman", "Riya", "Neha", "Rahul"]
for student in students:
    print(f"{student} is present")

    
  *OUTPUT:-  
PS D:\python task4> python loop.py
Numbers from 1 to 100:
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99 100 

Countdown:
10
9
8
7
6
5
4
3
2
1
Time Up!

Break & Continue Example:
1
2
3
4
6
7
Characters in string:
P
y
t
h
o
n

Multiplication Table of 5:
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

Numbers with step of 2:
0 2 4 6 8 10 12 14 16 18 20
Even numbers between 1 to 20:
2 4 6 8 10 12 14 16 18 20

Real-world example: Checking attendance
Aman is present
Riya is present
Neha is present
Rahul is present
# Task 4 - Loops & Iterations (Python Developer Internship)

## 📌 Overview
This task is part of the Python Developer Internship.  
The objective of this task is to understand and implement loops and iterations in Python.

---

## 🛠 Tools Used
- Python
- VS Code

---

## 📂 Files Included
- `loop_tasks.py` – Python script demonstrating different types of loops
- `README.md` – Task explanation and instructions

---

## ✅ Concepts Covered
- for loop
- while loop
- break and continue statements
- Iterating over strings
- Multiplication table
- range() function with steps
- Loop with conditions
- Real-world loop examples

---

## ▶️ How to Run the Code
1. Open terminal in the project folder
2. Run the following command:

```bash
python loop_tasks.py

