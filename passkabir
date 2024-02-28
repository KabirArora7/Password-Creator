#Password Generator Project
import random
# List of Alphabets
alphabets = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']

# List of Numbers
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']

# List of Special Characters
special_chars = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

# Main Function
print("This is Password Generator!")
new_alphabets = int(input("How many alphabets do you like in your password?\n")) 
new_special_chars = int(input(f"How many special_chars do you like?\n"))
new_numbers = int(input(f"How many numbers do you like?\n"))

# List of Passwords
pass_list = []

for char in range(1, new_alphabets + 1):
    pass_list.append(random.choice(alphabets))

for char in range(1, new_special_chars + 1):
    pass_list += random.choice(special_chars)

for char in range(1, new_numbers + 1):
    pass_list += random.choice(numbers)

print(pass_list)
random.shuffle(pass_list)
print(pass_list)

password_str = ""
for char in pass_list:
    password_str += char

# F-string
# Printing the final password
print(f"Your generated password_str is: {password_str}")
