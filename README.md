# Library Management System (LMS) Assignment

## Objective:
The goal of this assignment is to design and implement a **Library Management System (LMS)** using **C++** that will manage books, patrons, and transactions in a flexible and scalable manner. You must follow object-oriented design principles to ensure maintainability and extensibility. The system should be capable of managing the core functionalities of a library while adhering to **SOLID principles** to create a well-structured, modular, and easily extendable system.

## Functional Requirements:
The system should provide the following core functionalities:

1. **Book Management**:
   - Ability to add new books to the system.
   - Ability to search for books by title or author.
   - Ability to update the details of a book (e.g., changing availability status).
   - Books should have properties like `title`, `author`, and `availability status`.

2. **Patron Management**:
   - Ability to add new patrons to the system.
   - Ability to search for patrons by name or ID.
   - Ability to update patron information (e.g., contact information).
   - Each patron should have properties like `name`, `contact information`, and a list of borrowed books.

3. **Transaction Management**:
   - Ability for a patron to borrow a book from the library.
   - Ability for a patron to return a borrowed book.
   - The system should handle the borrowing and returning of books, tracking which books have been borrowed and by which patron.
   - A borrowed book should be marked as unavailable until it is returned.
   
4. **Support for Multiple Transaction Types**:
   - The system should support the addition of new transaction types in the future (e.g., late fees, renewals, etc.) without modifying the existing code.

5. **Book and Patron Abstraction**:
   - The system should be designed such that books and patrons can be extended in the future (e.g., adding support for new types of books, like eBooks or audiobooks).

## Design Guidelines:
1. **Extensibility**:
   - The system should be open for future extensions but closed for modification. New functionality (such as handling late fees, adding new book formats, or transaction types) should be achievable by adding new components, not changing existing ones.

2. **Maintainability**:
   - Your design should be modular, with clear separation of concerns. Each module or component should handle a single aspect of the system's functionality (e.g., book management, patron management, transaction handling).

3. **Testability**:
   - The system should be designed in a way that individual components can be tested independently. Focus on ensuring that your design allows for easy unit testing.

4. **Flexibility**:
   - Your design should allow for the addition of new features without requiring significant changes to existing code. For example, you should be able to add new types of books (like eBooks, audiobooks) or different types of transactions (like late fee calculations) without modifying the core structure of the system.

## Non-Functional Requirements:
- **Performance**: The system should handle a reasonable number of books, patrons, and transactions efficiently.
- **Error Handling**: Ensure proper error handling for edge cases, such as borrowing an unavailable book or returning a book that is not borrowed.
- **Data Persistence**: For this assignment, data persistence is not mandatory, but you should be able to load and save the state of books and patrons in a simple data structure (e.g., an array or list) while the system is running.

## Design Considerations:
- The design should respect object-oriented principles and be easy to extend in the future.
- Ensure that all modules (book management, patron management, transaction management) can be easily modified or extended without disrupting other parts of the system.
- Use appropriate abstractions where necessary to hide implementation details (e.g., abstracting book and patron management behind interfaces).

## Submission Requirements:
1. **Implementation**: 
   - Implement the **Library Management System** based on the functional and design requirements outlined above.
   - Ensure the system is modular, testable, and adheres to object-oriented principles.

2. **Design Document**:
   - Provide a **Design Document** describing the architecture and components of your system. Include explanations of your design decisions, focusing on how you applied the **SOLID principles** and how the system supports **extensibility**, **maintainability**, and **modularity**.
   - The document should also explain how you have structured your classes and components and why you have chosen your design approach.

3. **UML Diagrams**:
   - Provide UML diagrams (class diagram, sequence diagram, etc.) to visually represent the relationships between the main components and the flow of transactions within the system.

4. **Test Cases**:
   - Write test cases to verify the functionality of your system. The test cases should cover typical use cases like borrowing and returning books, searching for books and patrons, and handling various edge cases.

5. **Code Quality**:
   - The code should be well-commented, clean, and organized. Use meaningful names for variables and functions, and ensure proper indentation.

## Evaluation Criteria:
1. **Correctness**: Does your system correctly implement the required functionality (book management, patron management, transaction handling)?
2. **Adherence to SOLID Principles**: How well does your design follow the SOLID principles? Is your system modular, scalable, and easy to maintain?
3. **Design Document**: Does the design document clearly explain your system's architecture, the design decisions made, and how the SOLID principles were applied?
4. **Code Quality**: Is your code clean, organized, and easy to understand? Is it free from redundant or unnecessary code?
5. **Test Coverage**: Have you written comprehensive tests that validate the system's functionality, including edge cases and error handling?
6. **Extensibility**: How easy is it to add new features (like different types of books or transactions) to the system without modifying existing code?

## Deadline:
The assignment is due by **[Insert Due Date]**. Late submissions will be penalized unless prior arrangements are made.

---

This assignment is intended to help you practice applying the principles of object-oriented design and SOLID principles in a real-world system. It will also improve your ability to write clean, maintainable, and extendable code that can easily adapt to future requirements.
