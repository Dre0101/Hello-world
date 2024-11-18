# Dandre williams 00709860 
ASCII_LOWERCASE = "abcdefghijklmnopqrstuvwxyz"
ASCII_UPPERCASE = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
DECIMAL_DIGITS = "0123456789"

# function 
def is_alpha(word):
    for char in word:
        if char not in ASCII_LOWERCASE and char not in ASCII_UPPERCASE:
          return False
    return True 

def is_digit(s):
    for char in s:
        if char not in DECIMAL_DIGITS:
            return False
        return True
    
def to_lower(s):
   
   new_s = ''

   for i in range(len(s)):
       if s[i] in ASCII_UPPERCASE:
           new_s = new_s + s[i]. lower()
        else: 
           # do something

   return new_s 

print(to_lower("HELLO")) # hello

def to_upper(s):
    result = ""
    for char in s:
        if char in ASCII_LOWERCASE:
            # convert Lowercase to uppercse using ASCII values
            result += char(ord(char) - 32)
        else:
            result += char
    return result

def find_chr(s, char):
    if len(char) != 1:
        return -1
    for i in range(len(s)):
        if s[i] == char:
            return i 
    return -1

def replace_chr(s, old, new):
    if len(old) != 1 or len(new) != 1:
        return ""
    result = ""
    for char in s:
        if char == old:
            result += new 
        else:
            result += char 
    return result 

def replace_str(s, old, new):
    if old == "":
        # insert new string between each character in s 
        result = new 
        for char in s:
            result += char + new 
        return result 
    result = ""
    i = 0 
    while i < len(s):
        if s[i:i+len(old)] == old:
            result += new 
            i += len(old)
        else:
            result += s[i]
            i += 1
    return result






    
