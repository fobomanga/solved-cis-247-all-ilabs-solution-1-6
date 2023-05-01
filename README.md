Download Link: https://assignmentchef.com/product/solved-cis-247-all-ilabs-solution-1-6
<br>
<p class="ui header product-top-header" title="CIS 247 All iLabs: Solution 1-6">CIS 247 All iLabs:

<strong>CIS247A iLab 1 of 6: Creating a User Interface</strong>

<strong> iLab 1 of 6: Creating a User Interface</strong>

Scenario and Summary

This program creates the basic user interface code that can be used in the following week’s iLab assignments. The assignment will help you get started using the programming environment and some practice with coding. You will also be able to reuse much, if not all, of the code in later assignments.

In this program, you will create the following methods:

DisplayApplicationInformation, which will provide the program user some basic information about the program. DisplayDivider, which will provide a meaningful output separator between different sections of the program output. GetInput, which is a generalized function that will prompt the user for a specific type of information, then return the string representation of the user input. TerminateApplication, which provides a program termination message and then terminates the application.

Using these methods, you will construct a program that prompts the user for the following:

your name, which will be a string data type; your age, which will be an integer data type; the gas mileage for your car, which will be a double data type; and  a display of the collected information.

Also, note that the program should contain a well-documented program header.

Deliverables

Step

Deliverable

Step 4

Screenshot of running program results

Step 5

Zip file with entire Lab files

Preparation:

If you are using the Citrix remote lab, follow the login instructions located in the iLab tab in Course Home. Locate the Microsoft Visual Studio icon and launch the program.

i L A B  S T E P S

STEP 1: Review the Design

Download the program description and puesdocode design, and make sure you fully understand the program design and ask any questions that you may have BEFORE you start programming.

Click Week 1 Lab Design to download program design.

STEP 2: Construct the Program

Start Microsoft Visual Studio and create a new project titled “CIS247C_WK1_Lab_LASTNAME”. Using the design, construct the methods. Once the methods are constructed, use the design to create the main program.

STEP 3: Compile and Test

When done, ensure that there are no compile errors. If there are errors, open up the Error list and fix all listed errors. Execute your code and check your output to ensure that you have the desired output. If you need to fix anything, close your execution window, modify your code as necessary, and rebuild.

STEP 4: Screen Prints

Capture the results of each test and paste them into a Word document. Below is a sample program output.

Screenshot of a program output that reads: Welcome to your first Object Oriented Program–Employee ClassCIS247C, Week 2 Lab Name: Prof.Nana Liu *************** Start Program *************** *************** Get Name *************** Please enter your nameNana Liu Your name is: Nana Liu *************** Get Age *************** Please enter your age100 Your age is: 100 *************** Get Mileage *************** Please enter your mileage52.16 Your car MPG is: 52.16 The end of the CIS247C Week1 iLab. Press any key to continue. . .

STEP 5: Submit Deliverables

Put all of the Project files into a zip file. Put the zip file, test plan, and screen shots (Word document) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

<strong>CIS247A iLab 2 of 7: Employee Class</strong>

General Questions – General General Questions

<strong>iLab 2 of 6: Employee Class</strong>

Scenario and Summary

We begin our investigation of object-oriented programming by creating an object-oriented program with a class called Employee. You will create two objects based on the Employee class, along with a class that contains the main method. The attributes, constructors, and methods for this class must satisfy the requirements in Steps 1 through 3. After you create the objects, you will prompt the user for information and then display it.

We will want to ensure that this first class is well-constructed and tested since we will extend this class in Labs 3 through 6.

Deliverables

Due this week:

Capture the Console output window and paste it into a Word document. Zip the project folder files. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Class Diagram

Use the following UML diagram to build the class. The first section specifies the attributes. The second section specifies the behaviors, and the first character specifies the access modifier value, where:

“-” means that the class member is private, and “+” means that the class member is public.

Employee – firstName : string – lastName : string – gender : char – dependents : int – annualSalary : double +Employee() +Employee(in first : string, in last : string, in gen : char, in dep : int, in salary : double) +calculatePay() : double +displayEmployee() : void +getFirstName() : string +setFirstName(in first : string) +getLastName() : string +setLastName(in last : string) +getGender() : char +setGender(in gen : char) +getDependents() : int +setDependents(in dep : int) +getAnnualSalary() : double +setAnnualSalary(in salary : double)

