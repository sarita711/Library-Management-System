## 1. Instructions on How to Run the Program

a. Download and Extract the ZIP File:
b. Open the Project in an IDE:
c. Compile the project to check for any errors.
d. Locate the LibraryManager class which contains the main method.
e. Run this class to start the console-based application.
f. Follow the on-screen instructions to add, remove, search, and list books in the library.

## Getting Started  - Library Management System
This project is a simple Library Management System developed using Java. It demonstrates the application of Object-Oriented Programming (OOP) concepts, SOLID principles, and basic design patterns. The system allows users to manage a collection of books and eBooks through a console-based application.
## features
    1.Add new books and eBooks to the library.
    2.Remove books based on ISBN.
    3.Search for books by title.
    4.List all available books in the library.
    5.Display the download size for eBooks.
    6.Demonstrate the use of Singleton and Factory design patterns.
## Classes and Design
   1. Book Class
      Attributes: title, author, isbn, available
      Methods: Constructor, getters, setters, toString()
    2. Library Class
       Attributes: List of Book objects
       Methods: addBook(), removeBookByIsbn(), searchBookByTitle(), listAllBooks()
    3. EBook Subclass
       Attributes: Inherits from Book, additional fileSize
       Methods: Constructor, getters, setters, toString()
    4. LibraryManager Class
       Attributes: Singleton instance, Library object
       Methods: displayMenu(), main()
    5. BookFactory Class
       Methods: createBook()


## Design patterns

   1.Singleton Pattern: Ensures only one instance of LibraryManager exists.
   2.Factory Pattern: BookFactory class to create Book or EBook objects based on input parameters.

## how to run

  1. Compile the Java files:
            javac Book.java Library.java EBook.java LibraryManager.java BookFactory.java
  2. run the libraryManager:
        java LibraryManager

## key feature and enhancements
  1.Encapsulation: 
             All attributes are private and accessed via getters and setters.
  2.Inheritance: 
             EBook class extends Book class.
  3.Polymorphism: 
             toString() method is overridden in EBook class.
  4.Single Responsibility Principle (SRP): 
             Each class has a single responsibility.
  5.Open/Closed Principle (OCP): 
             The system is open for extension (e.g., adding EBook) but closed for modification.
  6.Singleton Pattern: 
             Ensures a single instance of LibraryManager.
  7.Factory Pattern: 
             Simplifies object creation and promotes loose coupling.


## Conclusion
This project demonstrates the application of OOP principles, SOLID principles, and design patterns in building a simple yet effective Library Management System. It provides a solid foundation for further enhancements and real-world applications.




## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
