# Agcaoili_UrielJoseph_2ECEA_PA1
# ECE2112

ALPHABET SOUP PROBLEM: Create a function that takes a string and returns a string with its letters in alphabetical order.

```python
s = input("Enter your word: ")   #Gets the user's input for the word which will have it's letters to be sorted in alphabetical order and puts it into a string.

def alphabet_soup(s):   #The function which takes the word from the string and sorts the letters of the word in alphabetical order.
    return ''.join(sorted(s))   #This returns the word with it's letters in alphabetical order

alphabet_soup(s)
```