STEP 2: Code the Employee Class

Create a new project called “CIS247B_Week2Lab_YourName”. Using the provided Class Diagram from Step 1, code the Employee class in the new project (i.e., “Realize the UML Class diagrams”). The default constructor should set the attributes as follows: , , (for unknown), , and ,000. The multi-arg constructor should initialize all of the attributes using values passed in using its parameter list. As shown in the Class diagram, each attribute should have a “getter” to retrieve the stored attribute value, and a “setter” that modifies the value. The calculatePay( ) method of the Employee class should return the value of annual salary divided by 52 (return annualSalary / 52;). The displayEmployee() method should display all the attributes of the Employee object in a well-formatted string with logical labels applied to each attribute. Don’t forget to call calculatePay from within the displayEmployee method in order to display the Employee’s weekly pay as well!

STEP 3: Code the Main Program

In the Main class, create code statements that perform the following operations. Be sure you follow proper commenting and programming styles (header, indentation, line spacing, etc.).

Create an Employee object using the default constructor. Prompt for and then set the first name, last name, gender, dependents, and annual salary. (Remember that you have to convert gender, dependents, and annual salary from strings to the appropriate data type.) Using your code from last week, display a divider that contains the string “Employee Information” Format the currency using the following formatting services:

cout&lt;&lt;“Annual Salary:t” &lt;&lt; setprecision(2)&lt;&lt;showpoint&lt;&lt;fixed&lt;&lt;annualSalary &lt;&lt; “
”;

Display the Employee information. Create a second Employee object using the multi-argument constructor, setting each of the attributes with appropriate valid values. Using your code from last week, display a divider that contains the string “Employee Information”. Display the Employee information for the second Employee object.

STEP 4: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

STEP 5: Screen Prints

Capture the Console output window and paste into a Word document. The following is a sample screen.

Screenshot of a program output that reads: Welcome to your first Object Oriented Program–Employee ClassCIS247C, Week 2 Lab Name: Prof.Nana Liu *************** Employee 1 *************** Please enter your First Name Nana Please enter your Last Name Liu Please enter your Gender Female Please enter your Dependents 2 Please enter your Annual Salary 60000 Employee Information ___________________________________________ Name: Nana Liu Gender: F Dependents: 2 Annual Salary: 60000.00 Weekly Salary 1153.85 *************** Employee 2 *************** Name: Mary Noia Gender: F Dependents: 2 Annual Salary: 150000.00 Weekly Salary: 2884.62 The end of the CIS247C Week 1 iLab. Press any key to continue…

STEP 6: Submit Deliverables

Capture the Console output window and paste into a Word document. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

<strong>CIS247A iLab 3: Overloaded Methods and Static Methods / Variables</strong>

General Questions – General General Questions

<strong>iLab 3 of 6: Overloaded Methods and Static Methods / Variables </strong>

Scenario and Summary

The objective of the lab is to take the UML Class diagram and enhance last week’s Employee class by making the following changes:

Create a static variable called numEmployees that holds an int and initialize it to zero. This will allow us to count all the Employee objects created in the main class. Increment numEmployees in all of the constructors Add overloaded versions of setDependents and setAnnualSalary that accept strings. This way, we will have two “set” methods for both dependents and annual salary; one that accepts a string, and one that accepts its default data type.

Deliverables

Due this week:

Capture the Console output window and paste it into a Word document. Zip the project folder files. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Diagram

Employee – firstName : string – lastName : string – gender : char – dependents : int – annualSalary : double – static numEmployees : +Employee() +Employee(in fname : String, in lname : String, in gen : char, in dep : int, in sal : double) +calculatePay() : double +displayEmployee() : void +getFirstName() : String +setFirstName(in name : String) : void +getLastName() : String +setLastName(in name : String) : void +getGender() : char +setGender(in gen : char) : void +getDependents() : int +setDependents(in dep : int) : void +getAnnualSalary() : double +setAnnualSalary(in sal : double) : void +setAnnualSalary(in sal : String) : void

The following attribute has been added:

– static numEmployees: The following behaviors have been added:

+ static getNumEmployees( ) : int+ setDependents(in dep : String) : void+ setAnnualSalary(in sal : String) : void

STEP 2: Create the Project

You will want to use the Week 2 project as the starting point for the lab.

