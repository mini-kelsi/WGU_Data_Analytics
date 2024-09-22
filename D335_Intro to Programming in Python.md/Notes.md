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

