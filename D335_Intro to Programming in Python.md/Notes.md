## 2.1 Programming

- A computer **program** consists of  of instructions executing one at a time.
- Basic intrustion types are:
  - **Input** A program gets data, perhaps from a file, keyboard, touchscreen, network, etc.
  - **Process** A program performs computations on that data, such as adding two values like x + y.
  - **Output** A program puts that data somewhere, such as to a file, screen, or network.

- **Variables** refer to data, like x,y and z. The name is due to a variable's value "varying" as a program assigns a variable like x with new values.

  - **Computational thinking** is creating a sequence of instructions to solve a problem.
 
  - **Algorithm** is a sequence of instructions that solves a problem.

 ## 2.2 Programming using Python
 
  - **Python interpreter** is a computer program that executes code written in the Python programming language.
 
  - **interactive interperater** is a program that allows ther user to execute one line of code at a time.
 
  - **Code** is a common word for the textuall representation of a program.
 
  - **Line** is a row of text.
 
  - The interactive interpreter displays a **prompt** (">>>") that indicates the interpreter is ready to accept code.
 
  - **Statement** is a program instruction. A *program* mostly consists of a *series* of statements, and each statement usually appears on its own line.

  - **Expressions** are code that return a value when evaluated; for example, the code _wage * hours * weeks_ is an expression that comput4es a number. The symbol * is used for muliplication.  The names wage, hours, weeks, and salary are **variables**, which are named references to values stored by the interpreter.

  - A new variable is created by performing an **assignment** using the = symbol, such as _salary = wage * hours * weeks_, which creats a new variable called salary.

  - The **print()** function displays variables or expression values.

  - '#' characters denote **commnets**, whihc are optional but can be used to expl;ain portions of code to a human reader.

    **_What is the purpose of variables?_**
    
      - **Store values for later use.**

    **_The code 20 * 40 is an expression._**
    
      -**True**

    **_How are most Python programs developed?_**
    
      -**Writing code in files.**

    **_Comments are required in a program._**
    
      -**False.**

### A First Program

> wage = 30
>
> hours = 40
>
> weeks = 52
> 
> salary = wage * hours * weeks
>
> print('Salary is:', salary)
>
> hours = 35
>
> salary = wage * hours * weeks
>
> print('New salary is:', salary)
>
### Output

> Salary is: 62400
> 
> New salary is: 54600

## 2.3 Basic Input and Output

- The primary way to print output is to use the built-in function **print()**.

- Text enclosed in quotes is known as a **string literal**. Text in string literals may have letters, numbers, spaces, or symbols like @ or #.  Each use of *print()* starts on a new line.

