import random

name = input("Howdy, What is your name? ")

def intro_greeting():
    global random_number 
    random_number = random.randint(1, 9)
    global question 
    question = input("What is your question for the all-knowing 8-Ball? ")
    print(random_number)

# answer = str("")

def eight_ball_replies():
    intro_greeting()
    if random_number == 1:
        answer = "For sure."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 2:
        answer = "Yeah, I guess."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 3:
        answer = "Indubatibly."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 4:
        answer = "I dunno boss, try again."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 5:
        answer = "Try it later."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 6:
        answer = "It's better I not tell you."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 7:
        answer = "Imma say no."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 8:
        answer = "Not lookin good boss man."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    elif random_number == 9:
        answer = "Not gonna happen."
        print(name +" asks: "  + question)
        print("Magic 8-Ball's answer: " + answer)
    else:
        answer = "Error"

eight_ball_replies()
# print(answer)
# print(name +" asks: "+ question)

# print("Magic 8-Ball's answer: " + answer)

# run_again = print("Do you want to run again?")

def play_again():
    run_again = input("Do you want to run again? y/n: ")
    if run_again == "y":
        eight_ball_replies()
        play_again()
    else:
        print("Thanks for playing.")

play_again()


# while run_again():
#     # main program
#     while True:
#         answer = str(input('Run again? (y/n): '))
#         if answer in ('y', 'n'):
#             break
#         print("invalid input.")
#     if answer == 'y':
#         continue
#     else:
#         print("Goodbye")
#         break
# run_again()
