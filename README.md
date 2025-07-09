# GUESSING-GAME
A simple python guessing game made by me


secret_word = "chips"
guess = ""
print("What is deep fried,causes numerous healh problems but still loved by people?")
guess_count = 0
guess_limit = 4
out_of_guesses = False

while guess!= secret_word and not(out_of_guesses):
    if guess_count< guess_limit:
       guess= input("ENTER GUESS:")
       guess_count+=1
    else:
         out_of_guesses = True
if out_of_guesses:
                  print("Out of Guesses, you lose!")
else:
     print("You Win!")
