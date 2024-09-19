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

> # Each print statement starts on a new line
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

- 



  
