# EXPERIMENT 1: Introduction to Python Programming 
This repository contains Python codes for solving the given programming problems for this experiment. Full details of each solutions using Python are included in this repository. 

# 1. Alphabet Soup Problem 
Function used: alphabet_soup(s)

Description: The function takes one parameter 's', this is expected to be the string. 'def' is the keyword used to define a function. 's' is the argument that will be passed to the function when it is called. 

Function: ''.join(sorted(s))' 'return' 

Description: The function will help to sort the string and put them together. The return function returns the alphabetically sorted string.

Example: alphabet_soup("hello")

Output: "ehllo"

# 2. Emoticon Problem 
Function used: 'def words_to_emoticons(sentence)'

Description: This line defines a function named words_to_emoticons that takes a single argument sentence, which is expected to be a string. 

Dictionary: 'emoticon_map{...}'

Description: Dictionary in Python is a collection of key-value pairs.

Function: 'words = sentence.split()'

Description: This line splits the sentence string into a list of words. 'split()' is a method that divides the string into parts (words) wherever there is a space (by default) and returns a list of those words.

Line: 'result = [emoticon_map[word] if word in emoticon_map else word for word in words]' 

Description: Used to list comprehension to create a new list 'result'.

Line: 'return ' '.join(result)'

Description: This line joins the words back into a single string.

Example: print(emotify("Make me smile"))

Output: Make me :)





