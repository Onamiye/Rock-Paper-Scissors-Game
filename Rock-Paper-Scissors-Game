# Rock-Paper-Scissors
import random
choices = ["rock", "paper", "scissors"]   
You = input('Choose either "rock", "paper" or "scissors": ').lower()

choice = len(choices)-1      #creating a variable to store the endpoint index number
random_choice = random.randint(0, choice)     #making a random choice
computer = choices[random_choice]            #indexing with the random number generated



if You == "rock":
  print(f"You: {choices[0]}")
elif You == "paper":
  print(f"You: {choices[1]}")
elif You == "scissors":
  print(f"You: {choices[2]}")
else:
 print("wrong choice")

print(f"Computer: {computer}")


if You == "rock" and computer == "rock":
  print("No winner, play again")
elif You == "rock" and computer == "scissors":
  print("You Win!")
elif You == "rock" and computer == "paper":
  print("You lose, try again")
elif You == "scissors" and computer == "rock":
  print("You lose, try again")
elif You == "scissors" and computer == "scissors":
  print("No winner, play again")
elif You == "scissors" and computer == "paper":
  print("You win!")
if You == "paper" and computer == "rock":
  print("You win!")
elif You == "paper" and computer == "scissors":
  print("You lose, try again")
elif You == "paper" and computer == "paper":
  print("No winner, try again")
