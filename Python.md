<!---# Interactive Coding Exercise 1: Printing--->
<!---# Write a program in main.py that prints the same notes from the previous lesson using what you have learnt about the Python print function.
print("Hello world!")--->
       print("Hello world!\nHello world") <!--- \n means new line goes to next line --->
       ---->
       Hello world!
       Hello world!
       ______________________________
       print("Hello" + "Jeremy") --->
       HelloJeremy
       ______________________________
       print("Hello" + " " + "Jeremy") --->
       Hello Jeremy
       ______________________________
       print("What is your name?") --->
       What is your name?
       ______________________________
       input("What is your name?")  <!--- input("A prompt for the user-->
       What is your name? <!--- Cursor to input after the questions mark--->
       ______________________________
       print("Hello " + input("What is your name?")) --->
       Hello <!--- you would input your name after What is your name?--->
       What is your name?Jeremy --->
       Hello Jeremy
       
<!---# Interactive Coding Exercise 2: Debugging Practice--->
<!---# Look at the code in the code editor on the right. There are errors in all of the lines of code. Fix the code so that it runs without errors. --->
       print(Day1 - String Manipulation")
       print("String Concatenation is done with the "+" sign.")
         print('e.g. print("Hello " + "world")')
       print(("New lines can be created with a backslash and n.")

<!---# 1. Missing double quotes before the word Day.--->
      print("Day 1 - String Manipulation")
<!---# 2. Outer double quotes changed to single quotes.--->
      print('String Concatenation is done with the "+" sign.')
<!---# 3. Extra indentation removed.--->
      print('e.g. print("Hello" + "world")')
<!---# 4. Extra ( in print function removed.--->
      print("New lines can be created with a backslash and n.")

       
<!---# Interactive Coding Exercise 3: Input Fuction--->
<!---# Write a program that prints the number of characters in a user's name. You might need to Google for a function that calculates the length of a string.--->
       print( len( input("What is your name?"))) --->
       6 <!---calculates the length of characters in the input--->
       ______________________________
       

<!---# Interactive Coding Exercise 4: Variables--->
<!---# 🚨 Don't change the code below 👇--->
       a = input("a: ")
       b = input("b: ")
<!---# 🚨 Don't change the code above 👆--->

<!---#Write your code below this line 👇--->
       c = a
       a = b
       b = c
       _____________________________
       a = 100
       b = 5
       --->
       a = 5
       b = 100
       _____________________________
       _
       name = input("What is your name?) <!--- input would be Jeremy / name then would = Jeremy, so Jeremy would be printed. --->
       print(name) 
       ---> 
       Jeremy
       _____________________________
       print( len( input("What is your name?") ) ) <!---the action would print the length of characters of the name inputed. --->
       name = input("What is your name?") <!--- name inputed would be Jeremy --->
       length = len(name) <!--- length = len(Jeremy) --->
       print(length) <!--- 6 would be printed --->
       --->
       _____________________________
       
       Errors Encountered
<!---# IndentationError: unexpected indent--->
<!---# SyntaxError: EOL while scanning string literal--->
<!---# NameError: name 'nama' is not defined--->

<!---
JtheCoder4/JtheCoder4 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