STEP 3: Modify the Employee

Using the UML Diagrams from Step 1, code the changes to the Employee class. Create a static numEmployees variable and initialize it to zero. Increment numEmployees by 1 in each of the constructors. Create an overloaded setDependents method and this time make the parameter a string. Create an overloaded setAnnualSalary method and this time make the parameter a string.Remember that you will have to convert the string in the above two “set” methods to the data type of the attribute. Make the getNumEmployees a static method. (This way, you can call it with the class name instead of an object name.)

Be sure you follow proper commenting and programming styles (indentation, line spacing, etc.).

STEP 4: Modify the Main Method

In the Main class, create code statements that perform the following operations. Be sure you follow proper commenting and programming styles (header, indentation, line spacing, etc.). Note that several of the steps below were accomplished in last week’s assignment. New steps are in bold.

Create an Employee object using the default constructor. Prompt for and then set the first name, last name, and gender. Consider using your getInput method from Week 1 to obtain data from the user for this step as well as Step 3. Prompt for and then set dependents and annual salary using the new overloaded setters. Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the Employee Information. Display the number of employees created using getNumEmployees. Remember to access getNumEmployees using the class name, not the Employee object. Create a second Employee object using the multi-arg constructor, setting each of the attributes with the following values: “Mary”, “Noia”, ‘F’, 5, 24000.0 Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the employee information for the second Employee object. Display the number of employees created using getNumEmployees. Remember to access getNumEmployees using the class name, not the Employee object.

STEP 5: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

STEP 6: Screen Prints

Capture the Console output window and paste it into a Word document. The following is a sample program output.

Screenshot of program that reads: ************** Employee 1 ************** Please enter your First Name Nana Please enter your Last Name Liu Please enter your Gender Female Please enter your Dependents 2 Please enter your Annual Salary 60000 Employee Information ________________________________________ Name: Nana Liu Gender: F Annual Salary: 60000.00 Weekly Salary: 1153.85 — Number of Employee Object Created — Number of employees: 1 ************** Employee 2 ************** Employee Information _______________________________________ Name: Mary Noia Gender: F Dependents: 2 Annual Salary: 150000.00 Weekly Salary: 2884.62 — Number of Employee Object Created — Number of employees: 2 The end of the CIS247C Week3 iLab. Press any key to continue…

STEP 7: Submit Deliverables

Capture the Console output window and paste it into a Word document. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

<strong>CIS247A iLab 4: Composition and Class Interfaces</strong>

General Questions – General General Questions

<strong>iLab 4 of 6: Composition and Class Interfaces/Abstract Class</strong>

Scenario and Summary

The objective of the lab is to modify the Employee class to demonstrate composition and a class interface. An employee typically has benefits, so we will make the following changes:

Create a Benefits class. Integrate the Benefit class into the Employee class. Create an iEmployee abstract class to guarantee that calculatePay is implemented in the Employee class. A tutorial on interfaces can be downloaded here.

Deliverables

Due this week:

Capture the Console output window and paste it into a Word document. Zip the project folder files. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Diagram

Employee – firstName : string – lastName : string – gender : char – dependents : int – annualSalary : double – static numEmployees : +benefit : Benefit +Employee() +Employee(in fname : String, in lname : String, in gen : char, in dep : int, in sal : double) +calculatePay() : double +displayEmployee() : void +static getNumEmployees() : int +getFirstName() : string +setFirstName(in name : String) : void +getLastName() : String +setLastName(in name : String) : void +getGender() : char +setGender(in gen : char) : void +getDependents() : int +setDependents(in dep : int) : void +getAnnualSalary() : double +setAnnualSalary(in sal : double) : void +setAnnualSalary(in sal : String) : void &lt;&lt;interface Fido : Animal +calculatePay() : double Benefit -healthinsurance : string -lifeinsurance : double -vacation : int +Benefit() +Benefit(in health : string, in life : double, in vacation : int) +displayBenefits() : void +getHealthInsurance() : string +setHealthInsutance(in hins : string) : void +getLifeInsurance() : double +setLifeInsurance(in lifeIns : double) : void +getVacation() : int +setVacation(in vaca : int) : void

The only change to the Employee class is that there is a new attribute:

+benefit : Benefit

Notice that there is a “+” for this attribute, meaning that it is public. Make sure to examine the multi-arg constructor’s signature!

