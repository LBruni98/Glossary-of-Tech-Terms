# Glossary-of-Tech-Terms

## These are terms that are used within project development

### Scrumdown Terms
1. Burn-Down Chart

A chart that shows the amount of work that remains. Time is represented on the x-axis and the amount of work on the y-axis. The chart is a means to communicate unfinished work from either sprint or product backlogs.

2. Sprint

An event that usually consists of 30 days or less, with work being carried out consecutively and without gaps.

3. Stakeholder

A peron with interest within the project and actively engaged with the scrum team.
  
4. Velocity

An optional, but often used, indication of the average amount of Product Backlog turned into an Increment of product during a Sprint by a Scrum Team, tracked by the Development Team for use within the Scrum Team.

5. Product Backlog

An ordered list of the work to be done in order to create, maintain and sustain a product. Managed by the Product Owner.
  
6. Development Team

The role within a Scrum Team accountable for managing, organizing and doing all development work.
  
7. Increment

Piece of working software that adds to previously created Increments, where the sum of all Increments -as a whole - form a product.
  
8. Forecast

Items from the product backlog deemed feasible for implementation by the development team.
  
9. Sprint Planning

Time-boxed event of 8 hours, or less, to start a Sprint. It serves for the Scrum Team to inspect the work from the Product Backlog that’s most valuable to be done next and design that work into Sprint backlog.
  
10. Sprint Review

An event after the sprint that takes around 4 hours or less to conclude the work in a sprint and to inspect the product of a sprint.

### Programming Terms
#### 1. Algorithm

A process followed in caluclations or other solutions, run mainly by a computer.

#### 2. Paradigms
##### Procedural
This paradigm is based on the concept of procedures or methods; sequences of commands to be executed. Procedures are mainly used in larger projects, used by many programming languages and have the following benefits:
  - Reusability of code designed as procedures
  - Ease of following the logic
  - Maintainability

###### Characteristics
A procedure is a sequence of activities that are followed within a program to perform a frequently used operation. Procedural paradigms act on if something is needed, putting more importance on the things to be done and have their own scope and inputs/outputs, making them act like smaller programs. Modern programming languages are built on the principles of procedural paradigms.

##### Object Oriented
This paradigm is based on objects that contain data in fields, rather than actions and logic. Both functions and data make up an object and can be inherited from other objects the programmer creates. 

###### Characteristics
Rather than procedure, its more orientated on its own data. Objects created will be used by it to implement data and these objects can communicate through functions. Enscapsulation is also present in this paradigm, where data is manipulated into a single unit, protecting it from external interference and misuse, which in languages like java are supported by classes and objects

##### Event Driven
This paradigm allows for the program to react towards user input. Specific inputs such as clicking on a button or typing in text and used for different functions to operate.

###### Characteristics
This paradigm is reliant on event handlers, a type of function that runs a certain action once a specific event is triggered. This paradigm is mainly visual, which ensures simplicity and ease of development. It's service orientated as well, meaning that it takes very little of the computer's processing power as to not slow down the computer and has services available on a network ensuring the code does not need to be rewritten each time.

##### 2.1 Relationships Between Paradigms
Each paradigm is more towards creation in order to create a full program, but each are different in how they function. The Procedural paradigm creates procedures, functions that run in order to create a program without being provoked and event-driven paradigms also create these features. The difference between the two here are that procedural paradigms are created and run instantaneously, whereas event-driven paradigms only run once an event has occurred, such as a click of a mouse or button.
The object-oriented paradigm mainly creates objects via classes compared to the other two paradigms where they create functions. The objects created are used mainly to solve soultions, objects communicate via functions to help achieve the solution rather than relying on an event.

#### Process of Implementation
The way to successfully implement this algorithm is to go at the tasks individually and that way, the whole process is ordered and each task can be fully realized.

The first step to creating the program is to plan out what the initial steps for development; outlining the user stories and creating flowcharts and pseudo-code of the program, generally to understand how it will work and its layout.

Next is to find the IDE and programming language applicable for the program; what will help with the development and what would best suit the program.

Then would be to take the stories and create the program in accordance to the user stories laid out in planning. The program takes shape here and not developing is easier, rather than approaching the program in a huge epic. Along with easier development through individual tasks, the user can also test every individual part for easier testing and can easily understand the structure of the code.

