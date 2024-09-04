How to run this program:
Compile all files and then run ConsoleApp.class.
   
Program Overview:
This program utilizes a customSet to ensure that names and numbers are unique. If a duplicate name or number is encountered, it throws custom exceptions.

Menu Options:
Add Subscriber: This function adds a subscriber whose phone number matches the specified format at the start of the program.

Delete Subscriber: Removes a subscriber if they exist and their number is in the correct format.

Append Multiple Numbers: This function adds multiple numbers to an existing subscriber if the subscriber exists and the new numbers meet the format requirements.

Append Number: This function adds a single number to an existing subscriber if the subscriber exists and the new number matches the format.

Update Subscriber Numbers: This function replaces a subscriber's numbers with new ones, ensuring the new numbers follow the specified format.

Search by Name: Searches for a subscriber by name with logarithmic time complexity.

Search by Number: This function finds and returns a subscriber's name by their phone number if they exist.

Display All Subscribers: Prints all subscribers in the phonebook.

Exit: Closes the program.
