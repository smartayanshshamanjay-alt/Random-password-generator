# Random Password Generator

## About

I made this project using Python to generate random passwords.

In this project, the user enters the password length and the program creates a password using lowercase letters, uppercase letters, numbers and special characters.

I also added some input checking so that the program does not accept an invalid password length.

## What this project can do

- Ask the user for password length
- Check if the entered value is valid
- Add lowercase and uppercase letters
- Add numbers and special characters
- Generate a random password
- Shuffle the characters before showing the password

## How I made it

I used Python and the `string` and `random` modules.

First, the program takes the password length. Then it selects one character from each required category. The remaining characters are selected randomly. At the end, all the characters are shuffled and the password is printed.

## Running the project

You just need Python installed on your computer.

Run the Python file and enter the password length when the program asks for it.

For example:

Enter your password length: 8
Your password is:
xP4@kL9!
