# Rock-Paper-Scissors
##########################################################First approach
import random # import random module
user_guess=input("'r' for rock, 'p' for paper, 's' for scissors? ") #user guess
list_com=['r','p','s'] # list for computer guess
random_com=random.randint(0,2) # 0 and 2 includes in the interval
com_guess=list_com[random_com] # computer guess randomly
if user_guess==com_guess:
    print(f"equal, both of them are {user_guess}")
elif user_guess!=com_guess:
     if user_guess=='r' and com_guess=='p':
        print(f"winner is computer with {com_guess}")
     elif user_guess=='p' and com_guess=='r':
         print(f"winner is user, computer guess is {com_guess}")
     elif user_guess=='r' and com_guess=='s':
         print(f"winner is user, computer guess is {com_guess}")
     elif user_guess=='s' and com_guess=='r':
         print(f"winner is computer with {com_guess}")
     elif user_guess=='p' and com_guess=='s':
         print(f"winner is computer with {com_guess}")
     elif user_guess=='s' and com_guess=='p': 
         print(f"winner is user, computer guess is {com_guess}")
##########################################################Second approach