Also, the dotted directed line between Employee and iEmployee specifies that the Employee class must implement the iEmployee abstract class, and thus provide an implementation for the calculatePay method.

STEP 2: Create the Project

You will want to use the Week 3 project as the starting point for the lab. To do this, you will want to create a new project by following these steps:

Create a new project and name it “CIS247C_WK4_Lab_LASTNAME”. Copy all the source files from the Week 3 project into the Week 4 project. Before you move on to the next step, build and execute the Week 4 project.

STEP 3: Modify the Employee Class

Using the UML Diagrams from Step 1, create the Benefit class. To get an idea of how to format displayBenefits, take a look at the output in Step 5. Add a Benefit attribute to the Employee class. Initialize the new Benefit attribute in both Employee constructors. Again, take note of the multi-arg constructors parameter list! Create the iEmployee interface (abstract class in C++). Modify the Employee class to implement the new interface so that Employee will have to implement the calculatePay method.

class Employee : public iEmployee

6.  Modify the Employee class to call displayBenefit when displaying Employee information.

STEP 4: Modify the Main Method

Notice that the Employee class now has a public benefit object inside it. This means that you can access the set methods of the Benefit object with the following code:

&lt;Employee object.benefit.&lt;method

As an example, to set the lifeInsurance attribute inside an Employee object called emp, we could execute the following code:

emp.benefit.setLifeInsurance(lifeInsurance);

The steps required to modify the Main class are below. New steps are in bold.

Create an Employee object using the default constructor. Prompt for and then set the first name, last name, and gender. Consider using your getInput method from Week 1 to obtain data from the user for this step as well as Step 3. Prompt for and then set the dependents and annual salary using the overloaded setters that accept Strings. Prompt for and set healthInsurance, lifeInsurance, and vacation. Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the Employee Information. Display the number of employees created using getNumEmployees(). Remember to access getNumEmployees using the class name, not the Employee object. Create a Benefit object called benefit1 using the multi-arg construction. Use any information you want for health insurance, life insurance, and vacation. Create another Employee object and use the constructor to fill it with the following:“Mary”, “Noia”, ‘F’, 5, 24000.0, benefit1 Using your code from Week 1, display a divider that contains the string “Employee Information”. Display the employee information. Display the number of employees created using getNumEmployees(). Remember to access getNumEmployees using the class name, not the Employee object.

STEP 5: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

STEP 6: Screen Prints

Capture the Console output window and paste it into a Word document. The following is a sample screen print.

Screenshot of program output that reads: CIS247CWeek4iLab’ CMD.EXE was started with the above path as the current directory. UNC paths are not supported. Defaulting to Windows directory. Welcome to your Object Oriented Program–Employee ClassCIS247C, Week 4 LabName: Prof.Nana Liu *************** Employee 1 *************** Please enter your First Name Nana Please enter your Last Name Liu Please enter your Gender Female Please enter your Dependents 2 Please enter your Annual Salary 60000 Please enter your Health InsuranceCigna Please enter your Life Insurance1.5 Please enter your Vacation Days21 Employee Information ________________________________________ Name: Nana Liu Gender: F Dependents: 2 Annual Salary: 60000.00 Weekly Salary: 1153.85 Benefit Information ________________________________________ Health Insurance: Cigna Life Insurance: 1.50 Vacation: 21 days — Number of Employee Object Created — Number of employees: 1 ************** Employee 2 ************** Employee Information _______________________________________ Name: Mary Noia Gender: F Dependents: 2 Annual Salary: 150000.00 Weekly Salary: 2884.62 Benefit Information _______________________________________ Health Insurance: North West Mutual Life Insurance: 5000000.00 Vacation: 14 days — Number of Employee Object Created — Number of employees: 2 The end of the CIS247C Week4 iLab. Press any key to continue…

STEP 7: Submit Deliverables

Capture the Console output window and paste it into a Word document. Put the zip file and screen shots (Word document that contains programming code and screen shots of program output) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

<strong>CIS247A iLab 5: Inheritance</strong>

General Questions – General General Questions

<strong>iLab 5 of 6: Inheritance</strong>

Scenario and Summary

The objective of the lab is to take the UML Class diagram and enhance last week’s Employee class by making the following changes:

Create a class called Salaried that is derived from Employee. Create a class called Hourly that is also derived from Employee. Override the base class calculatePay() method. Override the displayEmployee() method.

