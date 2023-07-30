# 🚀 Java-Term-Projects Challenge

These three projects are exercises aimed at solidifying the basics of java (object-oriented).
##  Project 1: 💰 Family Budgeting Software
> This software is mainly to simulate the realization of a family budget software based on a text interface, familiar with the basic syntax of Java, and master the use of basic data types, loop statements, branch statements, method invocation and return value receiving, and simple screen output format control.

🪴 It mainly involves the following knowledge points: 

    1.  Local variables and basic data types
    2.  Loop statements
    3.  Branch statement
    4.  Method invocation and receipt of return values
    5.  Simple screen output format control

##  Project 2:  📚  Library Information Management Software

> Simulate the realization of a "Library Information Management Software" based on a text interface, familiar with object-oriented programming and debugging skills, and master the use of classes, objects, arrays, and MVC design pattern.

the structure of the project is as follows:

```
BookView
|--> Book: An entity object used to encapsulate book information.
|--> BookList: A management module for Book objects. It internally manages an array of Book objects and provides corresponding methods for adding, modifying, deleting, and traversing the objects, which are called by BookView.
|--> BookView: A user interface display module responsible for handling interface logic. It displays menus, receives user input, and calls the relevant methods of BookList.
|--> BookTest: The main class of the program, which is responsible for starting the program and creating the BookView object.

```


🪴It mainly involves the following knowledge points:

    1. Using the Class Structure: Properties, Methods, and Constructors
    2. Object creation and use
    3. class encapsulation
    4. Declaring and using arrays
    5. Insertion, deletion and replacement of arrays
    6. Use of the keyword: this


##  **Project 3:  👩🏻‍💻   Development team personnel scheduling system**

The Team Management System is a Java-based application that provides functionalities to manage a development team. The system allows users to add, remove, and view team members, handle team member assignments, and manage their equipment. It is designed to be a flexible and extensible system for managing various types of team members, such as Programmers, Designers, and Architects, along with their respective equipment.

🪴It mainly involves the following knowledge points:

    1.  Class inheritance
    2.  Polymorphism
    3.  Abstract class
    4.  Interface
    5.  Exception handling
    6.  File read and write
    7.  MVC design pattern

### Modules:
The peoject is orgnaized into three modules: Domain, Service, and View.

Domain: 
> The Domain module defines the core entities and their properties in the team management system. It includes the following classes:

- |--> **Employee**: Represents the basic information of a team member, including their ID, name, age, and salary.
- |--> **Programmer**: Extends Employee and adds additional properties specific to programmers, such as a member ID, status, and equipment.
- |--> **Designer**: Extends Programmer and adds an additional bonus field specific to designers.
- |--> **Architect**: Extends Designer and includes a stock field specific to architects.
- |-->**Equipment**: Represents the equipment used by team members and includes subclasses like PC, MAC, and Printer.
- |--> **PC**: Extends Equipment and adds additional properties specific to PCs, such as model and display.

- |--> **MAC**: Extends Equipment and adds additional properties specific to MACs, such as model and color.

- |--> **Printer**: Extends Equipment and adds additional properties specific to printers, such as type and name.

Service:
> The Service module provides the core business logic of the team management system. It includes the following classes:

  |--> **TeamData**: A management module for Employee objects. It internally manages an array of Employee objects and provides corresponding methods for adding, modifying, deleting, and traversing the objects, which are called by TeamView.
  |--> **TeamListService**: A user interface display module responsible for handling interface logic. It displays menus, receives user input, and calls the relevant methods of TeamData.
  |--> **TeamService**: The main class of the program, which is responsible for starting the program and creating the TeamView object.
  |--> **TeamStatus**: An enumeration class that defines the status of a team member.
  |--> **TeamException**: A custom exception class that defines exceptions that may occur in the team management system.

View:
> The View module provides the user interface for the team management system. It includes the following classes:

  |--> **TeamView**: A user interface display module responsible for handling interface logic. It displays menus, receives user input, and calls the relevant methods of TeamListService.
  |--> **TSUtility**: A utility class that provides methods for reading user input and displaying menus.

JUnit Test:
> The JUnit Test module provides unit tests for the team management system. It includes the following classes:

  |--> **TeamServiceTest**: A unit test class for the TeamService class.
  |--> **TeamViewTest**: A unit test class for the TeamView class.
  |--> **TeamDataTest**: A unit test class for the TeamData class.
  |--> **TeamListServiceTest**: A unit test class for the TeamListService class.
  |--> **TeamExceptionTest**: A unit test class for the TeamException class.

