# Python3-program-to-Convert-characters-
https://www.geeksforgeeks.org/convert-alternate-characters-string-upper-case/

# Python3 program to Convert characters 
# of a string to opposite case
 
# Function to convert characters 
# of a string to opposite case
def convertOpposite(str):
    ln = len(str)
 
    # Conversion according to ASCII values
    for i in range(ln):
        if str[i] >= 'a' and str[i] <= 'z':
 
            # Convert lowercase to uppercase
            str[i] = chr(ord(str[i]) - 32)
 
        elif str[i] >= 'A' and str[i] <= 'Z':
 
            # Convert lowercase to uppercase
            str[i] = chr(ord(str[i]) + 32)
