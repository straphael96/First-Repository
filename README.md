# First-Repository
For those interested, see my development and progression into the world of coding

Here is a little code I created the other day:

import random
maximum=6
minimum=1

roll_again="yes"

roll_again=raw_input("Roll the Dice?")

while roll_again =="yes" or roll_again =="y":
	print "Rolling Dice..."
	print "The Dice Reads..."
	print random.randint(minimum,maximum)

	roll_again=raw_input("Roll The Dice Again?")
