### Programming (General)



- A computer **program** consists of instructions executing one at a time. Basic instruction types are:
  
   - *Input*: A program recieves data from a file, keyboard, touchscree, network, etc.
     
   - *Process*: A program performs computations on that data, such as adding two values like x + y.
     
   - *Output*: A program puts that data somewhere, such as a file, screen, or  network.

- Programs use **variables** to refer to data, like x,y, and z.

------------------------------------
### Q&A

Which instruction completes the program to compute a triangle's area?

base = Get next input
height = Get next input
Assign x with base * height



Put x to output

 > Multiple x by 1/2



Which instruction completes the programing to compute the average of three numbers?

x = Get next input
y = Get next input
z = Get next input



Put a to output

> a = (x+y+z)/3

--------------------------------------

- **Computational Thinking** - creating a sequence of instructions to solve a problem
  
- **Algorithm** - a sequence of instructions that solves a problem
  
- **Python Interpreter** - a computer program that executes code written in the Python programming language.
  
- **Interactive Interpreter** - a program that allows the user to execute one line of code at a time.
  
- **Code** - a common word for the textual representation of a program.
  
- **line** - a row of text
  
- The interactive interpreter displays a **prompt**(">>>") that indicates the interpreter is ready to accept code.

- **Statement** - a program instruction that mostly consists of a series of statements, and each statment usualy appears on its own line.
  
- **Expressions** are code that return a value when evaluated
  
- **Variables** - named referenced to values stored by the interpreter.
  
- A new variable is created by performing an **assignment**.
  
- **print()** function displays variables or expression values.

- Characters such as "#" denote **commments**, which are optional but can be used to explain portions of code to a human reader.

-------------------------------------------
### Q&A

What is the purpose of variables?

> To store values for later use.



The code 20 * 40 is an expression.

> True
>> Expressions are code that yield a value when evaluated.



How are most Python programs developed?

> By writing code in files.
>> The Python interpreter can load and execute Python code saved in files.



Comments are required in a program.

 > False

------------------------------

- Text enclosed in quotes is known as a **sting**

---------------------------------
### Q&A

*Select the line that will print the given string. If none of the options are valid, select N/A.*

Welcome!

>print('Welcome!')



Password is: BaNaNa123

>print('Password is: BaNaNa123')

--------------------------------
### Q&A

*What's the output of the code?*

num_wheels = 4
print(num_wheels)

>4


num_wheels = 4
print('Number of wheels:', num_wheels)

> Number of wheels: 4



num_wheels = 4
vehicle_typle = 'pickup truck'
print('A', vehicle_type, 'has', num_wheels, 'wheels')

> A pickup truck has 4 wheels

--------------------------

- Output can be moved to the next line using the **newline character** "\n"

- An **escape sequence** is a string that has a special meaning, like the newline character "\n", that always starts with a backslash.

- Any space, tabe, or newline is called **whitespace**

- The **input()** function is used to read input form a user.

- A **type** determines how a value can behave. Strings and integers are each an example of a type.

- The **int()** function can be used to convert that string to the integer 123.

- A **syntax error** violates a programming language's rules on how symbols can be combined to create a program.

- **Runtime Error** - a program's syntax is correct but the porgam attemtps an impossible operation, such as dividing by zero or multiplying strings together.

- A runtime error halts the execution of the porgram. Abrupt and unintended terminationn of a program is often called a **crash** of the program.

<img width="865" height="355" alt="image" src="https://github.com/user-attachments/assets/6cdd6739-1c8c-4bd2-876a-633906f3c0bf" />

<img width="929" height="260" alt="image" src="https://github.com/user-attachments/assets/3ce0fb07-d494-4645-a753-8d448379b02d" />

- **Logic error** - program would load correctly but would not behave as intended

- A logic error is often called a **bug**.

- **Itegrated Development Environment (IDE)** is software that integrates a text editor and a Python interpreter, often with additional tools.

----------------------------------
### Q&A

Which software is necessary when programming either with or without an IDE?

> Text editor and Python interpreter
>> A programmer uses a text editor to create the source file and a Python interpreter to run the source file. Thus, an IDE must include a text editor and Python interpreter at minimum.



Which of the following is an advantage of using an IDE?

> Fewer steps are needed when running a porgram using an IDE.
>> An IDE provides the ability to rapidly run code. Without an IDE, a programmer must manually run the source file in a Python interpreter. An IDE usually provides a shortcut button that automatically runs a Python program.

---------------------------

- **Syntax highlighting** uses different colors for keywords, variables, strings, and other code syntax elements. Syntax highlighting can halep a programmer identify errors such as unclosed quotes and parentheses. missing colons, and misspellings.

- **Automatic delimiter completion** adds a mathcing closing auotation mark, parenthesis, bracket, or brace when a corresponding opening symbold is typed, which can hlep errors be more easily identified.

-----------------------------
### Q&A

What is syntax highlighting?

> Appearance of different code elements in different colors

In the animation above, the porgrammer was was able to identify an error because of the wrong colors in the following line of code.

print("Salary is, wage * 40 * 52)

Use syntax highlighting to identify the error.

> A quotation mark is missing.
>> the color of the code after the word "is" is the same color as the color of "Salary is", indication that everything after the first quotation mark is being treated aas part of a string literal. The programmer forgot to add a closing quotation mark between "is" and the comma.

In the animation above, the programmer switched to edit a different file by clicking a different filename in the file manager pane. How else could the programmer have switched between files?

> by clicking the tabs along the top of the text editor
>> Open files appear in tabs above the code window. Clickin on a tabe switches the code window to view or edit the selected file.

---------------------------------

- A **Console** (or **terminal**) is a text-based interface that allows a user to run programs, enter input, and view program output.

- A console's **command-line interface** (**CLI**) is an interface that allows a user to enter commands to run programs and work with files.
  - One advantage is the ability to run a program with command-line arguments.
 
- **Command-line argument** is a value entered by a user after the program name when running a program name when running a program from a command line.

---------------------
### Q&A

Which of the following is displayed in a console?

> Both input and output
>> Both a program's output and the user's input to the program appear on the console. A programmer must examine a program carefully to distinguish between output from a print statement and input entered by the user.


In the following command, what are the command-line arguments?

python3 main.py 0.5 25

> main.py 0.5 25
>> python3 is the executable program name, and pain.py 0.5 25 are specific command-line arguments that change how python3 runs. different executable programs accept different command-line arguements.


What is the advantage of running a program through a CLI in an IDE?

> A CLI allows a program to easily be run with arguments.
>> The CLI allows a program to be run with command-line arguments, which can be used to change how the porgram runs. Without a CLI, any arguments for the program must be pre-specified by editiing IDE-specific configurations.

----------------------------------

- Circuits called **processors** were created to porcess a list or desired calculations, each called an **instruction**.

- A **memory** is a circuit that can store 0s and 1s in each of a a series of thousands of addressed locations, like a series of addressed mailbosses that each


