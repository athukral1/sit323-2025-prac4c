# sit323-2025-prac4c

Tech Stack: 
•	GitHub
•	Visual Studio
•	Node.js

Code Overview:
In addition to listening on port 3000, this Express-based Node.js server offers a number of mathematical operations via several API endpoints, such as /add, /subtract, /multiply, /divide, /exponentiate, /sqrt, and /modulo. Numerical parameters n1 and n2 are extracted from the query string by the server, which then verifies that they are there and that they are legitimate integers before processing incoming requests. It returns a 400 error with the relevant message if invalid values are found. Every mathematical operation, including division by zero and the square root of a negative number, is handled by a distinct function that handles computations and any exceptions. The server replies with a 500 error and an error message if there is an execution error. A welcome message is displayed on the root endpoint /, which functions as a basic test page. To parse incoming JSON and URL-encoded data, middleware functions express.json() and express.urlencoded() are included. This solution demonstrates a methodical approach to fundamental arithmetic computations, input validation, error handling, and RESTful API queries in a Node.js environment.

Features
•	Supports the following arithmetic operations:
	Addition (/add)
	Subtraction (/subtract)
	Multiplication (/multiply)
	Division (/divide)
	Exponentiation (/exponentiate)
	Square Root (/sqrt)
	Modulo (/modulo)


•	Input validation to ensure correct numerical values are provided.


•	Proper error handling, including division by zero and invalid inputs.


•	Express middleware support for JSON and URL-encoded data parsing.


•	A test endpoint at / to confirm server functionality.

