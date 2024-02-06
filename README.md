# Python-Password-Generator

This Python program is a simple password generator. Here's a detailed explanation of how it works:

1. User Input:

The program prompts the user to input two pieces of information:
The number of passwords they want to generate (no_of_passwords).
The length of each password (password_len).

2. String Constants:

The program imports the string module, which provides a collection of string constants.
Three string constants are used:
string.ascii_letters: Contains all ASCII letters (both uppercase and lowercase).
string.digits: Contains all digits.
string.punctuation: Contains all punctuation characters.

3. Selection List:

The program concatenates the three string constants (letter, digit, and special_char) to create selection_list. This list contains all possible characters that can be used to generate passwords.

4. Password Generation:

The program uses nested loops to generate the specified number of passwords (no_of_passwords) of the specified length (password_len).
The outer loop (for i in range(no_of_passwords)) iterates over the number of passwords to generate.
The inner loop (for j in range(password_len)) iterates over the length of each password.
Inside the inner loop, the program randomly selects a character from selection_list using secrets.choice() and appends it to the password string.

5. Output:

Each generated password is printed on a new line.
