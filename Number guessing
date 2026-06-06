import random
attempt=1

secret = random.randint(1,10)

guess = int(input("Enter your guess: "))

while guess != secret:
   if guess < 1 or guess > 10:
      print("Please enter a number between 1 to 10")
   elif guess < secret:
      print("Too low")
   else:
      print("Too high")

   guess = int(input("Enter your guess:"))
   attempt = attempt + 1

print("You win")
print("Attempt:", attempt)
