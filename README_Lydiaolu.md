/ 1. Setup Phase
SET SECRET_NUMBER to a random integer between 1 and 10 (inclusive)
SET GUESS_CORRECT to FALSE

// 2. Game Loop (Repetition Control)
WHILE GUESS_CORRECT is FALSE:
    // A. Input Phase
    DISPLAY "Guess the secret number between 1 and 10: "
    READ USER_GUESS

    // B. Decision Control Phase
    IF USER_GUESS is equal to SECRET_NUMBER:
        // Correct Guess
        DISPLAY "🎉 Congratulations! You guessed the correct number: " + SECRET_NUMBER + "!"
        SET GUESS_CORRECT to TRUE // Exit condition for the loop
    ELSE IF USER_GUESS is less than SECRET_NUMBER:
        // Guess is Too Low
        DISPLAY "Too low! Try again."
    ELSE (meaning USER_GUESS is greater than SECRET_NUMBER):
        // Guess is Too High
        DISPLAY "Too high! Try again."

// 3. End of Program-