# Definition of what an algorithm is and outlining the process in building an application

A programming algorithm is a step by step guide that a computer is required to follow to find a solution or meet a goal. There are many instances where algorithms are used, data processing, calculation and other related computer and mathematical operations all need algorithms.

1. Receiving a set of requirements from a client or coming up with your own set of requirements
2. Understanding what the requirements are
3. Choosing a software lifecycle methodology to follow
4. The design process can take place next
   - An algorithm would be created
   - Research of the application can be done
        
        Who the target audience are?
        
        Looking at existing solutions and see what improvements can be made
        
               
        
   - Brainstorm solutions to meet requirements
        
        The team can look at the aesthetics of the application
        
        How the user would interact with the application
        
        
   - Choose a solution that best fits the requirements 
5. Implementation of the application can take place
   - What programming language can be used?
   - What IDE will be used?
   - Start developing the application 
   - Based on the software lifecycle chosen a prototype will be created
6. Then some internal testing can be done
7. Buliding of the application will start
8. The team will then test & refine continuously until they are happy with the application 
9. They will then give the application to the client
7. Lastly, some maintenance can take place

# Determine the steps taken from writing code to execution.

These are the steps which need to be taken from writing the code to the code being executed.

Preprocessor: This is not part of the compiler, but is in the compilation process. It is a text substitution tool and it commands the compiler to do the necessary pre processing before the actual compilation begins. 

Compiler: This is a software program that changes high-level source code into low level object code (or binary code) in machine language, this is so it can be understood by the processor. It translate the code from one language to another without changing the meaning. 

Linker: In high level languages, some built in header files or libraires are stored. These predefined libraires have basic functions which are very important for executing the program. The functions are connected to the libraries by a program called linker.

Loader: This is a program which loads machine codes of a program into the system memory. This is the part which is in charge for loading programs. 



# Give explanations of what procedural, object orientated and event driven paradigms are; their characteristics and the relationship between them.

**Procedural programming**

Procedural programming is a paradigm that is based upon the thought of procedure calls, this is when statements are structured into procedures, this can also be called sub routines or functions. 

This type of paradigm has predefined variables local variables, global variables, programming libraries.

Local variable: Variables can only be accessed in the specific block of code not the entire script of code

Global variable: Variable that can be seen throughout the entire program, this can be done by every other procedure taking place 

Programming libraires: Gives permission to the variable values to be pass through the program which will control it with a procedure


            srand(time(NULL));
            cout << "This is the first number: ";
            int randomNumber1(rand() % 10 + 1);
            cout << randomNumber1 << endl; 



**Object orientated**

This is a programming paradigm which is built around objects not actions and data rather than logic. A program which has a logical procedure receives input from data, processes it and produces output. 

Characteristics of object oriented programming:

Encapsulation : This is the idea of capturing data and storing it safely and securely from outside interfaces

Inheritance   : This is where a class can be derived from a base class, it has all the elements from a base class and some of its own 

Polymorphism  : This is the power to live in various forms. An operator can be overloaded to add two integer numbers and two floats

![](https://i.imgur.com/9hqyOLW.png)

**Event driven programming**

Event driven programming is a paradigm which is subject to events like user actions, this could be mouse clicks or key presses. This paradigm is very useful in GUI's and other applications such as games. The traceball game which was created was an event driven program because it requires mousemovement. 

https://github.com/Ahm15275097/Traceball/blob/master/code.html

![example](https://i.imgur.com/CQBseRE.png)

Event handlers: The function or method will be executed in response to an action taking place, for example a key being pressed or the mouse being moved. 

Trigger functions: These are functions that decide which piece of code is executed when a certain event occurs

![](https://i.imgur.com/84SmQSp.png)

# Analyse the common features that a developer has access to in an IDE

In an IDE a developer has many tools to help them write code quickly and efficiently. Below are just some features which a developer has access to. 

Code completion: An IDE has the ability to know a language's keywords and functions which makes it easier to code. This can be used to do tasks such as highlight errors, suggest a list of available functions based on a certain situation or give a function's definition from the official documentation.

Syntax highlighting: This features displays the code in different colours and fonts, this is in according to which category it belongs to. This is integrated to help make the code more readable, this can be more of an assistance for large pieces of code. This makes it more easier to find what they are looking for.

Resource management: languages often depend on specific resources like library or header files to be at a certain locations. IDE ought to have the capability to manage these resources. The IDE should be aware of any required resources so that errors can be found early in the development stage not in the compile or build stage. 

Compile and build:  IDEs translate code from  languages to the object code(code that is produced by the compiler) of the platform. Requirements for these features vary substantially from language to language. Normally, an IDE specialises in one language or a set of similar languages. 

Debugging: IDE's also have an internal debugger, the developer can use this tool to see if there are any errors in the code. The debugger can help the developer clear any faults if they are present. The debugging process is mentioned below along with debugging facilities in the IDE.




# Explain  the  debugging  process and explain  the debugging  facilities  available  in  the  IDE. 

This is the process in which bugs and erros are found and removed within computer programs. This is handled in a sequential manner by debugging tools. 

**Debugging process**

Gather information on the error: If there are error's in the code it will terminate as soon as the user would like to run the run the program. information is given on the error and the user will take all the information to help them fix the problem.

Isolate source of the bug: This part of the process is to search for which part of the program is causing the error. Iterative testing is used in this part of the process. Iterative testing can help the debugger find where the error is occuring.

Identify the cause of the bug: This step requires finding the actal cause of the bug. Here the developer is finding out why the bug exists. A trained debugger can isolate where the error has come from, but someone who is more expereinced can be more accurate and identify the actual cause of the error. 

Determine fix for bug: From finding out the location of the bug and the cause of the bug, the developer can can now come up with an appropriate fix for this error. 

Fix and test: Now that the devloper has come up with a solution, the fix should be implemented and tested to see if that has solved the problem.


**Debugging facilities**

The IDE gives the user a debugging tab in its application, this application has different tools in the drop down menu. For example, jdeveloper by oracle, this allows the developer to set break points in the code. These break points allow the developer to examine variables, step forward line by line and show code as it executes. Also in python IDE, after the program has been run and a error was found, Python will tell the developer on what line and where on that line the error has occured.

![breakpoint type](https://i.imgur.com/jvvWSRn.png)

# Evaluate how the debugging process can be used to help develop more secure, robust applications. 

Programs go through alot of  testing, updating, troubleshooting and maintenance. Faults and errors are normally present in software, but this is easily removed. In this process, complete software programs are regularly compiled and executed to see if issues can be found and rectified. Large software programs, which contain millions of source code lines, are divided into small components. For efficiency, each component is debugged separately at first, followed by the program as a whole.

The debugging process helps remove bugs and faults throughout the development of the application.  











