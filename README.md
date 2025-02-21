# Password Strength Checker

A simple Python script that generates a random password while including a user-supplied word or phrase. 
The script randomizes the case of the input word, adds random characters (letters, digits, symbols) to 
meet the desired length, and finally shuffles everything to avoid a predictable structure.

## What It Does

User Input: The user can supply any base word or phrase they want to see in the final password.

Randomized Case: Each character in the base word is randomly converted to uppercase or lowercase.

Extended Random Characters: The script pads the password with random letters, digits, and symbols up to a specified length.

Shuffle: The combined characters are shuffled.

## How to Run

1. Clone this repository or download `password_gen.py`. 
2. Ensure Python is installed, you will need 3.7 or higher.
3. In your terminal, run `python password_gen.py`.
4. Enter a word and length of password when prompted.

## Warnings and Limitations

- This tool is for educational purposes only and for my own fun.
- It does not comprehensively make secure or good passwords; it’s simple.
- Do not rely on it to make you a foolproof passport.

## Ethical Considerations

- This tool could be used to make extremely predictable passwords, for example if you know what word someone
  might use, and that they used this tool it can be used againts them.
- This too may let some users believe that it produces secure passwords, but this security isn't backed by anything
  beyond passwrod length and a few layers of randomness (From pytong methods at that)
