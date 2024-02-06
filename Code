import secrets
import string

no_of_passwords = int(input("Enter the no of passwords you want? "))
password_len = int(input("Enter the password length: "))
letter = string.ascii_letters
digit = string.digits
special_char = string.punctuation
selection_list = letter + digit + special_char

for i in range(no_of_passwords):
    password = ''
    for j in range(password_len):
        password += ''.join(secrets.choice(selection_list))
    print(password)
