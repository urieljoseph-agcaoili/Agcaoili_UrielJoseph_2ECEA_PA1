# Agcaoili_UrielJoseph_2ECEA_PA1

# ECE2112

ALPHABET SOUP PROBLEM: Create a function that takes a string and returns a string with its letters in alphabetical order.

```python
s = input("Enter your word: ")   #Asks the user's input for the word which will have it's letters to be sorted in alphabetical order and puts it into a string.

def alphabet_soup(s):   #The function takes the word from the string which will have it's letters to be sorted in to alphabetical order.
    return ''.join(sorted(s))   #This sorts the letters of the word to alphabetical order, joins the letters to form the word in alphabetical order and returns it.

alphabet_soup(s)   #This shows the word in alphabetical order to the user.
```

EMOTICON PROBLEM: Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.

```python
s = input("Enter the sentence to emotify:")   #Asks the user's input for the sentence which will have it's selected words to be converted to emojis and puts it into a string.

def emotify_sentence(sentence):   #The function takes the sentence from the string and converts the selected words into emojis.
    sentence = sentence.replace("smile", ":)")   #Converts the word "smile" in the sentence into ":)".
    sentence = sentence.replace("grin", ":D")   #Converts the word "grin" in the sentence into ":D".
    sentence = sentence.replace("sad", ":(")   #Converts the word "sad" in the sentence into ":(".
    sentence = sentence.replace("mad", ">:(")   #Converts the word "mad" in the sentence into ">:(".
    return sentence   #This returns the sentence with the seleceted words converted into it's emoji form.

emotify_sentence(s)   #This shows the converted sentence to the user.
```

UNPACKING LIST PROBLEM: Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

```python
writeyourcodehere = [1, 2, 3, 4, 5, 6, 9, 30]   #A list that stores the numbers.

first = writeyourcodehere[0]   #This takes the first element from the list.
last = writeyourcodehere[-1]   #This takes the last element from the list.
middle = writeyourcodehere[1:-1]   #This takes the elements inbetween the first and last element of the list.

print("First:", first)  #Displays "First: " and the first element from the list.
print("Middle:", middle)   #Displays "Middle: " and the elements between the first and last element from the list.
print("Last:", last)   #Displays "Last: " and the last element from the list.
```
