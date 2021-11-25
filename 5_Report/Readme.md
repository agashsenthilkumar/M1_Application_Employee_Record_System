# Requirement
## Introduction
Employee Record System is software designed to manage a company's primary housekeeping responsibilities. ERS assists businesses in keeping track of all personnel and their data. It's utilised to run the business with the help of a computerised system. This software was created to manage the records of any company's employees. It will assist businesses in keeping track of all of their employees' records in a single file. Employee Record System is software designed to manage a company's primary housekeeping responsibilities. ERS assists businesses in keeping track of all personnel and their data. It's utilised to run the business with the help of a computerised system. This software was created to manage the records of any company's employees.It will assist businesses in keeping track of all of their employees' records in a single file.You can list the employees' records here, but you can't search them like you can in other C projects. Try changing this project and implementing the search feature with your own code. This project is finished and free of errors.                                                                                                                                                                            Aim of the Employee’s Record System: The user will be provided with 5 options Add a
new record.
Delete a record.
Modify a record.
View all the records.
Exit.                                                                                                                                                                            Data of the Employees:Name,Age,Salary,Employee ID.
## Research
The problem definition for developing the system is to keep employee data, make employee management easy, split jobs and control employee access, and use technology for accurate and quick processing while maintaining full privacy and authority access. The project's goal is to create an employee information system that tracks employee status, attendance, and the monthly salary process and delivery. To eliminate or diminish the disadvantages of the current system as much as feasible, and to avoid data entry errors.In existing method employee management are employeerecord are maintaining in records. It’s a manual process.Complicated to search the employee salaryNeeds for extra manual effort.In existing system is standalone process normal employee cannot track their employee status.Less Accuracy Danger of losing some files. Certain required report is not available Timeconsuming process.
## FEATURE
Employee Record System is software designed to manage a company's primary housekeeping responsibilities. ERS assists businesses in keeping track of all personnel and their data. It's utilised to run the business with the help of a computerised system. This software was created to manage the records of any company's employees.
## SWOT ANALYSIS
 All functions will be available in switch scenarios. The objective is to use File Handling techniques to write data to a text file and to read the data as well. In the same folder, we must also include a data.txt file.The name of the application and the developer are displayed in the first frame: It's made up of few printf statements and a predefined system function (). The C/C++ standard library includes the system() function. It is used to pass commands that can be executed in the operating system's command processor or terminal, and then it returns the command once it has been completed. The colour of the console, i.e. background (3), and the text on the console, i.e. foreground, will be changed by system("Color 3F") (F).system("pause") will pause the screen and display the following message to the user: To continue, press any key...The gotoxy() function will aid in the setting of the presented data's coordinates. Switch Case: The required function will be executed based on the user's input in the switch cases. The code is developed using simple file management techniques such as opening, closing, writing in, and reading files, among others.
## WHO
Human resources managers (HRM) have a wide range of responsibilities inside a business, since they safeguard both the employer and employee's interests. They manage employee relations for firms and look for ways to reduce labour costs.Establish explicit regulations and processes, as well as job descriptions for each employee. Review the material with your employees to ensure that they understand your expectations, the repercussions for breaking workplace rules, and your commitment to consistently and fairly enforcing the rules.
## WHAT
 Employee managementis a Web based application that works within a centralized networkis a method for assisting your employees in reaching their full potential and achieving your company's objectives. It's a comprehensive process that encompasses practically all aspects of human resources, including new hire recruitment, payroll management, performance management, and more.
 ## WHEN
 This project presents a review on the software program "Employee Management " as should be used in a company to manage the records of employee, ... You've visited this page 2 times. Last visit: 17/11/21.
 ## WHERE
 EMS aids in the elimination of the manual procedure, saving both time and money. This system safeguards the professional and personal information of employees and the firm. HR and business managers are relieved of their burdens and pressures thanks to the personnel management system.
 ## HOW
 For storing the data of the employee, create a user define datatype which will store the information regarding Employee.For building the employee table the idea is to use the array of the above struct datatype which will use to store the information regarding employee.Since we are using array to store the data, therefore to delete the data at any index shift all the data at that index by 1 and delete the last data of the array by decreasing the size of array by 1.For searching in the record based on any parameter, the idea is to traverse the data and if at any index the value parameters matches with the record stored, print all the information of that employee.
## Detail requirements
## High Level Requirements
PC with Pentium IV processor.
512 MB RAM or above.
40 GB Hard Disk or above.
## Low level Requirements
Operating system : Windows XP (or latest).
Front end : C Runtime
Platform : C sting

## DESGIN
## Structure Daigram
### Components Daigram
![st1 drawio](https://user-images.githubusercontent.com/94293980/143192282-d437be0c-e81b-440e-afe7-49de294f33a3.png)
## Behaviour Diagram
### Activity Daigram
![BD1](https://user-images.githubusercontent.com/94293980/143193848-333e2c6e-95eb-4656-be24-6e4173819708.jpg)
### Data Diagram
![bh2](https://user-images.githubusercontent.com/94293980/143193841-c8a95575-6e09-49fd-9585-96b0292afe93.jpg)

## Implementation
## Manual
### Setup to run Project
An integrated development environment (Suggesting Visual Studio Code). 
GCC compiler to compile the project.
"make" to run the Makefile smoothly.

### Steps To run Project
1.First clone the repository from the Github.
2.Open the repository in an IDE (Suggesting Visual Studio Code).
3.The next step is to build the project with the help of make command :- make all
4.Next step is to run the project with help of make command :- make run
5.If you want to run the test cases then run the following command:- make test
6.Clean all executable files by following command :- make clean

## TEST PLAN
## Table no: High level test plan

| **Test ID** | **Description**                      | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------|------------ |-------------|----------------|------------------|
|  H_01       |Adding new employee data to record    |Employee data|SUCESS       |SUCESS          |PASS              |
|  H_02       |Deleting new employee data form record|Name         |SUCESS       |SUCESS          |PASS              |
|  H_03       |Modify new employee data from record  |Name/new data|NEW DATA     |NEW DATA        |PASS              |

## Table no: Low level test plan

| **Test ID** | **Description**                    | **Exp IN**  | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|------------------------------------|-------------|-------------|----------------|------------------|
|  L_01       |Display all employee data to record |Choice case  |Display data |Display data    |PASS              |
|  L_02       |Modify the error data in record     |Correct data |Display data |Display data    |PASS              |
