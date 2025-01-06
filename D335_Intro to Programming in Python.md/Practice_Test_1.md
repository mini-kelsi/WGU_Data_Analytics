# 33.1 LAB: Formatted Output: No Parking Sign

**_instructor note_** *The skills required of this lab are covered in **Chapter 2 - Introduction to Python**.  To successfully complete this lab, review the content of Chapter 2 and complete the Challenge Activities associated.*

Write a program that prints a formatted "No parking" sign as shown below.  Note the first line has two leading spaces. For ALL labs, end with newline (unless otherwise stated).

>   NO PARKING
>
> 2:00 - 6:00 a.m.

![{FB77A694-3FF1-4326-9DA4-9725A5E91B40}](https://github.com/user-attachments/assets/38c55a17-153d-4690-a309-28b9e998811a)

-----------------------------

# 33.2

### LAB: Input: Mad Lib

**_instructor note_** *The skills required of this lab are covered in **Chapter 2 - Introduction to Python**.  To successfully complete this lab, review the content of Chapter 2 and complete the Challenge Activities associated.*

Mad Libs are activites that have a person provide various words, which are then used to complete a short story in unexpected (and hopefully) ways.

Complete a program that reads four values from input and stores the values in variables *first_name*, *generic_location*, *whole_number*, and *plural_noun*. The program then uses the input values to output a short story.  The first input statement is provided in the code as an example. 

**Notes:** To test your program in the Develop mode, pre-enter four values (in seperate lines) in the input box and click the Run program button.  the auto-grader in the Submit mode will test your program with different sets input of values.

Ex. If the input values are:

>Eric
>
>Chipotle
>
>12
>
>cars

then the program uses the input values and outputs a story:

> Eric went to Chipotle to buy 12 different types of cars

Ex. If the input values are:

> Brenda
>
> Philadelphia
>
> 6
>
> bells

then the program uses the input values and outputs a story:

> Brenda went to Philadelphia to buy 6 different types of bells


----------------------

# 33.3 LAB: Covert to Dollars

**_instructor note_** *The skills required of this lab are covered in **Chapter 3 - Variables and Expressions**.  To successfully complete this lab, review the content of Chapter 3 and complete the Challenge Activities associated.*

Given four values representing counts of quarters, dimes, nickels, and pennies, output the total amount as dollars and cents.

Output each floating-point value with two digits after the decimal point, which can be achieved as follows:
> print(f'Amount: ${dollars: .2f}')

Ex. If the input is:

> 4
>
> 3
>
> 2
>
> 1

where the 4 is the number of quarters, 3 is the number of dimes, 2 is the number of nickels, and 1 is the number of pennies, the output is:

> Amount: $1.41


----------------------

# 33.4 LAB: Driving Costs

**_instructor note_** *The skills required of this lab are covered in **Chapter 3 - Variables and Expressions**.  To successfully complete this lab, review the content of Chapter 3 and complete the Challenge Activities associated.*

Driving is expensive.  Write a program with a car's gas mileage (miles/gallon) and the cost of gas (dollars/gallon) as floating-point input, and output the gas coast for 20 miles, 75 miles, and 500 miles.

Output each floating-point value with two digits after the decimal point, which can be achieved as follows:

>print(f'{your_value1: .2f} {your_value2: .2f} {your_value3: .2f};)

Ex. If the input is:

> 20.0
>
> 3.1599

where the gas mileage is 20.0 miles/gallon and the cost of gas is $3.1599/gallon, the output is:

> 3.16 11.85 79.00

Note: Real per-mile cost would also include maintenance and depreciation.

-----------------------

# 33.5 LAB: Input and Foramtted Output: Right-Facing Arrow

**_instructor note_** *The skills required of this lab are covered in **Chapter 4 - Types**.  To successfully complete this lab, review the content of Chapter 4 and complete the Challenge Activities associated.*

Given input characters for an arrowhead and arrow body, print a right-facing arrow.

Ex. If the input is:

> *
>
> #

Then the output is:

>       #
> ******##
> ******###
> ******##
>       #


----------------------------

# 33.6 LAB: Phone Number Breakdown

**_instructor note_** *The skills required of this lab are covered in **Chapter 4 - Types**.  To successfully complete this lab, review the content of Chapter 4 and complete the Challenge Activities associated.*

Given an integer representing a 10-digit phone number, output the area code, prefix, and line number using the format (800) 555 - 1212.

Ex. If the input is:

> 8005551212

the output is:

> (800) 555 - 1212

*Hint:* Use % to get the desired rightmost digits. Ex. The rightmost 2 digits of 572 is gotten by 572 % 100, which is 72.

*Hint:* Use // to shift right by the desired amount. Ex. Shifting 572 right by 2 digits is done by 572 // 100, which yields 5. (Recall integer division discards the fraction).

For simplicity, assume any part starts with a non-zero digit. So 0119998888 is not allowed.


------------

# 33.7 LAB: Smallest Number

**_instructor note_** *The skills required of this lab are covered in **Chapter 5 - Branching**.  To successfully complete this lab, review the content of Chapter 5 and complete the Challenge Activities associated.*

Write a program whose inputs are three integers, and whose output is the smallest of the three values.

Ex. If the input is:

> 7
>
> 15
> 3

the output is:

> 3


---------------

# 33.8 LAB: Exact Change

**_instructor note_** *The skills required of this lab are covered in **Chapter 5 - Branching**.  To successfully complete this lab, review the content of Chapter 5 and complete the Challenge Activities associated.*

Write a program with total change amount as an integer input, and output the change using the fewest coins, one coin type per line.  The coin types are Dollars, Quarters, Dimes, Nickles, and Pennies.  Use singular and plural coin names as appropriate, like 1 Penny vs. 2 Pennies.

Ex: If the input is:

> 0

(or less than 0), the output is:

> No change

Ex. If the input is:

> 45

the output is:

> 1 Quarter
>
> 2 Dimes


--------------------

# 33.9 LAB: Output Range with Increment of 5

**_instructor note_** *The skills required of this lab are covered in **Chapter 6 - Loops**.  To successfully complete this lab, review the content of Chapter 6 and complete the Challenge Activities associated.*

Write a program whose input is two integers. Output is the first integer and subsequent increments of 5 as long as the value is less than or equal to the second integer.  End with a newline.

Ex. If the input is:

> -15
>
> 10

the output is:

> -15 -10 -5 0 5 10

Ex. If the second integer is less than the first as in:

> 20
>
> 5

the output is:

> Second integer can't be less than the first

*For coding simplicity, output a space after every integer, including the last.*


------------------

# 33.10 LAB: Print String in Reverse

**_instructor note_** *The skills required of this lab are covered in **Chapter 6 - Loops**.  To successfully complete this lab, review the content of Chapter 6 and complete the Challenge Activities associated.*

Write a program that takes in a line of text as input, and outputs that line of text in reverse.  The program repeats, ending when the user enters "Done", "done", or "d" for the line fo text.

Ex. If the input is:

> Hello there
>
> Hey
>
> done

then the output is:

> ereht olleH
>
> yeH


---------------------------

# 33.11 LAB: Fibonacci Sequence

**_instructor note_** *The skills required of this lab are covered in **Chapter 7 - Functions**.  To successfully complete this lab, review the content of Chapter 7 and complete the Challenge Activities associated.*

The Fibonacci sequence begins with 0 and then 1 follows.  All subsequent values are the sum of the previous two, ex: 0, 1, 1, 2, 3, 5, 8, 13. Complete the fibonacci() function, which has an index n as parameter and returns the nth value int he sequence. Any negative index values should return -1.

Ex. If the input is:

> 7

the output is:

> fibonacci(7) is 13

*Note: Use a for loop and **DO NOT** use recursion.


----------------

# 33.12 LAB: Calculate Average

**_instructor note_** *The skills required of this lab are covered in **Chapter 7 - Functions**.  To successfully complete this lab, review the content of Chapter 7 and complete the Challenge Activities associated.*

complete the calc_average() function that has an integer list parameter and returns the average value of the elements in the list as a float.

Ex. If the input list is:

> 1 2 3 4 5

then the returned average will be:

> 3.0


-----------------

# 33.13 LAB: Warm Up: Text Analyzer & Modifier

**_instructor note_** *The skills required of this lab are covered in **Chapter 10 - Strings**.  To successfully complete this lab, review the content of Chapter 10 and complete the Challenge Activities associated.*

(1) Prompt the user to enter a string of their choosing. Output the string. (1pt)

Ex.

> Enter a sentence or phrase:
>
> The only thing we have to fear is fear itself.
>
> 
> You entered: The only thing we have to fear is fear itself.

(2) Complete the get_num_of_characters() function, which returns the number of characters in the user's string.  *We encourage you to use a for loop in this functions.** (2pt)

(3) Extend the program by calling the get_num_of_characters() function and then output the returned result. (1pt)

(4) Extend the program further by implementiing the output_without_whitespace() function. output_without_whitespace() outputs the string's characters except for whitespace (spaces, tabs). Note: A tabe is '\t'. Call the output_without_whitespace() function in main(). (2pt)

Ex.

> Enter a sentence or phrase:
>
> The only thing we have to fear is fear itself.
>
> You entered: The only thing we have to fear is fear itself.
>
> 
> Number of characters: 46
>
> 
> String with no whitespace: Theonlythingwehavetofearisfearitself.


-----------------------

# 33.14 LAB: Palindrome

**_instructor note_** *The skills required of this lab are covered in **Chapter 10 - Strings**.  To successfully complete this lab, review the content of Chapter 10 and complete the Challenge Activities associated.*

A palindrome is a word or a phrase that is the same when read both forward and backwards.  Examples are: "bob", "sees", or "never ordd or even" (ignoring spaces).  Write a program whose input is a word or phrase, and that outputs whether that the input is a palindrome. 

Ex. If the input is:

> bob

the output is:

> bob is a palindrome

Ex. If the input is 

> bobby

the output is:

> bobby is not a palindrome

*Hint:* Start by removing spaces. Then check if a string is equivalent to it's reverse.


--------------------

# 33.15 LAB: Parsing Dates

**_instructor note_** *The skills required of this lab are covered in **Chapter 10 - Strings**.  To successfully complete this lab, review the content of Chapter 10 and complete the Challenge Activities associated.*

Write a program to read dates from input, one date per line.  Each date's format must be as follows: March 1, 1990.  Any date not following that format is incorrect and should be ignored.  The input ends with -1 on a line alone.  Output each correct date as: 3/1/1990.

*Hint:* Use string [start:end] to get a substring when parsing the string and extracting the date. Use the split() method to break the input into tokens.

Ex. If the input is:

> March 1, 1990
>
> April 2 1995
>
> 7/15/20
>
> Decemeber 13, 2003
>
> -1

then the output is:

> 3/1/1990
>
> 12/13/2003


----------------------

# 33.16 LAB: Car Wash

**_instructor note_** *The skills required of this lab are covered in **Chapter 11 - Lists and Dictionaries**.  To successfully complete this lab, review the content of Chapter 11 and complete the Challenge Activities associated.*

Write a program to calculate the total price for car wash services. A base car wash is $10.  A dictionary with each additional service and the corresponding cost has been provided.  Two additional services can be selected. A '-' signifies an additional service was not selected. Output all selected services, according to the input order, along with the corresponding costs and then the total price for all car wash services.

Ex. If the input is:

> Tire shine
>
> Wax

The output is:

> ZyCar Wash
>
> Base car was -- $10
>
> Tire shine -- $2
>
> Wax -- $3
>
> ----
>
> Total price: $15

Ex. if the input is:

> Rain repellent
>
> -

the output is:

> ZyCar Wash
>
> Base car wash -- $ 10
>
> Rain repellent -- $2
>
> ----
>
> Total Price: $ 12



---------------------

# 33.17 LAB: Simple Integer Division - Multiple Exception Handlers

**_instructor note_** *The skills required of this lab are covered in **Chapter 12 - Exceptions**.  To successfully complete this lab, review the content of Chapter 12 and complete the Challenge Activities associated.*

Write a program that reads integers user_num and div_num as input, and output to quotient (user_num divided by div_num). Use a try block to perform all the statements. Use an except block to catch any ZeroDivisionError and output an exception message Use another except block to catch any ValueError caused by invalid input and output an exception message.

*Note:* ZeroDivisionError is thrown when a division by zero happens. ValueError is thrown when a user enters a value of different data type than what is defined int he program.  Do not include code to throw any exception in the program.

Ex. If the input of the program is:

> 15
>
> 3

the output of the program is:

> 5

Ex. If the input of the program is:

> 10
>
> 0

the output of the program is:

> Zero Division Exception: integer division or modulo by zero

Ex. If the input of the program is:

> 15.5
>
> 5

the output of the program is:

> Input Exception: invalid literal for in() with base 10: '15.5'


--------------------

# 33.18 LAB: Step counter - Exceptions

**_instructor note_** *The skills required of this lab are covered in **Chapter 12 - Exceptions**.  To successfully complete this lab, review the content of Chapter 12 and complete the Challenge Activities associated.*

A pedometer treats walking 2,000 steps as walking 1 mile. Write a steps_to_miles() function that takes the number of steps as a parameter and returns the miles walked.  The steps_to_miles() function throws a ValueError object with the message "Exception: Negative step count entered." when the number of steps is negative.  Complete the main () program that reads the number of steps from a user, calls the steps_to_miles() function, and outputs the returned value from the steps_to_miles() function. Use a try-except block to catch any ValueError object thrown by the steps_to_miles() function and output the exception message.

Output each floating - point value with two digits after the decimal point, which can be achieved as follows:
> print(f'{your_value:.2f}')

Ex. If the input of the program is:

> 5345

the output of the program is:

> 2.67

Ex. If the input of the program is:

> -3850

the output of the program is:

> Exception: Negative step count entered.


--------------------------

# 33.19 LAB: Thesaurus

**_instructor note_** *The skills required of this lab are covered in **Chapter 14 - Files**.  To successfully complete this lab, review the content of Chapter 14 and complete the Challenge Activities associated.*


Given a set of text files cotaining synonyms for different words, complete the main program to output the synonyms for a specific word. Each text file contrains synonyms for the word specified in the file's name, and each row within the file lists the word's synonyms that begin with the same letter, separated by a space.  The program reads a wo





