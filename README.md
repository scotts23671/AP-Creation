print("Hello! Welcome to Math Practice!")
choice = str(input("What do you want to practice? Addition, substraction, multiplication or divsion?"))
#IJUSTOUTEVERYTHINGTHERE
def hardAddition():
    import random
    a = random.randint(10,101)
    b = random.randint(10,101)
    answer = a+b
    studentAnswer = str(input("what is "+ str(a)+"+"+str(b)+"?"))
    if studentAnswer != str(answer):
        print("oops! That's wrong. The right answer is "+ str(answer))
    else:
        print("That's right! "+str(answer)+ " is the right answer.")
    
import random
print("Hello! Welcome to Math Practice!")
choice = str(input("What do you want to practice? Addition, substraction, multiplication or divsion?"))
while choice == "addition":
    print("Let's add!")
    choice2 = str(input("Would you like easy or hard addition?"))
    if choice2 == "hard":
        hardAddition()
    elif choice2 == "easy":
        a = random.randint(1,11)
        b = random.randint(1,11)
        answer = a+b
        studentAnswer = str(input("what is "+ str(a)+"+"+str(b)+"?"))
        if studentAnswer != str(answer):
            print("oops! That's wrong. The right answer is "+ str(answer))
        else:
            print("That's right! "+str(answer)+ " is the right answer.")
    else:
        break
