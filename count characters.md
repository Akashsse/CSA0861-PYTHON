# CSA0861-PYTHON
def count_chars(string):
    letters = 0
    digits = 0
    symbols = 0

    for char in string:
        if char.isalpha():
            letters += 1
        elif char.isdigit():
            digits += 1
        else:
            symbols += 1

    return (letters, digits, symbols)

input_string = "Hello, World! 123"
(letters, digits, symbols) = count_chars(input_string)
print("Letters:", letters)
print("Digits:", digits)
print("Symbols:", symbols)
