![todo jpeg](https://github.com/user-attachments/assets/e02f1bf0-a7ef-4286-9102-775686733793)

## Passport Management System in C
A simple console-based passport management system built in C. This program allows users to create, list, and delete passport records, storing the data in a binary file. It demonstrates basic file handling and CRUD operations in C.

## Features
List Passports: View all stored passport details.
Create Passport: Input and store a new passport's details, including name, email, passport number, and date of birth.
Delete Passport: Remove a passport from the system using its unique ID.
File Management: All data is stored in a binary file (Data.dat), and operations are performed using file I/O functions in C.
Program Structure
main() function starts the program and presents the main menu.
passportList() displays all stored passports in a formatted list.
createPassport() allows the user to input new passport details and saves them to a file.
deletePassport() removes a passport entry by copying non-matching records to a temporary file.
footerMenu() provides navigation options after each action is completed.
Prerequisites
To run this program, you need:

A C compiler (e.g., GCC).
Basic knowledge of C programming, especially file handling and user input.
Installation
Clone the repository:

## bash
Copy code
git clone https://github.com/[your-username]/passport-management-system.git
cd passport-management-system
Compile the program:

bash
Copy code
gcc passport_management.c -o passport_management
Run the program:

bash
Copy code
./passport_management
Usage
Upon running the program, you'll see a menu offering options to:

## List all passports.
Create a new passport.
Delete an existing passport.
Example
Creating a new passport:

Enter the full name, email address, and date of birth (DD-MM-YYYY).
The system generates a unique passport number and stores the information in the file.
Deleting a passport:

Enter the passport ID, and the corresponding record will be removed from the system.
File Structure
Data.dat: The binary file where passport records are stored.
passport_management.c: The main source file containing all program logic.
Contributing
Contributions are welcome! If you'd like to enhance this project:

## Fork the repository.
Create a new branch.
Make your changes and submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.