Deliverables

Due this week:

Capture the Console output window and paste into a Word document. Zip the project folder file. Put the zip file and screenshots (Word document) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Diagram

Notice the change in UML diagram. It is common practice to leave out the accessors and mutators (getters and setters) from UML class diagrams, since there can be so many of them. Unless otherwise specified, it is assumed that there is an accessor (getter) and a mutator (setter) for every class attribute.

Employee #firstName : string #lastName : string #gender : char #dependents : int #annualSalary : double #benefit : Benefit -static numEmployees : +Employee() +Employee(in fname : string, in lname : string, in gen : char, in dep : int, in benefits : Benefit) +static getNumEmployees() : int +CalculatePay() : double +displayEmployee() : void Benefit -healthinsurance : string -lifeinsurance : double -vacation : int +Benefit() +Benefit(in hins : string, in lins : double, in vac : int) +displayBenefits() : void Salaried -MIN_MANAGEMENT_LEVEL : -MAX_MANAGEMENT_LEVEL : -BONUS_PERCENT : -managementLevel : int +Salaried() +Salaried(in fname : string, in lname : string, in gen : char, in dep : int, in sal : double, in ben : Benefit, in manLevel : int) +Salaried(in sal : double, in manLevel : int) +CalculatePay() : double +displayEmployee() : void Hourly -MIN_WAGE : -MAX_WAGE : -MIN_HOURS : -MAX_HOURS: -wage : double -hours : double -category : string +Hourly() +Hourly(in wage : double, in hours : double, in category : string) +Hourly(in fname : string, in lname : string, in gen : char, in dep : int, in wage : double, in hours : double, in ben : Benefit, in category : string) +CalculatePay() : double +displayEmployee() : void

STEP 2: Create the Project

Create a new project and name it CIS247C_WK5_Lab_LASTNAME. Copy all the source files from the Week 4 project into the Week 5 project.

Before you move on to the next step, build and execute the Week 5 project.

STEP 3: Modify the Employee Class

Using the updated Employee class diagram, modify the attributes to be protected. Delete the iEmployee interface class, and remove the reference from the Employee class.

STEP 4: Create the Salaried Class

Using the UML Diagrams from Step 1, create the Salaried classes, ensuring to specify that the Salary class inherits from the Employee class. For each of the constructors listed in the Salaried class, ensure to invoke the appropriate base class constructor and pass the correct arguments to the base class constructor. This will initialize the protected attributes and update the numEmployees counter. The valid management levels are 0, 1, 2, and 3, and should be implemented as a constant. Override the calculatePay method to add a 10 percent bonus for each of the management levels (i.e., bonus * .10). The bonus percentage should be implemented as a constant. Override the displayEmployee() method to add the management level to the employee information.

STEP 5: Label Title

Using the UML Diagrams from Step 1, create the Hourly classes, ensuring to specify that the Hourly class inherits from the Employee class. For each of the constructors listed in the Hourly class, ensure to invoke the appropriate base class constructor and pass the correct arguments to the base class constructor. This will initialize the protected attributes and update the numEmployees counter. The valid category types are “temporary”, “part time”, and “full time”. The provided hours must be more than 0 hours and less than 50 hours, and the limits should be implemented as constants. The provided wage must be between 10 and 75, and the limits should be implemented as constants. Override the calculatePay method by multiplying the wages by the number of hours. Override the Employee setAnnualSalary method and set the annual salary by multiplying the weekly pay by 50. Override the displayEmployee() method to add the category to the hourly employee information.

STEP 6: Label Title

Using previous weeks’ assignments as an example, create at least one Employee, Hourly, and Salaried employee. For each object created, display the number of employees created. For each object created, write statements to exercise each of the public methods listed in the Class diagram. For each object created, invoke the object’s displayEmployee() method to display the employee’s information. For employee, the following information needs to be displayed:

Partial Sample output

Screenshot of program output that reads: Employee Information ________________________________________ Name: Nana Liu Gender: F Annual Salary: 60000.00 Weekly Salary: 1153.85 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 1.50 Vacation: 20 days — Number of Employee Object Created — Number of employees: 1

6.  For salaried employee, the following information needs to be displayed:

Partial Sample output

