## Project Title ------Simple Quiz Game (Python CLI Based)-----

## Technologies Used
Python (Core programming language)
Command Line Interface (CLI) for interaction
Basic Python concepts:
print() for output
input() for user input
if-else conditions
Variables (score)

## How It Works
Program start hote hi welcome message print hota hai
4 questions ek-ek karke user ko dikhaye jaate hain
Har question ke liye:
User input deta hai (1/2/3/4)
Program correct answer check karta hai
Agar answer sahi hai → score +1
Galat hai → next question
End me final score display hota hai

## How to Run
Step 1: Python Install karein
Ensure Python installed hai:
python --version

Step 2: File Save karein
Code ko save karein:
Simple-Quiz-Game.py

Step 3: Run karein
Terminal ya CMD me:
python Simple-Quiz-Game.py

## Code
```
print("---Welcome to the Quiz Game---")
print("--------------------------------")

score = 0  
total_questions = 4

print("\n-Question A: India ka capital kya hai?")
print(" 1. Mumbai\n","2. Delhi\n","3. Kolkata\n","4.Uttar Pradesh\n")

answer = int(input("Enter your Answer(1/2/3/4) : "))
if answer == 2:
    print("---Sahi jawab---")
    score += 1
else:
    print("---Galat jawab---")

print("\n-Question B: Python kis type ka language hai?")
print(" 1. Programming Language\n","2. Snake\n","3. Car Brand\n","4. Operating System\n")

answer = int(input("Enter your Answer(1/2/3/4) : "))
if answer == 1:
    print("---Sahi jawab---")
    score += 1
else:
    print("---Galat jawab---")

print("\n-Question C: 56 + 23 kitna hota hai?")
print(" 1. 86\n","2. 97\n","3. 11\n","4. 79\n")

answer = int(input("Enter your Answer(1/2/3/4) : "))
if answer == 4:
    print("---Sahi jawab---")
    score += 1
else:
    print("---Galat jawab---")

print("\n-Question D: Ram Mandir UP ke kis jila me hai?")
print(" 1. Ayodhya\n","2. Mirzapur \n","3. Jaunpur\n","4. Varanasi\n")

answer = int(input("Enter your Answer(1/2/3/4) : "))
if answer == 1:
    print("---Sahi jawab---")
    score += 1
else:
    print("---Galat jawab---")

print("\n-----------------------------")
print(f" Quiz khatam! Aapka final score hai: {score}/4")
print("--------Thank you--------")
```
## Output
---Welcome to the Quiz Game---
--------------------------------
-Question A: India ka capital kya hai?
1. Mumbai  2. Delhi  3. Kolkata  4. Uttar Pradesh

Enter your Answer(1/2/3/4) : 2
---Sahi jawab---

-Question B: Python kis type ka language hai?
Enter your Answer(1/2/3/4) : 1
---Sahi jawab---

-----------------------------
Quiz khatam! Aapka final score hai: 3/4
--------Thank you--------

## Author
Ayush Singh
GitHub: https://github.com/ayush893singh
