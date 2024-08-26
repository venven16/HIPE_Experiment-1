# Experiment 1 Codes

1. 
# Start
def alphabet_soup(s):
    return ''.join(sorted(s))

# Output
print(alphabet_soup("hello"))  # Output: ehllo
print(alphabet_soup("hacker")) # Output: acehkr 

2. 
# Start
def emotify(sentence): 
    # Dictionary for mapping words to their corresponding emoticons 
    emoticon_map = {"smile": ":)", "Grin": ":D", "sad": ":((", "mad": ">:("}
    
    # Splitting the sentences into words 
    words = sentence.split()
    
    # Replace the words with emoticons 
    output = [emoticon_map[word] if word in emoticon_map else word for word in words]
    
    # Retrurning the the words back into a sentence 
    return ' '.join(output) 

# Output
print(emotify("Make me smile")) # Output: Make me :)
print(emotify("I am mad")) # Output: I am >:(

3. 
# Start

# Listing the variables 
writeyourcodehere = [1, 2, 3, 4, 5, 6] 

# Unpacking the varibles into first, middle and last
first, *middle, last = writeyourcodehere

# Example 
print("Example: 1st = [1, 2, 3, 4, 5, 6]")  
print()

# Output 
print("first:", first, end="     ") # Output: 1
print("middle:", middle, end="    ") # Output: 2,3,4,5
print("last:", last) # Output: 6
