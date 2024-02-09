# Project on Banking Software
Repository for Project on Banking Software
<br>

INTRODUCTION

This project is aimed at developing Bank Management System for customers. The project has been planned to be having the view of distributed architecture, with centralized storage of the database. Data storage has been planned using the constructs of MySQL and all the user interfaces have been designed using JAVA.

Database Tables: The basic constructs of table spaces have been implemented in MySQL database to increase consistency and dependability for data storage. MySQL was selected for its reliability and easy retrieval of data.

Graphical User Interface: Java JDK 21 was used extensively for front-end development. Users are provided with a GUI in which they can choose from various options and can perform desired operations using self-explanatory menus.

PROBLEM STATEMENT

To create user-friendly software for a banking system. 

Why I choose this topic?

Project Management Skills: Managing a project involves setting timelines, allocating resources, and tracking progress. This experience introduced project management methodologies and tools, teaching me how to organize and execute a software project effectively.

Attention to Detail and Testing: Creating software for banking requires precision and accuracy. I learned the importance of thorough testing, quality assurance, and attention to detail to ensure that the software meets the standards.

Real-World Application of Knowledge: This project will bridge the gap between theoretical knowledge gained in classes and its practical implementation.

METHODOLOGY

1. Project requirements as well as industry standards should be kept in mind.

2. Choosing appropriate technologies like which programming language should be used, maintaining a database, providing framework, etc. 

3. Implementing modules and functions that provide most stability and make the software secure altogether.

4. Testing individual modules to ensure they function as intended.

TECHNOLOGY & REQUIREMENTS

Programming Language: JAVA

Front-end Development: JAVA JDK 21 (Apache NetBeans IDE)

Back-end Development: MySQL (Database)

WORKING OF BANKING MODULE

Login Class: User opens the Login window and enters the account number and PIN. If "LOG IN" is clicked, the entered account number and PIN are checked against the login table in the database.

Sign Up Class: User opens the Signup window and enters personal details. Data validation is performed, and if valid, the details are inserted into the signup table of the database.

Main Class: User logs in and is presented with various transaction options such as Deposit, Withdrawal, Loan Enquiry, etc. Upon selection, the corresponding class is instantiated.

WORKING OF LOAN MANAGEMENT SYSTEM

Loan Enquiry Class: This class represents the main loan application form. The form includes personal details, and users can select their loan type.

Vehicle Loan Class: This class handles the details for Vehicle Loans, including loan requirements and fixed rate of interest and monthly EMIs.

Home Loan Class: This class manages Home Loan applications, including loan amount and duration of repayment and monthly EMIs.

Personal Loan Class: This class handles Personal Loan applications, including loan amount and duration of repayment and monthly EMIs.

CONNECTING DATABASE

Establishing Connection: The primary purpose of this class is to establish a connection to a MySQL database using the DriverManager.getConnection() method.

Database Connection URL: The database connection URL is specified as"jdbc:mysql://localhost:3306/bankingSystem," indicating the local MySQL server on port 3306 and the "bankingSystem" database.

CONCLUSION

Technologies and Specifications: As specified in the methodology, MySQL Database was used for the back end, JAVA JDK Version 21 using Apache NetBeans for front-end development. The program’s step-by-step operation encompasses a range of classes, including Balance Enquiry, Deposit, Loan Enquiry, etc.

Structured Approach: This methodology guarantees a structured approach by offering a clear road map for the software development process. The objectives of developing a seamless and effective banking software solution are met by the utilization of database connectivity, data validation and user-friendly interfaces.

FUTURE IMPROVEMENTS

Enhanced Security Features: Specific security features like encryption, secure authentication, and cyber threat protection are yet to be implemented.

Scalability Planning: Assessing the project's ability to handle increased users, transactions, and data without compromising performance is crucial.

Mobile Application Integration: Considering the increasing popularity of mobile banking, creating a mobile application will provide convenience for users.

User Interface Enhancements: Making constant improvements to the user interface for bank personnel and clients based on user feedback.

Process Automation: Automating standard banking procedures to increase productivity, transaction accuracy and lower manual error rates.

Regular Maintenance & Updates: Creating a schedule for routine updates to keep the software up to date with new developments in technology and to fix any security issues that may arise.
