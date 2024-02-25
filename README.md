---

# Secure Password Generator

## Overview
This is a simple yet secure password generator implemented in Python. It generates random passwords with customizable length and character composition, ensuring a balance between security and usability.

## Features
- Generates strong and random passwords.
- Customizable password length.
- Ability to include specific types of characters: numbers, special characters, uppercase letters, and lowercase letters.

## Usage
To use the password generator, simply call the `generate_password()` function from the provided script. By default, it generates a password with a length of 16 characters, including at least one of each character type (number, special character, uppercase letter, lowercase letter).

You can customize the password generation by providing arguments to the `generate_password()` function:
- `length`: Length of the generated password (default is 16).
- `nums`: Number of digits in the password (default is 1).
- `special_chars`: Number of special characters in the password (default is 1).
- `uppercase`: Number of uppercase letters in the password (default is 1).
- `lowercase`: Number of lowercase letters in the password (default is 1).

## Dependencies
This script requires the `secrets` and `string` modules from the Python standard library.

## Example
```python
if __name__ == '__main__':
    new_password = generate_password()
    print('Generated password:', new_password)
```

## Notes
- The password generator ensures that each generated password meets the specified constraints regarding the inclusion of different types of characters.
- The randomness of generated passwords is ensured by using Python's `secrets` module, which provides a cryptographically secure source of randomness.

---
