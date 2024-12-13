
1. Emmah Muchiri HDB212-0487/2023 
2. Otieno Godwins Joel HDB212-2129/2023 
3. Nellie Wangeci HDB212-2141/23 
4. Winter olali HDB212-0529/2023 
5. Mitchelle Wanga HDB212-0500/2023 
6. Adelbert ogeto HDB212-0507/2023
 7. Willington kutar. HDB212-0482/2023
 8. Emmanuel Owiti HDB212-0505/2023
 9. Ramsley Odhiambo HDB212-0527/2023 
10. Wills George HDB212-0517/2023 
11. Dennis Omondi HDB212-0511/2023 
12. Mike Clarence HDB212-2349/2023

C++ Object-Oriented Programming System
This project demonstrates the implementation of Object-Oriented Programming (OOP) concepts in C++ for a simple e-commerce system. The system includes functionalities such as product management, order creation, file I/O, exception handling, and user interaction through a command-line interface.

Table of Contents
Overview
Features
System Requirements
Installation Instructions
Compiling the Code
Running the Application
Usage Instructions
Error Handling
Credits
Overview
This software system models a basic e-commerce platform where:

Admin users can manage products (add/remove/list).
Customers can view products, place orders, and view their order history.
Order and product information is stored in a file for persistence.
The system demonstrates key OOP concepts:

Encapsulation
Inheritance
Polymorphism
Abstraction
Exception Handling
Features
User Management: Admin and Customer roles.
Product Management: Add, remove, and list products.
Order Management: Create and view orders.
File I/O: Persist order details in a file.
Error Handling: Graceful handling of invalid inputs and file-related errors.
System Requirements
Operating System: Windows, Linux, or macOS.
C++ Compiler: GCC 11 or higher, or equivalent.
IDE: Any C++ IDE (e.g., Visual Studio, Code::Blocks, CLion) or a text editor (e.g., VS Code) with GCC.
Libraries: Standard C++ libraries (iostream, fstream, vector, string, exception).
Installation Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/GN4-BBIT/GROUP-4/tree/778c1cc8060ba4ff557b84a2750bd3abc6c34eb2/E-commerce
Navigate to the Project Directory:

bash
Copy code
cd e-commerce-system
Compiling the Code
To compile the C++ code, follow these steps:

Using GCC (Command Line):
Open the terminal and navigate to the directory where your C++ files are located.

Compile the source code using the g++ compiler:



Using Visual Studio:
Open Visual Studio.
Create a new project and select "Console Application".
Add all the .cpp and .h files to your project.
Build the solution by clicking "Build Solution" in the toolbar.
Running the Application
After compiling the code, you can run the application:

On Command Line:
Navigate to the directory where the compiled file is located.
Run the executable:
bash
Copy code
./ecommerce_system
In Visual Studio:
Press Ctrl+F5 to run the program without debugging.
Usage Instructions
When the program runs, the user will be presented with a text-based menu. The options vary depending on whether you are logged in as an Admin or a Customer.

For Admin Users:
Add products
Remove products
List all products
View all orders
For Customer Users:
View available products
Place an order
View orders
Error Handling
The application includes error handling for common issues such as:

Invalid user input (e.g., entering a non-numeric value when selecting a product).
File I/O errors (e.g., unable to open a file).
Invalid operations (e.g., trying to remove a non-existing product).
If any error occurs, the system will display an appropriate message and allow the user to try again.

Credits
This project was developed as part of an Object-Oriented Programming assignment by Group 4 Group N BBIT. It demonstrates the use of key OOP principles and is designed for educational purposes.




