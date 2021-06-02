# DICE ROLLING STIMULATOR

This mini-project involves writing a program that simulates rolling dice. When the program runs, it will randomly choose a number between 1 and 6. The program will print that number and ask you if you’d like to roll the dice again.

## ALGORITHM:
1. Develop a random number.
2. Check the number.
3. Print the Face.
4. Looping.

## CODE:
'''
import random
print("This is a dice stimulator")
x = "y"
while x == "y":
    number = random.randint(1,6)
    if number == 1:
        print("----------")
        print("|        |")
        print("|    O   |")
        print("|        |")
        print("----------")
    if number == 2:
        print("----------")
        print("|        |")
        print("| O    O |")
        print("|        |")
        print("----------")
    if number == 3:
        print("----------")
        print("|    O   |")
        print("|    O   |")
        print("|    O   |")
        print("----------")
    if number == 4:
        print("----------")
        print("| O    O |")
        print("|        |")
        print("| O    O |")
        print("----------")
    if number == 5:
        print("----------")
        print("| O    O |")
        print("|    O   |")
        print("| O    O |")
        print("----------")
    if number == 6:
        print("----------")
        print("| O    O |")
        print("| O    O |")
        print("| O    O |")
        print("----------")
    x = input("Press y to roll again ")
'''    
