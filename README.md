# Password-generator-program-
import random import string
def generate_password(length=8):
characters = string.ascii_letters + string.digits + string.punctuation password = ''.join(random.choice(characters) for _ in range(length)) return password
# Generate a password with default length of 8 characters print(generate_password())
# Generate a password with a specified length print(generate_password(12))
