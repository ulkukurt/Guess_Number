# Guess_Number_Mix
Introduction
For your final assessment, please make the following enhancements to the Higher-Lower game from the
JavaScript exercises. You may start with the Higher-Lower solution or utilize your own solution to the
practice exercise.
1. Prompt for Max Number
Instead of locking the game into a number between 1 and 20, use the prompt() method to ask the user
what the maximum number should be. The prompt should be in a loop with validation as demonstrated
previously in the course making sure that the inputted value is a positive number. If the user inputs a
decimal, simply round it.
When a valid number is inputted, change the content of the instructions to specify guesses between 1
and N (where N is the user-provided maximum number).
Grading Criteria
Requirements:
• The application prompts the user for a maximum number.
• The application validates the user input and does not allow invalid entries (negative numbers, 0,
or non-numbers), re-prompting the user if an invalid entry is provided.
• If the user provides a decimal number, the application rounds it.
• The application selects a random number between 1 and N (where N is the user-provided
maximum number).
Points:
• 2 points will be given if all the requirements are implemented.
• 1 point if one requirement was missed.
• 0 points if two or more requirements were missed.
