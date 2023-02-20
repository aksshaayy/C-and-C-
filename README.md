# PROBLEM STATEMENT
#1) Write a C program, keeping following details in mind:
      i.  Use structure to store details of employee such as Name, Employee ID, Experience and Salary. 
      ii. Store details of 5 employees and then print them.




# CODE DETAILS 

In this program, we define a structure called Employee that contains four members: name, employeeId, experience, and salary. We then declare a variable of type Employee called employee in the main function.

We use scanf to get the employee details from the user and store them in the employee variable. We then print the employee details using printf.

we use '&' to get the address of the employeeId, experience, and salary variables when using scanf because these variables are not arrays. However, we don't need to use '&' with name because name is an array and the name of an array is a pointer to its first element.