- A literal string can be surrounded by matching single or double quotes. *Good practice is to use single quotes for shorter strings and double quotes for more complicated text or text that contains single quotes, like print ("Don't eat that!:)*

### Printing Text

 - Each print statement starts on a new line
>
> print('Hellow there.')
>
> print('My name is ...')
>
> print('Carl?')

### Output

> Hello there.
>
> My name is...
>
> Carl?

  **_Select the statement that prints the following: Welcome_**
  
    -**print('Welcome!')**
    
  **_Type a statement that prints the following: Hello_**
  
    -**print('Hello')**

- Can add end=' ' inside of print() to keep the output of a subsequent print statement on the same line seperated by a single space.

- EX. print('Hello', end-' ').

   **_Which pair of statements print output on the same line?_**

    - **print('Halt!', end=' ')**
      
    - **print('No access!')**

  **_Given the variable num_cars=9, which statement prints 9?_**
  
    - **print(num_cars)**
 
  **_Write a statement that prints the value of the variable num_people._**
  
    -**print(num_people)**

- Output can be moved to the next line by printing "\n", known as a **newline character**.

- EX. print('1\n2\n3') prints "1" on the first line, "2" on the second line, and "3" on the third line of output.
    
- print() always adds a newline character after the output automatically to move the next output to the next row, unless end=' ' is provided to replace the newline character with a space (or some other character).  An empty print() can be used to print only a newline.

  ### Printing without Text

  > print('123')
  >
  > print()
  >
  > print('abc')

  - Any space, tab, or newline is called **whitespace**.
 
   **_What is the output of print('You are', age, 'years old.')_**
  
    -**You are 22 years old.**

## 2.4 Errors

- **Syntax error** is a kind of mistack to violate a programming language's rule on how symbols can be combined to create a program.  'An example is putting multiple prints on the same line.'

   **_print(num_dogs)._**
  
    -**Error**
  
  **_print("Dogs:"num_dogs)_**
  
    -**Error**

  **_print('Woof!")_**
  
    -**Error**

  **_print(Woof!)_**
  
    -**Error**

  **_print("Hello + friend!")_**
  
    -**No Error**

  **_Experienced programmers write an extire program before running and testing the code._**
  
    -**False**

- **Runtime error** is wherein a program's syntax is correct but the program attempts an improssible operation, such as dividing by zero or multiplying strings together (like 'Hello' *'ABC').

- Abrupt and unintended termination of a program is often called a **crash** of the program.

![image](https://github.com/user-attachments/assets/94ac8356-86ec-4a48-85ff-151aa7d60eca)

![image](https://github.com/user-attachments/assets/0f151f96-6aa1-4401-9984-abeec3f87a00)

- A **logic error** is where the program is logically flawed.  The program would load correctly but would not behave as intended.

- A logic error is often called a **bug**.
  

## 2.5 Development Environment

- Code development is usually done with an **integrated development environment** or *IDE*. There are various IDEs that can be found online.

    - **IDLE** is the offical Pyhon IDE that is distributed with the installation of Python. Provides a basic environment for editing  and running programs.
    - **PyDev** is a plugin for the popular Eclipse program. PyDev includes extra features such as code completion, spell checking, and a debugger that can be useful tools while programming.
    - For *learning purposes*, web-based tools **CodePad** or **Repl** are useful.

   **_Python comes pre-installed on Windows machines._**
  
    -**False**

  **_Python code can be written in a simple text editor, such as Notepad (Windows)._**
  
    -**True**

  
## 2.6 Computers and Programs (General)

- 0s and 1s are known as **bits** (binary digits)

- Connections of switches, known as **circuits**, are built to perform calculations such as multiplying two numbers.

- Circuits called **processors** were created to process a list of desired calculations, each calculation called an **instruction**

- **Memory** is a circuit that can store 0s and 1s in each of a series of thousands of addressed locations.

- *A computer is basically a processor interacting with a mermory.*

- Programmer-created sequence of instructions is called a **porgram**, **application** or just **app**.

  **_A bit can only have the value of 0 or 1._**
  
    -**True**

  **_Switches have gotten larger over the years._**
  
    -**False**

  **_Memory stores bits._**
  
    -**True**

  **_The computer inside a modern smartphone would have been huge in 1960._**
  
    -**True**

  **_A processor executes instructions such as Add 200, #9, 201, represented as 0s and 1s._**
  
    -**True**  *A program is just a large list of such instructions.*


- Insturctions represeneted as 0s and 1s are known as **machine instructions**.

- A sequence of machine instructions together form an **executable program**.

- **Assemblers** are programs that automatically translate human readable instructions language instrutions into machine instructions.

- **Compilers** are programs that automatically translate high-level languageprograms into executable programs.
  

![image](https://github.com/user-attachments/assets/c2a34d5c-594d-4a33-a06c-dcd065bd26e4)


## 2.7 Computer Tour 

- **Input/Output Devices**: A **screen**(or monitor) displays items to a user. A **keyboard** allows a user to provide imput to the computer, typically accompnied by a *mouse* for graphical displays.

- **Storage**: A **disk** (aka *hard drive*) stores files and other data, such as program files, song/movie files, or officer documents.
   - Disks are *non-volatile*, meaning they maintain their contents even when powered off. *They do so by orienting magnetic particles in a 0 or 1 position.  The disk spins under a head that pusles electricity at just the right times or orient specific particles.*
   - Flash storage is also non-volatile. *They tunnel electrons into special circuits on the memory's chip and remove them with a **flash** of electricity that draws the electrons back out.*

- **Memory**: **RAM**(random-access memory) temporarily holds data red from storage and is designed such that any address can be accessed much faster that disk.
   - RAM is *volatile*, losing its contents when powered off.

- Memory size is typically listed in bits, or in bytes where a **byte** is 8 bits.
   - megabytes (million bytes)
   - gigabytes (billion bytes)
   - terabytes (trillion bytes)

- **Processor**: The **processor** runs the computer's programs, reading and executing instructions from memory, performing operations, and reading/writing data from/to memory.

- **Operating system** allows a user to run other programs and interfaces with the many toher peripherals. **CPUs** and **microprocessors** are also processors.

- A processor my contain a small amount of RAM on its own chip, called **cache** memory, acessible in one clock tick rather than several, for maintaining a copy of the most-used instructions/data.

- **Clock**" A processor's instructions execute at a rate governed by the processor's **clock**, which ticks at a specific frquency.
- 

![image](https://github.com/user-attachments/assets/bae1b05d-4255-4f27-abeb-6d9f28f3eecd)


*Side Note: A common way to make a PC faster is to add more RAM.*

## 2.8 Language History

- A **script** is a program whose instructions are executed by another program called an **interpreter**.

- **Open-source** language means that the community of users participate in defining the language and creating new interpreters, and is suppported by a larger community or programmers.

- Python is open-source.

   **_Python was first implemented in 1960._**
  
    -**False**  *Python was conceived in the late 1980s, and first implemented in the early 1990s.*

  **_Python is a high-level language that excels at pcreatin exceptionally fast-executing programs._**
  
    -**False**  *Python excels at providing powerful programming paradigms such as object-oriented programming and dynamic typing. Python incurs additional overhead costs because the language is interpreted.*

  **_A major drawback of Python is that Python code is more difficult ot read that code in most other programming languages._**

    -**False**  *Python was orgianlly designed with readability in mind.  Some of the maxims of Python include "simple is better than complex" and "readablity counts."*


## 2.9 Why Whitespace Matters

- **Whitespace** is any black space or newline.

  **_The programmer on the left intentionally inserted a newline in the first sentence, namely "kia Smith...video meeting". Why?_**

    -**So the text appears less jagged**

  **_The programmer on the right did not end the first sentence with a newline. What effect did that omission have?_**

    -**"Join meeting" apears on the same line**

  **_The programmer on the left neatly formatted the link, the "Phone:"text, and phone numbers. What did the programmer on the right do?_**

    -**Output those items without neatly formatting**

  **_On the right, why did the "Reminder..."text appear on the same line as the separator text "----"?_**
  
    -**Because the programmer didn't end the output with a newline**
 
  **_Whitespace ____ important in program output._**
  
    -**is**

## 3.1 Variables and Assignments

- A **variable** is a named item, such as x or num_people, used to hold value.

- **Assignment statement** assigns a variable with a vlaue, such as x=5.  That statement means x is assigned with 5, and x keeps that value during subsequent statements, until x is assigned again.

  *In programming, = is an assignment of a left-side variable with a right-side value. x=5 is read as "x is assigned with 5"*
  
*Indicate which assignment statements are valid.*

  **_x = 1_**
    
  -**Valid**

  **_x = y_**
    
  -**Valid**

  **_x = y + 2_**
   
  -**Valid**

  **_x + 1 = 3_**
  
  -**Invalid**

  **_x + y = y + x_**
    
  -**Invalid** 

*Given variables x, y, and z.*

**_x = 9,     y= x + 1,      What is y?_**
 -**10**

 **_x = 9,  y = x + 1,  What is x?_**
  -**9**

  **_x = 9, y = x + 1, x = 5, What is y?_**
   -**10**

- Increasing a variable's value by 1, as in x = x + 1, is common and known as **incrementing** the variable.

*Indicate the value of x after the statements execute.*

  **_x = 5, x = x + 7_**
   -**12**

  **_x = 2, y = 3, x = x (*)y, x = x(*) y_**
   -**18**

  **_y = 30, x = y + 2, x = x + 1_**
   -**33**

  **_Complete this statement to increment y: y=___ _**
   -**y+1**

## 3.2 Identifiers

- An **identifier** (also called a name) is a sequence of letters, underscores and digits and must start with a letter or an underscore.

- Python is **case sensitive**

- **Reserved words** (keywords) are words that are part of the language that cannot be used as a programmer-defined name. My language editors will automatically color a program's reserved words.

 *Which of the following are valid names?*

 **_numCars_**

  -**Valid**

**_num_cars1_**

  -**Valid**

**__numcars2_**

  -**Valid**

**_num cars_**

  -**Invalid**

**_3rd_place_**

  -**Invalid**

**_third_place__**

  -**Valid**

**_third_place!_**

  -**Invalid**

**_output_**

  -**Valid**

**_return_copy_**

  -**Valid**


- **PEP 8** is a document that outlines the basics of how to write Python code neatly and consistently.

- PEP 8 is an acronym for Python Enhancement Proposal.


## 3.3 Objects

- An **object** represents a value and is automatically created by the interpreter when executing a line of code.

- Deleting unused objects is an automatic process called **garbage collection** that helps to keep the memory of the computer less utilized.

- **Name binding** is the process of associating names wih interpreter objects. *An object can have more than one name bound to it, and every name is always bound to exactly one object.*

- Each Python object has three defining properties: value, type and identity.
   - **Value** A value such as "20", "abcdef", or 55.
   - **Type** The type of the objec, such as integer or string.
   - **Identity** A unique identifier that describes the object.
 
- The built-in function **type()** returns the type of an object.
  
- **Mutability** indicates whether the object's value is allowed to be changed.

- Integers and strings are **immutable**; modifying their values with assignment statements results in new objects being created and the anmes bound to the new object.

- Python provides a built-in function **id()** that gives the value of an object's identity.

  **_Which built-in function finds the type of an object?_**
   -**type()**

  **_Write an expression that gives the identity of a variable called my_num._**
  -**id(my_num)**

## 3.4 Numeric types: Floating - Point

- A **floating-point number** is a real number, like 98.6, 0.0001, or -666.667.

- **Float** is a data type for lfoating-point numbers.

- A **floating-point literal** is written with the fractional part even if the fraction is 0, as in 1.0, 0.0, or 99.0.

- A floating-point literal using **scientific notation** is written using an e preceding to the power of 10 exponent, as in 6.02e23 to represent 6.02x10^23.

  *The e stands for exponent.*

   **_Type 1.0e-4 as a floating-poihnt literal with a single digit beofre and four digits  after the decimal point._**
  
    -**0.0001**

  **_Type 7.2e-4 as a floating-point literal with a single digit before and five digits after the decimal point._**
  
    -**0.00072**

  **_Type 540,000,000 as a floating-point literal using scientific notation with a single digit before and after the decimal point._**
  
    -**5.4e8**

  **_Type 0.000001 as a floating-point literal using scientific notation with a single diit before and after the deciaml point._**
  
## 3.5 Arithmetic Expressions

- An **expression** is a combination of items, like variables, literals, operators, and parentheses, that evalutes to a value, like 2*(x+1).

- A **literal** is a specific value in code like 2.

- An **operator** is a symbol that performs a built-in calculation, like +.

![image](https://github.com/user-attachments/assets/535853fc-d006-4738-89d3-8c0240abfda6)

*Indicate which are valid expressions. x and y are variables.*

**_x + 1_**

 -**Valid**

**_2 * ( x - y )_**

 -**Valid**

**_x_**

 -**Valid**

**_2_**

 -**Valid**

**_2x_**

 -**Not Valid_** *In programming, multiplaction typicaly mujst be indicated explicitly using the * operator.*

**_2 +(xy)_**  

 -**Not Valid**

**_y = x + 1_**

 -**Not valid** *y-x+1 is an  assignment and not itself an expression.*

 --------

 *Does the expression correctly capture the intended behavior?*

 **_6 plus num_items:
 6 + num_items_**

  -**Yes**

**_6 times num_items:
6 x num_items_**

 -**No**  *The multiplication operator is * not x.*

**_total_days divided by 12:
total_days / 12_**

 -**Yes**

**_5 times t:
5t_**

 -**No**

**_The negative of user_val:
-user_val_**

-**Yes**
**_n factorial:
n!_**

 -**No** *Python doesn't use the ! symbol for factoral.*

---

- An expression **evaluates** to a value, which replaces the expression.

- An expression is evaluated using the order of standard mathematics, and such order is known in programming **precedence rules**

![image](https://github.com/user-attachments/assets/b96d12cb-0834-48cc-96f6-e046a0be61a1)

---

*Select the expression whose parentheses match the evaluation order of the original expression.*

**_y+2*z_**

 -**y+(2*z)**

**_z/2-x_**

 -**(z/2)-x**

**_x*y*z_**

 -**(x*y)* z**

**_X+1*y/2_**

 -**x+((1*y)/2)**

**_x/2+y/2_**

 -**(x/2)+(y/2)**

**_What is total_count after executing the following?
num_items=5
total_count= 1 + (2 * num_items) *4_**

 -**41**

## 3.6 Python Expressions

- A good practice is to include a single space around operators for readability, as in num_items + 2, rather than num_items+2.

- Minus (-) used as negative is known as **unary minus**

- Special operators called **compound operators** provide a shorthand way to update a variable, such as age **+=** 1 being shorthand for age = age + 1. Other coumpound operators include -=, *=, /= and %=.

![image](https://github.com/user-attachments/assets/fc32c5fe-f667-4720-b875-52ca344cccc5)

*Compound Operators*

**_num_atoms is initally 7. What is num_atoms after:
num_atoms += 5?_**

 -**12**

**_num_atoms is initally 7. What is num_atoms after:
num_atoms *= 2?_**

 -**14**

**_Rewrite the statemtent using a compound operator, or type: Not possible
car_count = car_count + 1_**

 -**car_count /= 2**

**_Rewrite the statement using a compound operator, or type: Not possible
num_items = box_count + 1_**

 -**Not possible** *A compound operator is shorthand for when a variable is updated, not for a more general assignment.*

**_The following code correctly assigns num_years with an integer value of 2 billion._**

**_num_years = 2,000,000,000_***

 -**False** *Commas aren't allowed in an integer literal.*

![image](https://github.com/user-attachments/assets/3c14a150-7c3a-4911-9320-93ab45c269e7)

![image](https://github.com/user-attachments/assets/da8ac2f1-34c1-4a2b-b7bc-6dd39a36784b)


## 3.7 Division and Modulo

-The division operator / performs division and returns a floating-point number. Ex:

  - 20 / 10 is 2.0
    
  - 50 / 50 is 1.0
    
  - 5. 10 is 0.5


- The floor divison operator // can be used to round down the result of a floating-point division to the closest smaller whole number value.  The resulting value is an integer type if both operands are integers; if either operand is a float, then a float is returned:

   - 20 // 10 is 2
 
   - 50 // 50 is 1
 
   - 5 // 10 is 0 (5/10 is 10 and the remainder 5 is thrown away)
 
   - 5.0 // 2 is 2.0

- For division, the second operand of / or // must never be 0, because division by 0 is mathematically undefined.

*Determine the result. Type "Error" if the program would terminate due to division by 0.  If the answer is a floating-point number, answer the form #. #, even if the answer is a whole number.*

**_12 / 4_**

 -**3.0**

**_5 /10_**

 -**0.5**

**_0.5 // 2_**

 -**2.0**

**_100 / 0_**

 -**Error** *100/0 is undefined and causes the program to terminate.*

- The **modulo operator(%)** evaluates the remainder of the division of two integer operands.

**_50 % 2_**

 -**0** *50 / 2 is 25 with remainder 0.*

**_51 % 2_**

 -**1** *Note that any odd number %2 is 1, while any even number % 2 is 0.*

**_78 % 10_**

 -**8** *78 / 10 is 7 with remainder 8.*

**_596 % 10_**

 -**6** *Note that any number % 10 yields the digit in the rightmost (1s) place, in this case 6.*

**_100 % (1 // 2)_**

 -**Error** *(1 // 2 ) evaluates to a 0. 100 % 0 is undefined (as 100/ 0 is undefined) and causes the program to terminate.*
 
 -----

**_Given a non-negative number x, which expression has the range 5 to 10?_**

 -**(x % 6) + 5** *% 6 yields 0 to 5. Then + 5 yields 5 to 10.*

**_Given a non-negative number x, which expression has the range -10 to 10?_**

 -**(x % 21) - 10_** *x % 21 yields 0 to 20. The -10 yields -10 to 10.*

**_Which gets the tens digit of x. Ex: If x=693, which expression yields 9?_**

 -**(x // 10) % 10_** *x // 10 shifts right one place, putting the tens digit in the ones place.  Then % 10 gets the (new) ones digit. Ex: 693 // 10 is 69, then 69 % 10 is 9.*

**_Given a 16-digit credit card number stored in x, which expression gets the last (rightmost) four digits? (assume the fourth digit from the right is non-zero.)_**

 -**x % 10000** *x % 10000 yields 0 -9999, being the rightmost four digits.  To get other digits like the next four digits, divide first to shift the desired digits to the rightmost digits, then use % to get just those digits.*

## 3.8 Module Basics

- Programmers typically write Python program code in a file **script** and execute the code by passing the script as in put to the Python interpreter.

- A **module** is afile containing Python code that can be used by other modules or scripts.

- A module is made available for use via the **import** statement.

- Once a module is imported, any object defined in that module can be accessed using **dot notation.**

![image](https://github.com/user-attachments/assets/3605a47b-0e6b-42a2-82aa-649303eafb44)

![image](https://github.com/user-attachments/assets/ca5553a8-228e-461a-b8c9-efe860a82fd3)

## 3.9 Math Module

- Python comes with a standard **math module** to support such advanced math operations.

- A **module** is Python code located in another file.  The programmer can import the module for use

- A **function** is a list of statements that can be exectued simply by referring to the function's name.

- The process of invoking a function is referred to as a **function call**.

- The item passed to a function is referred to as an **argument**.

![image](https://github.com/user-attachments/assets/4266fbc4-0be9-407f-abfb-5e6f1119cc47)

*Determine the final value of z.*

**_x = 2.3
z = math.ceil (x)_**

 -**3**

**_x = 2.3   z = math.floor (x)_**

 -**2**

**_z = 4.5    z = math.pow (math.floor (z), 2.0)_**

 -**16**  *math.floor(z) returns 4. Then math.pow(4, 2.0) returns 16.0.*

**_z = 15.75  z = math.sqrt (math.ceil (z))_**

 -**4.0** *math.ceil(z) returns 16. Then, math.sqrt(16) returns 4.0.*

**_z = 4    z = math.factorial (z)_**

 -**24** 

 ## 3.10 Representing Text

 - Python uses **Unicode** to represent every possible character as a unique numbr, known as **code point.**

 - A **newline** character, which indicates the end of a line of text, is encoded as 10.

 - The \ is known as a **backslash**

 - Upon reaching a \, the interpreter reconizes that item as the start of a special character's two-item sequence and then looks at the enxt item to determine the special character.  The two-item dequence is called an **escape sequence**.

![image](https://github.com/user-attachments/assets/d5bb8dcb-3f6e-4900-a29d-f167bffdaf02)

*Escape Sequences*

**_What is the output of print('\\c\\users\\juan')**

 -**/c/users/juan**

**_What is the output of print('My name is \'Tater Tot\'.')_**

 -**My name is 'Tator Tot.'**

**_What is the output of print('10...\n9...')_**

 -**10...
 9...**

 - Excape sequences can be ignored using a **raw string**. A raw string is created by adding a 'r' before a string literal, as in r'this is a raw string\' ', which would output as this is a raw string\'.

 - The built-in function **ord()** returns an encoded integer value for a string of length one.

 - The built-in funcion **chr()** returns a string of one character for an encoded integer.

**_Complete the code to output *\\*_**

 -**print(r"\\")**

**_Use a raw striing literal to assign "C:\file.doc" to my_string (without quotes)._**

 -**my_str = r'C:\file.doc'**

## 4.1 String Basics

- A **string** is a sequence of characters, like the text MARY, that can be stored in a variable.

- A **string literal** is a string value specified in the course code of a program.

- A programmer creates a string literal by surrounding ext with single or double quotes, such as 'MARY' or "MARY".

- The string type is a special construct known as **sequence type**.

**_Which answer creates a string variable first_name with a value 'Daniel'?_**

 -**first_name = 'Daniel'**

**_Which answer prints the value of the first_name variable?_**

 -**print(first_name)**

**_Which answer assigns first_name with a stirng read from input?_**

 -**frist_name = input('Type your name:')**

**_Which answer assigns first_name with an empty string?_**

 -**first_name = ' '**

- The **len()** built-in function can be used to find the length of a string.

**_What is the length of the string "Santa"?_**

 -**5**

**_Write a statement that prints the length of the string variable first_name._**

 -**print(len(first_name))**

- A programmer can access a character at a specific index by appending **brackets []** containing the index.

- 
