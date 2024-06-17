# Phone Directory

This is a simple phone directory program written in C that allows users to add, display, and search for contacts. The program stores contacts in a fixed-size array and provides a menu-driven interface for user interaction.

## Features

- **Add Contact**: Add a new contact with a name and phone number.
- **Display Contacts**: Display all contacts stored in the directory.
- **Search Contact**: Search for a contact by name.

## Getting Started

### Prerequisites

Make sure you have a C compiler installed on your system. You can use GCC, which is commonly available on many platforms.

### Compiling the Program

To compile the program, navigate to the directory containing `PhoneDirectory.c` and run the following command:


gcc -o PhoneDirectory PhoneDirectory.c

### Running the Program
After compiling, you can run the program using the following command:

./PhoneDirectory

## Usage
Upon running the program, the program will display a menu with options to perform various operations:

Add Contact: Enter the name and phone number of the contact you want to add to the directory.

Display Contacts: View all contacts currently stored in the phone directory.

Search Contact: Enter a name to search for a specific contact by name.

Exit: Exit the program.

Example
Here's an example of how the program can be used:

Adding a Contact:

mathematica
Copy code
Phone Directory Menu:
1. Add Contact
2. Display Contacts
3. Search Contact
4. Exit
Enter your choice: 1

Enter name: John Doe
Enter phone number: 1234567890
Contact added successfully!
Displaying Contacts:

mathematica
Copy code
Phone Directory Menu:
1. Add Contact
2. Display Contacts
3. Search Contact
4. Exit
Enter your choice: 2

Phone Directory:
Name: John Doe, Phone: 1234567890
Searching for a Contact:

mathematica
Copy code
Phone Directory Menu:
1. Add Contact
2. Display Contacts
3. Search Contact
4. Exit
Enter your choice: 3

Enter name to search: Jane Smith
Contact not found.
Exiting the Program:

mathematica
Copy code
Phone Directory Menu:
1. Add Contact
2. Display Contacts
3. Search Contact
4. Exit
Enter your choice: 4

Exiting...

## Contributing
Contributions to enhance this program or add new features are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

This README provides a brief overview of the PhoneDirectory.c program, its features, usage instructions, and guidance for contributing to the project. It helps users understand how to interact with the program effectively and encourages further development and improvement.
