# Password Generator🔐 

This is a simple Python script to generate random passwords of specified length.

## Usage

1. Run the script 'main.py'
2. Enter the desired length of the password.
3. Get your randomly generated password!

## Code

```python
import random

# Define characters to choose from
characters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%&*1234567890"

# Get password length from user
length = int(input("Enter Password length: "))

# Initialize password string
password = ""

# Generate password
for i in range(length):
    password += random.choice(characters)

# Print generated password
print("Generated Password:", password)
```
## Demo
![image](https://github.com/Ibrahim-Naseef/Password-Generator/assets/156147657/f91794fb-d642-4159-a376-5bd4702947e1)
