CODE DESCRIPTION
Description of how the code works :-
The code is based on c++
I have used file handling to enable file storage in the system.
The code is based on regex header file 
It accepts few constraints depending on the requirement of the assignment.
It has three functions :
ADD – Insert a new contact in the phonebook
SHOW  - displays all the contacts in the phonebook 
REMOVE – Deletes a contact from the phonebook.
The regex command is used for name and contact input validation
If any of the two is invalid the code exits, giving a 0 output
Else returns 1
NOT WORKING INPUT:
the code is not accepting O’malley jhon F. -type as a valid input
But rest all are accepted.

Compilation Instructions
Install visual studio version 15.1
Open developer command prompt.
Set path of the destination folder 
Compile the code with this command  cl /EHsc pragya_8488.cpp
Run the code with this command  pragya_8488

ASSUMPTIONS MADE:
The assignment description are the assumptions made while deciding the regex syntax
Another assumption is that “I haven’t taken wrong choice as an input, i.e. when program asks “do you want to enter more” the user has either y or Y as input; anything else will result in termination of code”


 PROS/CONS:
Pro: A txt file is created in your system as a database record
Cons: the txt file is not that much effective for display as it might disturb the indentation.
	The code is a bit complex and can be reduced
