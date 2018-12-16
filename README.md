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

Text editor: A text editor is where the source code is written, this can provide the developer will tools, such as syntax highlighting, to make it easier to write code. 

Preprocessor: This is not part of the compiler, but is in the compilation process. It is a text substitution tool and it commands the compiler to do the necessary pre processing before the actual compilation begins. 

Compiler: This is a software program that changes high-level source code into low level object code (or binary code) in machine language, this is so it can be understood by the processor. It translate the code from one language to another without changing the meaning. 

Linker: In high level languages, some built in header files or libraires are stored. These predefined libraires have basic functions which are very important for executing the program. The functions are connected to the libraries by a program called linker.

Loader: This is a program which loads machine codes of a program into the system memory. This is the part which is in charge for loading programs. 


**Interpreter** : In an interpreter the program is translated one at a time. The program continues to translate the code until the first error is met, in which case it stops. 

This is how a program is executed in relation to an interpreter:

1. Parse the source code and perform its behavior directly

Parsing is the process of analysing a string of symbols, this can be either in natural language, computer languages or data structures

2. Then the source code is translated into some efficient intermediate representation and it is immediately executed


3. Explicitly execute the stored precompiled code produced by a compiler which is part of the interpreter system


#  Examine  the  implementation  of  an  algorithm  in  a  suitable  language.  Evaluate  the  relationship  between  the  written algorithm  and the code variant

![Flowchart](https://i.imgur.com/qjTRYkp.png)


Code: https://github.com/Ahm15275097/High-and-Low-/blob/master/Code.cpp







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


# Using an IDE vs Not using an IDE

An integrated development environment supplies the user with various tools to help with creating and developing code. This report will be about the following projects, 'Traceball', which was created in notepad without the use of an IDE, and 'HighorLow', which was create in repli.it with the use of an IDE. 

Traceball  : https://github.com/Ahm15275097/Traceball/blob/master/code.html

HighandLow : https://github.com/Ahm15275097/High-and-Low-/blob/master/Code.cpp


When a program is in development and an IDE isn't in use, various problems can arise. The lack of assistance when coding slows down the completion time dramatically. For example, the absence of syntax highlighting causes alot of time proofreading and making sure that functions and variables are spelt correctly. This was so that no unexpected errors and bugs were found when the program was executed. Traceball, due to it being much more difficult and more proofreading done took much longer to create than HighandLow. In repl.it everything was made so much easier, the code was understood better as every was categorised and there were no issues with syntax.
Testing for the highandlow game was quick and easy as all that needed to be done was click a button. This was the benefit of using repl.it, as it was accessible more tests were done to make sure there weren't any errors and this allowed the flow of the programing to be better. To test the Traceball game, the file needed to  be saved with a .html extension. Then it had to be run in a browser which supported javascript, this was very time consuming and stopped the flow of programming.The debugging was also alot better with the use of an IDE. Finding a bug and solving it was very efficient as if something went wrong a command line would inform the developer straight away. On the Traceball project if something had gone wrong, the developer would have to go back to a previous file to see what they added and what caused the problem. 





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

The debugging process helps remove bugs and faults throughout the development of the application. Taking away faults and errors from an application will lower the chance that a flaw will be found in an application. This will make the application more robust as the chance of the application failing would masssively reduce. This is because errors and faults lead to an application being less resilient, users with bad intentions will target the system. 

In the debugging process, bugs can be purposely produced. This will allow the error to be understood from an attacker's perspective,enabling tests to be done against high level threats. Doing tests such as these allows the developer to see if the application works as they would like it to. The developer can also see how well their application reacts to threats and if any more improvements could me made. This would make the application more secure.


# Critically evaluate why a coding standard is necessary in a team as well as for the individual.

Coding standards are essential to having a well written program, this is so that when it is read by others it can be clearly understood. This is more important in a team when everyone needs to follow the same standards so that there won't be any unexpected errors. 

When a group project is assigned, everybody will work on the same program but will work on there own set tasks. No matter how the tasks are distributed it is vital that the coding standards are followed by each individual. Coding standards will help the team write up the code in the same format so the way the code is presented and looks remains consistant. For example, if 2 group members like to indent the code in certain parts of the program, for example after new functions have been created, and the other don't, the format of the code will look untidy and will make the work unprofessional. Coding standards ensure that everyone is together and there are no differences in code format. 

Coding standards are also important for when an idividual writes a piece of code. For example when trying to find errors and debugging, if the code is well written and is presented well, it will be easier to find bugs. Also when revisting code, it will be better understood, if the developer hasn't senn this piece of code in a long it can be easily understood if the coding standards were adhered to/. 














