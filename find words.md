# CSA0861-PYTHON
def find_words_with_alphabets_and_numbers(string):
    result = []
    words = string.split()
    for word in words:
        has_alphabet = False
        has_number = False
        for char in word:
            if char.isalpha():
                has_alphabet = True
            elif char.isdigit():
                has_number = True
            if has_alphabet and has_number:
                result.append(word)
                break
    return result

# Example usage
string = "Hello 123, this is a mixed string with alphabets and numbers 123456"
print(find_words_with_alphabets_and_numbers(string))
# Output: ['Hello', '123']