#### Coding Standards
Coding Standards are a set of guidelines for a developer to follow in order to create high quality code. These guidelines help a developer write in a specific way that best suits that language. It works because developers would have written in their own style when others would write their code in a different style; different indentation, naming of functions and commenting. If in a workplace environment, setting a standard for coders would help, so to improve readability of the code and helps with editing and modifying.

#### IDE
An IDE (Integrated Development Environment) is an application that provides a user with tools for writing up and testing software.

![IDE](https://github.com/LBruni98/Glossary-of-Tech-Terms/blob/master/Capture.PNG)

##### Analysis
A common feature that an IDE has is something called syntax highlighting. What this does is that it provides a colour scheme to support readibility and writing of the code, to differentiate the categories in a programming language that the IDE supports, with colours for variables, conditional statements, strings, comments, etc.

Another feature that is common in most IDEs are libraries. These allow for pre-set code already organized in blocks to be used or re-used to reduce development time, rather than writing all the code in a single block, being unorganized and time consuming.

A code editor or shell is included for the user to write, edit and save code documents. These editors also provide the user with quintessential tools to help them with writing; auto-completion where the program interprets what you may write; syntax checking, highlighting any errors and checking for any incorrect syntax use; and bracket matching, inputing any brackets where the user may have missed any and improving readibility of the code.

##### Comparison of IDEs and Non-IDE Software
An IDE is essentially a useful and easier method of writing and developing software no matter the language. It has a variety of features that can aid a developer in creating software, depending on the IDE in question. Writing a program without an IDE, such as a normal text editor, will only make the development harder and more time consuming, not to mention more problems arising and bugs being harder to fix. The benefits of IDEs outweigh using non-IDE alternatives that there is technically no reason to develop without having an IDE.

In IDEs, formatting tools such as syntax highlighting, auto completing and bracket matching are prevalent in almost every IDE avaliable, increasing readability of the code being written and making it easier for others, including the user, to understand. In IDEs, these features can aid in creation of code, with code structure being made automatically and defining the functions easier, whereas non-IDE software, don't include these functions, having the user to organise the lines and structure the code for readibility themselves.

IDEs and non-IDE software see both usage with more experienced programmers; using IDEs by enhancing their work or taking advantage of the features and using non-IDE software as they would get a suitable grasp of a chosen language or would even prefer the lack of features if they were to interfere with their work.

#### Debugging Process and Debugging Facilities
Debugging is a very useful tool when it comes to finalizing a program and making it both stable and accessible to the public. Debugging works by reading through the lines of code and from error codes delivered to the IDE's console, the developer can use these codes to generally see where the mistakes and problems are. IDE's can offer limited to advanced debuggers with a handful of tools, but most often than not, they would result to an actual debugger, different to an IDE as the tools can assist in tracking variables and breaking down code.

For programs, this means that the initial program can be mended quicker rather than looking at every individual line of code or just relying solely on error codes. This may be fine for smaller projects but debugging can help with larger projects, even for complex programs.

The debugging process begins when the code the user writes is completed and is continued in stages, being combined with other pieces of code and the product coming together. Errors are detected once the code is run through a computer program, mainly an IDE and once it has been identified, then it is necessary to track down the error in the code. Looking at a logger mainly is a good way of finding the code and using either a standalone debugger or the IDE's built in debugger to track when and where the bug strikes and use said debugger to assist in fixing the bug. The bugs are fixed along with assessing that no newer bugs have appeared.

##### Debugging Tools
* Console - The console is another feature in most common IEs that allows input/output and interaction of a program. When executed the program tends to run here. If an error is present, instead of not executing, an error will be written out. What makes the console helpful for finding errors is that line number will be revealed as to where said error is occurring and will note down what could be a possible cause, such as missing characters or undefined variables

* Step into - This executes the code one line at a time and checks each line as if it were "stepping into" the code, no matter what functions step in and out of.

* Step out - This tool executes the remaining lines of code in a function and breaks when the return function has been completed. This works in tandem with the step in tool

* Changing variable values - Some IDE debuggers allow you to change the values of variables. This is to test how the program handles a setting or speed through a loop. Because it is done in real time, it saves time than having to stop and restart the debugging process.

* Realtime editing - In some IDEs, you can also edit code while the program is running, allowing the developer to view real time results that they can change on the fly. It saves alot of time and allows for experimentation of different solutions at any time during debugging.

