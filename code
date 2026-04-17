import random
level = input("1-Easy, 2-Normal, 3-Hard")
if level == "Easy":
    start , end = 1,10
elif level == "Normal":
    start , end = 10,100
else:
    start , end = 100,1000
number = random.randint(start, end)
attempts = 10
while attempts > 0:
    you = int(input("Your Number: "))
    if you == number:
        print("You Won!")
        break
    elif you > number:
        print("your num very big")
    else:
        print("your num very small")
    attempts -= 1
    print("Your attempts:", attempts)
    if attempts == 0:
        print("You Lose!")
    stop = input("Do you want to continue? (yes/no):")
    if stop == "n":
        break
