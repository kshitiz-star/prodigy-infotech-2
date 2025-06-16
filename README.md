# Number guessing game
A number-guessing game in Java is a simple program where the computer randomly selects a number, and the user has to guess it within a limited number of attempts. The program provides feedback on whether the guessed number is too high or too low, guiding the user toward the correct answer.

# Rules of the Game:

* If the guessed number is bigger than the actual number, the program will respond with the message that the guessed number is higher than the actual number.
* If the guessed number is smaller than the actual number, the program will respond with the message that the guessed number is lower than the actual number.
* If the guessed number is equal to the actual number or if the K trials are exhausted, the program will end with a suitable message.
# Implementation Details
The program generates a random number between a predefined range (e.g., 1 to 100).
The user has limited attempts (K tries) to guess the number.
At each guess, the program provides a hint:
* If the guessed number is higher, it tells the user to guess lower.
* If the guessed number is lower, it tells the user to guess higher.
* If the user guesses correctly, they win.
* If all attempts are exhausted, the game reveals the correct number.
# Approach:

To implement the game, we need to follow the steps listed below:

* Generate a random number using the Math.random() method.
* Take user input using Scanner.
* Compare the guess with the random number and provide feedback.
* Limit the number of attempts using a loop.
* Handle edge cases (e.g., invalid inputs).
# Implementation 
![image alt](https://github.com/kshitiz-star/prodigy-infotech-2/blob/main/Screenshot%202025-06-14%20111312.png?raw=true)



