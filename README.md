# Library Management System with Student and Teacher Access

This project is a C++ based library management system that grants different access levels to students and teachers for managing library resources.

## Overview

The system allows two types of users - students and teachers - to perform various library-related operations:

### Student Access
- Search for books by title, author, or ISBN
- Check out books
- Return books
- View borrowed books and due dates

### Teacher Access
- Perform all student functions
- Add new books to the library inventory
- Remove books from the inventory
- View all available books

## Features

- **User Authentication**: Differentiates between students and teachers based on login credentials.
- **Book Management**: Enables adding, removing, and searching for books.
- **Checkout and Return**: Allows users to borrow and return books.
- **Due Date Tracking**: Keeps track of borrowed books and their due dates.

## Installation

### Prerequisites
- C++ Compiler (Supporting C++11 or later)
- Standard Template Library (STL)

### Steps to Compile and Run
1. Clone the repository: `git clone https://github.com/yourusername/library-management.git`
2. Navigate to the project directory: `cd library-management`
3. Compile the code: `g++ -std=c++11 main.cpp -o library`
4. Run the program: `./library`

## Usage

Upon running the program, users will be prompted to log in with their respective credentials (student/teacher). After authentication, they will have access to their functionalities based on their user type.

### Student Functions
1. Search for a book
2. Check out a book
3. Return a book
4. Display borrowed books

### Teacher Functions
1. Search for a book
2. Check out a book
3. Return a book
4. Display borrowed books
5. Add a book
6. Remove a book
7. Display available books

## Contributing

Contributions are welcomed! If you encounter any issues or have suggestions for enhancements, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
