# Employee Payroll Management System

A Java-based desktop application designed to automate employee salary calculation and payslip generation. The project demonstrates the practical implementation of Object-Oriented Programming concepts using Java Swing and PDF generation.

## 📌 Overview

The Employee Payroll Management System simplifies payroll processing by allowing an administrator to enter employee details and automatically calculate gross salary, deductions, and net salary.

The system supports two employee categories:

* Permanent Employees
* Contractual Employees

The application provides a graphical user interface built with Java Swing and generates structured payslips for employee records.

## ✨ Features

* Employee ID and name input
* Basic salary entry
* Permanent and Contractual employee selection
* Automated gross salary calculation
* Automated deduction calculation
* Net salary calculation
* Interactive Java Swing GUI
* Payslip generation
* PDF-based digital documentation
* Input validation
* Clear/reset functionality

## 🛠️ Technologies Used

| Technology                         | Purpose                   |
| ---------------------------------- | ------------------------- |
| Java                               | Core programming language |
| Java Swing                         | Graphical User Interface  |
| OOP                                | Application architecture  |
| iText / OpenPDF                    | PDF payslip generation    |
| VS Code / IntelliJ IDEA / NetBeans | Development environment   |

## 🧠 OOP Concepts Demonstrated

The project focuses on applying important Object-Oriented Programming concepts:

### Abstraction

An abstract `Employee` class provides common employee attributes and behaviour.

### Inheritance

`PermanentEmployee` and `ContractEmployee` inherit common functionality from the `Employee` class.

### Encapsulation

Employee-related data and operations are organized within classes.

### Polymorphism

Different employee types implement their own salary calculation logic while being handled through the common employee structure.

## 💰 Salary Calculation

### Permanent Employee

```text
Gross Salary = Basic Salary + HRA + DA
Deductions = PF + Tax
Net Salary = Gross Salary - Deductions
```

### Contractual Employee

```text
Gross Salary = Basic Salary + Allowance
Deductions = Tax
Net Salary = Gross Salary - Deductions
```

## 🏗️ System Architecture

```text
                    Employee Payroll System
                              |
                 +------------+------------+
                 |                         |
             Java Swing               Payroll Logic
                 |                         |
        Employee Information        Employee Class
                 |                         |
                 |              +----------+----------+
                 |              |                     |
                 |       PermanentEmployee     ContractEmployee
                 |              |                     |
                 +--------------+---------------------+
                                |
                         Salary Calculation
                                |
                         Payslip Generation
                                |
                           PDF Document
```

## 🖥️ Application Workflow

1. Launch the application.
2. Enter the employee ID.
3. Enter the employee name.
4. Enter the basic salary.
5. Select the employee type.
6. Generate the payslip.
7. The system calculates gross salary, deductions, and net salary.
8. Payslip information is displayed in the GUI.
9. The payslip can be generated as a PDF.

## 📂 Project Structure

```text
employee-payroll-management-system/
│
├── src/
│   ├── Employee.java
│   ├── PermanentEmployee.java
│   ├── ContractEmployee.java
│   └── PayrollModernUI.java
│
├── screenshots/
│   └── payroll-system.png
│
├── README.md
└── LICENSE
```

> Update the file names above according to the actual files in your GitHub repository.

## 🎯 Project Objectives

* Develop an object-oriented payroll management system using Java.
* Automate salary calculations for different employee categories.
* Build a user-friendly desktop GUI using Java Swing.
* Generate digital payslips.
* Demonstrate real-world applications of OOP concepts.

## 🚀 Future Improvements

The current project can be extended with:

* MySQL or SQLite database integration
* Employee record management
* Admin/HR authentication
* Employee search and update functionality
* Payroll history
* Cloud-based storage
* Multi-user access
* Improved PDF reporting
* Monthly/yearly payroll reports

## 📊 Current Limitations

* Desktop-based application
* No database connectivity in the current implementation
* No authentication system
* No cloud synchronization

## 👨‍💻 Team

**Jatoth Sravani**
**Vankalla Sai Lalitha Raam**
**Mandaram Bhanu Prakash**

Developed as a Course End Project for Object-Oriented Programming Laboratory.

## 📚 References

* Java Documentation
* Java Swing Documentation
* iText PDF Library
* OpenPDF Documentation

## ⭐ If you found this project useful

Consider giving the repository a ⭐ and exploring the project.

