# Simple-Quiz-Game.py
This is a simple command-line Quiz Game built using Python

print("---Welcome to the  Quiz Game---")
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
print(" 1. Programing Language\n","2. Snake\n","3. Car Brand\n","4.Operating System\n")

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

