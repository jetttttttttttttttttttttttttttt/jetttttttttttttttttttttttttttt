import random

def guess_the_number():
    print("Welcome to Guess the Number!")
    print("I've picked a number between 1 and 100. Try to guess it!")
    
    # Generate a random number between 1 and 100
    number_to_guess = random.randint(1, 100)
    attempts = 0
    
    while True:
        guess = int(input("Enter your guess: "))
        attempts += 1
        
        if guess < number_to_guess:
            print("Too low! Try again.")
        elif guess > number_to_guess:
            print("Too high! Try again.")
        else:
            print(f"Congratulations! You've guessed the number {number_to_guess} in {attempts} attempts!")
            break

if __name__ == "__main__":
    guess_the_number()
- 👋 Hi, I’m @jetttttttttttttttttttttttttttt
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jetttttttttttttttttttttttttttt/jetttttttttttttttttttttttttttt is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
