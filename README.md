# Project
A simple menu-driven console program to manage books in a library 

## Details
1. Persistent Storage of books
  - Data of books is save (when the system is ended with option 0/save and exit) in the books.txt file in root directory

2. Console options
  - Below is the available console options
    1. List all books
    2. Add a new book
    3. Edit an available book
    4. Search books by keyword in name
    5. Delete a book
    6. List all the books sort descending by price

## Continous Development/Changing Oppotunities
I tried to make it simple to change the console options in the future
It is very easy to add in runtime a new "optionId" for the console, e.g

> main.addCommand(1, new ListAllBooks(bookManager));

For further development, I suggest to add the ability of deleting console option :)

## Author
Thi Hai Yen, Nguyen
11.2021

Thank you for visiting this repository <3


