# Cookie Jar

## Description
The Cookie Jar is a Python program that simulates a cookie jar with a limited storage capacity. 
It allows users to deposit and withdraw cookies while keeping track of the current number of cookies in the jar. 
The program uses object-oriented programming to manage the jar's capacity and contents.

## Tools and Languages
- **Python:** Programming language used to develop the application.
- **Visual Studio Code:** Code editor used to write and run the program.
- **Pytest:** Python testing framework used to create and execute automated tests.

## Features
- **Cookie Storage:** Keeps track of the number of cookies currently in the jar.
- **Capacity Limit:** Sets a maximum number of cookies the jar can hold.
- **Deposit Cookies:** Allows users to add cookies without exceeding the jar's capacity.
- **Withdraw Cookies:** Allows users to remove cookies without withdrawing more than the jar contains.
- **Cookie Display:** Uses the `__str__` method to display the cookies as emojis.
- **Error Handling:** Raises ValueError exceptions when invalid operations are attempted.
- **Automated Testing:** Uses pytest to test initialization, cookie deposits, withdrawals, and string representation.

## What I Built
I developed a Cookie Jar program using Python and object-oriented programming. 
I created a Jar class with methods to manage cookie storage, capacity, deposits, and withdrawals. 
I also implemented properties to access the jar's capacity and current size.
Additionally, I created a separate test file using pytest to verify that the program works correctly, including testing invalid operations and capacity restrictions.
