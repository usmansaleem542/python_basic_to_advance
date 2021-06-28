# Basic Syntax
## Print something
    print("Something")
    print('Something')
## Comments in Python
    # First comment
    print ("Hello, Python!") # second comment
## Print Variable Value
    a = 5
    print(a)
    print("Value of A: ", a)
    print("Value of A: {}".format(a))
    print(f"Value of A: {a}") 
## Lines and indentation
Python does not use braces({}) to indicate blocks of code for class and function definitions or flow control
Blocks of code denoted by line indentation
    
    a = 5
    if a == 5:
        print("True")
    else:
        print("False")

Note: Python ignores comments, blank lines
## Input From User
    user_val = input("\n\nPress the enter key to exit.")
    print(user_val)

## Strings
    str = 'Hello World!'
    print (str)          # Prints complete string
    print (str[0])       # Prints first character of the string
    print (str[2:5])     # Prints characters starting from 3rd to 5th
    print (str[2:])      # Prints string starting from 3rd character
    print (str * 2)      # Prints string two times
    print (str + "TEST") # Prints concatenated string

## Lists
    list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
    tinylist = [123, 'john']
    
    print (list)          # Prints complete list
    print (list[0])       # Prints first element of the list
    print (list[1:3])     # Prints elements starting from 2nd till 3rd 
    print (list[2:])      # Prints elements starting from 3rd element
    print (tinylist * 2)  # Prints list two times
    print (list + tinylist) # Prints concatenated lists

## Tuples
    tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
    tinytuple = (123, 'john')
    
    print (tuple)           # Prints complete tuple
    print (tuple[0])        # Prints first element of the tuple
    print (tuple[1:3])      # Prints elements starting from 2nd till 3rd 
    print (tuple[2:])       # Prints elements starting from 3rd element
    print (tinytuple * 2)   # Prints tuple two times
    print (tuple + tinytuple) # Prints concatenated tuple

## Dictionary
    #!/usr/bin/python3

    dict = {}
    dict['one'] = "This is one"
    dict[2]     = "This is two"
    
    tinydict = {'name': 'john','code':6734, 'dept': 'sales'}
    
    print (dict['one'])       # Prints value for 'one' key
    print (dict[2])           # Prints value for 2 key
    print (tinydict)          # Prints complete dictionary
    print (tinydict.keys())   # Prints all the keys
    print (tinydict.values()) # Prints all the values

## Arithmetic Operators
    + Addition -------->   5 + 2 = 7
    - Subtraction ----->   5 – 2 = 3
    * Multiplication -->   5 * 2 = 10
    / Division -------->   5 / 2 = 2.5
    % Modulus --------->   5 % 2 = 1
    ** Exponent ------->   5 ** 2 = 25
    // Floor Division-->   5 // 2 = 2

## Comparison Operators
    ==
    !=
    >
    <
    >=
    <=

## Decision Making
    if
    elif
    else

## Loops

# Lets Learn Git
Git is a distributed revision control and source code management system
Git is a free software