# Palindrome_checker
def is_palindrome(string):
    return string == string[::-1]

word = input("Enter a word: ")
if is_palindrome(word):
    print("It's a palindrome!")
else:
    print("Not a palindrome.")
