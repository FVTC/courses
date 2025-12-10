---
title: Exam 3 - Practical
subtitle: C# Intermediate Programming
hideNav: false

live: https://fvtc.software/fvtc/exams/cs-inter-practical3-12.10.25
repository: https://github.com/fvtc/courses
---

# Exam 3 - Practical

Your goal for this exam is to finish a payroll application. The application will allow a user to view, update, insert, and delete payroll information from a SQL Server database.

## Provided Resources

1. Payroll.sql - This script will create the table structure needed for the application. The table includes the following fields:

- ID (int, primary key, identity)
- EmployeeID (int)
- CheckNumber (int)
- PayrollDate (datetime)
- CheckAmount (decimal)
- HoursWorked (decimal)

Additionally, the script will insert some sample data into the table. Re-execute this script in Visual Studio to recreate the table and data.

2. Starter Project (FVTC.Payroll) - A Visual Studio solution is provided with a Windows Forms Application. The project includes a completed Windows Forms UI, completed Persistence Layer, and an incomplete Business Layer. The Business Layer is where you will implement the required functionality.

The following parts of the application are completed, and should not be modified:

- The UI and PL are fully implemented and functional.
- All project references are correctly set up.
- All of the classes that are needed for the application are already created.
- Some todo comments are provided in the Business Layer to guide you on where to implement functionality. Use the Task List in Visual Studio to easily navigate to these comments.

## Instructions

1. Create and setup the database.
2. Download and extract the starter project from Blackboard.
3. Open the solution in Visual Studio.
4. Implement the required functionality in the Business Layer.

## Submission

Push up your completed project to Azure DevOps and submit the URL to Blackboard.




