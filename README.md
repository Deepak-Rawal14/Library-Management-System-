# Library-Management-System
LMS
This project involves creating a library system in BlueJ that allows for the management of physical books and electronic resources in a library. The system will consist of several classes representing different entities in the library, including physical books, electronic resources, authors, library members, and library guests.

The PhysicalBook class will have data fields for the ISBN, title, author, library member, and a list of strings storing the damages for the book. The class will have getter and setter methods for all data fields, and a method to check if the book is available. The setter method for the damages list will append the value of its parameter to the end of the list. A method to print all the details of a book will also be included, with considerations for when the library member or author data fields are null.

The ElectronicResource class will have a boolean field indicating whether the resource can be downloaded and other relevant data fields. The class will have getter and setter methods for all data fields and a method to print all the details of an electronic resource.

The Author class will have data fields for the author's first name, surname, and address. The class will have getter and setter methods for all data fields and a method to print all the details of an author.

The LibraryMember class will have a data field for the library member ID number and a list of book objects currently borrowed by a library member. The class will have getter and setter methods for all data fields and methods to print all the details of a library member, add a book to the list of borrowed books, print the details of all books currently borrowed by a library member, and return the number of books currently borrowed by a library member.

The LibraryGuest class will have a data field for the duration of library access for a guest or visitor. The class will have getter and setter methods for all data fields.

The Library class will have a list of library resources, which can be physical books or electronic resources. The class will have getter and setter methods for all data fields and methods to print all the details of the library, check if the catalogue contains a resource object, edit the author's first name for a resource, search the catalogue by resource title, search the catalogue by author surname, remove a resource object from the library catalogue, and remove a resource object at a specific position in the library catalogue.

The project will be implemented using BlueJ, a Java-based integrated development environment (IDE) that is widely used for teaching and learning object-oriented programming. The project will involve creating classes and methods as specified in the requirements, and testing the functionality of each class and method using BlueJ's built-in testing tools. The project will also involve ensuring that the system is user-friendly and efficient for managing library resources.

Overall, this project will provide a comprehensive and efficient library management system that can be used by library staff and patrons to manage their books and electronic resources effectively. The system will also provide valuable insights into object-oriented programming concepts, such as inheritance, encapsulation, and polymorphism, which are fundamental to software development
