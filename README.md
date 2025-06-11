# Password-Genarator
A simple Python script that generates secure, customizable passwords based on user preferences.

Features
Choose password length.

Include or exclude uppercase letters.

Include or exclude lowercase letters.

Include or exclude digits.

Include or exclude special characters.

Ensures at least one character type is selected.

How It Works
The program prompts you to specify password criteria and then generates a random password matching those criteria.

Usage
Run the script.

Enter the desired password length.

Choose whether to include uppercase letters, lowercase letters, digits, and special characters by typing y (yes) or n (no).

Receive your generated password instantly.

Example
pgsql
Copy
Edit
Welcome to the Password Generator!
Enter desired password length: 12
Include uppercase letters? (y/n): y
Include lowercase letters? (y/n): y
Include numbers? (y/n): y
Include special characters? (y/n): n

Generated password: Ab7XqLp9TvDz
Requirements
Python 3.x

How to Run
Clone the repository and run the Python script:

bash
Copy
Edit
python password_generator.py
Replace password_generator.py with the filename if different.

Error Handling
If no character types are selected, the program will display an error:

sql
Copy
Edit
Error: At least one character type must be selected
