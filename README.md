# guessing-game
import random
num = random.randint(1,100)
guess =none
while guess != num:
	guess = input("choose a number between 1 to 100")
	guess = int(guess)
	if num < guess:
		print('the guess is higher then the number')
	elif num > guess:
		print('the guess is smaller then the number')
print('you are right')
