# number-guess-game
This algorithm uses a loop to allow for multiple guesses and decision control (if/else statements) to provide feedback.
# 🔢 Simple Number Guessing Game

## Project Details
* **Project Title:** Simple Number Guessing Game Algorithm
* **Project Author:** [lydiadeolu]
* **Peer Reviewer:** [Partner's Name]

// 1. Setup Phase
SET SECRET_NUMBER to a random integer between 1 and 10 (inclusive)
SET GUESS_CORRECT to FALSE

// 2. Game Loop (Repetition Control)
WHILE GUESS_CORRECT is FALSE:
    DISPLAY "Guess the secret number between 1 and 10: "
    READ USER_GUESS

    // B. Decision Control Phase
    IF USER_GUESS is equal to SECRET_NUMBER:
        DISPLAY "🎉 Congratulations! You guessed the correct number!"
        SET GUESS_CORRECT to TRUE
    ELSE IF USER_GUESS is less than SECRET_NUMBER:
        DISPLAY "Too low! Try again."
    ELSE:
        DISPLAY "Too high! Try again."

// 3. End of Program
END
