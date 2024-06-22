Name:I.karthika varsha 
company:CODETECH IT SOLUTIONS 
ID:CT08DS1712
Domain:Java programming
Duration:10th july 2024 
mentor:G.Sravani

overview of the project
This Java program calculates the average marks of three subjects entered by the user and then assigns a grade based on the average score.
java.util.*: Imports the entire java.util package, including Scanner which is used for input.
Main Class (Main):

Contains the main method where execution starts.
Scanner Initialization:

Creates a Scanner object sc to read input from the console.
Input Prompt:

Prints "enter the marks" to prompt the user to enter marks.
Input Reading:

Reads three integers a, b, and c using nextInt() method of Scanner to store marks of three subjects.
Average Calculation:

Computes the average of the three marks using the formula (a + b + c) / 3.
Grade Assignment:

Uses conditional statements (if-else if) to determine and print the corresponding grade based on the calculated average:
"O grade" for average > 91 and <= 100
"A+ grade" for average > 81 and <= 90
"A grade" for average > 71 and <= 80
"B+ grade" for average > 61 and <= 70
"B grade" for average > 51 and <= 60
"C grade" for average > 41 and <= 50
"fail" for average <= 40
Output:

Prints the calculated average and the corresponding grade based on the conditions.
