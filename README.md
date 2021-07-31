# Check-whether-a-string-is-a-pangram.
 # Python3 program to # Check if the string is pangram import string    alphabet = set(string.ascii_lowercase)    def ispangram(string):     return set(string.lower()) >= alphabet        # Driver code string = "The mental patient is going to hospital." if(ispangram(string) == True):     print("Yes") else:     print("No")