Screenshot of program output that reads: Name: Jackie Chan Gender: M Dependents: 1 Annual Salary: 50000.00 Weekly Salary: 1250.00 Benefit Information ________________________________________ Health Insurance: HMO Life Insurance: 100.00 Vacation: 16 days Salaried Employee Management Level: 3 — Number of Employee Object Created — Number of employees: 2

7.  For hourly employee, the following information needs to be displayed:

Partial Sample output

Screenshot of program output that reads: Name: James Bond Gender: M Dependents: 0 Annual Salary: 100000.00 Weekly Salary: 2000.00 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 5.00 Vacation: 17 days Hourly Employee Category: Unknown Wage: 40.00 Hours: 50.00 — Number of Employee Object Created — Number of employees: 3

STEP 7: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

Below is the complete sample program output for your reference.

Screenshot of program output that reads: ************** Employee 1 ************** Please enter your First Name Nana Please enter your Last Name Liu Please enter your Gender Female Please enter your Dependents 2 Please enter your Annual Salary 60000 Please enter your HealthInsurancePPO Please enter your LifeInsurance1.5 Please enter your Vacation Days20 Employee Information ________________________________________ Name: Nana Liu Gender: F Annual Salary: 60000.00 Weekly Salary: 1153.85 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 1.50 Vacation: 20 days — Number of Employee Object Created — Number of employees: 1 ************** Employee 2 ************** Please enter your First Name Jackie Please enter your Last Name Chan Please enter your Gender Male Please enter your Dependents 1 Please enter your HealthInsuranceHMO Please enter your LifeInsurance100 Please enter your Vacation Days16 Employee Information ________________________________________ Name: Jackie Chan Gender: M Dependents: 1 Annual Salary: 50000.00 Weekly Salary: 1250.00 Benefit Information ________________________________________ Health Insurance: HMO Life Insurance: 100.00 Vacation: 16 days Salaried Employee Management Level: 3 — Number of Employee Object Created — Number of employees: 2 *************** Employee 3 *************** Please enter your First Name James Please enter your Last Name Bond Please enter your Gender Male Please enter your Dependents 0 Please enter your Health InsurancePPO Please enter your Life InsurancePPO Please enter your Vacation Days17 Employee Information _______________________________________ Name: James Bond Gender: M Dependents: 0 Annual Salary: 100000.00 Weekly Salary: 2000.00 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 5.00 Vacation: 17 days Hourly Employee Category: Unknown Wage: 40.00 Hours: 50.00 — Number of Employee Object Created — Number of employees: 3 The end of the CIS247C Week 5 iLab. Press any key to continue…

STEP 8: Label Title

Capture the Console output window and paste into a Word document. Put the zip file and screenshots (Word document) in the Dropbox.

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information.

<strong>CIS247 iLab 6: Abstract Classes</strong>

General Questions – General General Questions

<strong>iLab 6 of 7: Abstract Class and Polymorphism </strong>

Scenario and Summary

We have two separate goals this week:

We are going to create an abstract Employee class and two pure virtual functions – calculatePay() and displayEmployee(). The abstract Employee class will prevent a programmer from creating an object based on Employee, however, a pointer can still be created. Objects based on Salaried and Hourly will be allowed. The pure virtual function calculatePay() in Employee will force the child classes to implement calculatePay(). The other pure virtual function displayEmployee() in Employee will force the child classes to implement displayEmployee(). We are going to implement Polymorphism and dynamic binding in this iLab.

Deliverables

Due this week:

Capture the Console output window and paste it into a Word document. Zip the project folder in the Microsoft Visual Studio. Put the zip file and screenshots (word document) in the Dropbox.

i L A B  S T E P S

STEP 1: Understand the UML Diagram

Notice in the updated UML diagram that the Employee class is designated as abstract by having the class name Employee italicized. Also, the calculatePay method is italicized, which means that it is a pure virtual function and needs to be implemented in the derived classes. In addition, make displayEmployee() method a pure virtual function as well.

