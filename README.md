def say_hi(name):
    return "Hello,"+ name
Greeting = say_hi("Player")
print(Greeting)
choice=str(input("What do you want to practice? Addition, subtraction, multiplication, or division?"))
if choice == "multiplication":
    print("Let's get started with multiplication?")
    glossary={
    "5*4":"20",
    "6*4":"24",
    "7*4":"28",
    }

    for key,val in glossary.items():
        firstprob=key
        print(key)
        answer=input("What is the answer?")
        if answer == val:
            print("correct")
        else:
            print("You'll get it next time!")
elif choice == "division":
    print("Let's get started with division!")
    glossary={
        "20/4":"5",
        "24/6":"4",
        "28/4":"7",
        }
    for key,val in glossary.items():
        firstprob=key
        print(key)
        answer=input("What is the answer?")
        if answer == val:
            print("correct")
        else:
            print("Try again!")