Employee #firstName : string #lastName : string #gender : char #dependents : int #annualSalary : double #benefit : Benefit -static numEmployees : +Employee() +Employee(in fname : string, in lname : string, in gen : char, in dep : int, in benefits : Benefit) +static getNumEmployees() : int +CalculatePay() : double +displayEmployee() : void Benefit -healthinsurance : string -lifeinsurance : double -vacation : int +Benefit() +Benefit(in hins : string, in lins : double, in vac : int) +displayBenefits() : void Salaried -MIN_MANAGEMENT_LEVEL : -MAX_MANAGEMENT_LEVEL : -BONUS_PERCENT : -managementLevel : int +Salaried() +Salaried(in fname : string, in lname : string, in gen : char, in dep : int, in sal : double, in ben : Benefit, in manLevel : int) +Salaried(in sal : double, in manLevel : int) +CalculatePay() : double +displayEmployee() : void Hourly -MIN_WAGE : -MAX_WAGE : -MIN_HOURS : -MAX_HOURS: -wage : double -hours : double -category : string +Hourly() +Hourly(in wage : double, in hours : double, in category : string) +Hourly(in fname : string, in lname : string, in gen : char, in dep : int, in wage : double, in hours : double, in ben : Benefit, in category : string) +CalculatePay() : double +displayEmployee() : void

STEP 2: Create the Project

Create a new project and name it CIS247C_WK6_Lab_LASTNAME. Copy all the source files from the Week 5 project into the Week 6 project.

Before you move on to the next step, build and execute the Week 6 project.

STEP 3: Modify the Employee Class

Define calculatePay() as a pure virtual function. Define displayEmployee() as a pure virtual function. When class Employee contains two pure virtual functions, it becomes an abstract class.

STEP 4: Create Generalized Input Methods

Reuse method getInput() from the previous iLab to prompt the user to enter Employee information.

STEP 5: Modify the Main Method

Create two employee pointers with:

Employee * Salaried(10000,3); Employee * Hourly(50, 40, “full time”);

The first employee pointer refers to a salaried employee and the second employee pointer refers to a hourly employee.

Prompt the user to enter information for these two pointers and display the calculated result.

For salaried employee, the following information needs to be displayed:

Partial Sample Output:

Screenshot of program output that reads: Employee Information ________________________________________ Name: Nana Liu Gender: F Annual Salary: 60000.00 Weekly Salary: 1500.00 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 1.50 Vacation: 21 days Salaried Employee Management level: 3

For hourly employee, the following information needs to be displayed:

Partial Sample Output:

Screenshot of program output that reads: Name: Jackie Chan Gender: M Dependents: 1 Annual Salary: 100000.00 Weekly Salary: 2000.00 Benefit Information ________________________________________ Health Insurance: HMO Life Insurance: 100.00 Vacation: 18 days Hourly Employee Category: full time Wage: 50.00 Hours: 40.00

STEP 6: Compile and Test

When done, compile and run your code.

Then, debug any errors until your code is error-free.

Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild.

Below is a complete sample program output for your reference.

Screenshot of program output that reads: Welcome to your Object Oriented Program–Employee ClassCIS247C, Week 6 LabName: Prof.Nana Liu ************** Employee 1 ************** Please enter your First Name :Nana Please enter your Last Name :Liu Please enter your Gender :Female Please enter your Dependents :2 Please enter your Annual Salary :60000 Please enter your HealthInsurance:PPO Please enter your LifeInsurance:1.5 Please enter your Vacation Days:21 Employee Information ________________________________________ Name: Nana Liu Gender: F Dependents: 2 Annual Salary: 60000.00 Weekly Salary: 1500.00 Benefit Information ________________________________________ Health Insurance: PPO Life Insurance: 1.50 Vacation: 21 days Salaried Employee Management level: 3 ************** Employee 2 ************** Please enter your First Name :Jackie Please enter your Last Name :Chan Please enter your Gender :Male Please enter your Dependents :1 Please enter your HealthInsurance:HMO Please enter your LifeInsurance:100 Please enter your Vacation Days:18 Employee Information ________________________________________ Name: Jackie Chan Gender: M Dependents: 1 Annual Salary: 100000.00 Weekly Salary: 2000.00 Benefit Information ________________________________________ Health Insurance: HMO Life Insurance: 100.00 Vacation: 18 days Category: full time Wage: 50.00 Hours: 40.00 — Number of Employee Object Created — Number of employees: 2 The end of the CIS247C Week6 iLab. Press any key to continue…

STEP 7: Submit Deliverables

Submit your lab to the Dropbox located on the silver tab at the top of this page. For instructions on how to use the Dropbox, read these Step-by-Step Instructions or watch this  Dropbox Tutorial.

See Syllabus “Due Dates for Assignments &amp; Exams” for due date information