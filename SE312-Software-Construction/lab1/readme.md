Department of Computing



SE-312: Software Construction
Class: BESE 9AB
Lab 01: Javascript 
Date: 22 February, 2021
Time: 09:00-11:50am & 02:00-4:50pm 
Instructor: Dr. Seema Jahan
Lab Engineer: Mr. Aftab Farooq




    	 
Lab 01: JavaScript 
Introduction
JavaScript is a well-known scripting language which is widely used to handle behavior of a web site. Most of modern websites use JavaScript and JavaScript based frameworks to control dynamic behavior at the client side. Students have learned basic and advanced concepts of JavaScript during their previous semesters. This lab will help them to further revise and understand these concepts by practically using JavaScript in given situations.
Objectives
The objective of this lab is helping students to familiarize themselves with basic concepts of JavaScript by practically implementing them in a given situation. The knowledge, students already gained in their previous semesters will help students to develop and control dynamic behavior of a web page using JavaScript.
Tools/Software Requirement
Notepad, Browser.
Helping Material:
W3Schools: https://www.w3schools.com/js/default.asp

Lab Tasks
Task 
Create a simple web based calculator as shown in the image below.
 
Following are the important functionalities of the calculator:
	Whenever a user presses any number (0-9) or operations (+,-,x,/,±, .), it must be shown in the input text field (see example image below). 
 
	In case of ‘.’ button pressed, a ‘0’ must be added at the end of the string as shown in above image. 
	When ‘=’ button is pressed result is shown in the text field.
	‘C’ button must clear and reset everything (text field, any storage variables).
	For a given input N, ‘1/x’ should give the results of 1/N (e.g. input =5, result = 0.20) of the given input.
	For a given input N, ‘x2’ should square the input (e.g. input =5, result = 25).
	The square root button, √,should calculate the square root of the input.
	The ‘±’ button should add/remove a ‘–’ sign to the input value.
	MS button must store the numeric input value written in the text field in a variable. In case of an equation as shown in the image above, it should not store anything.
	MC button should clear stored numeric value.
	MR button should recall the stored value and display it in the input text field.
	M+ button should add the input value given in the text field in to the stored value in memory and save it as stored value. 

Hints:
	JS ‘OnClick’ event will be attached to all buttons in the calculator.
	To handle value storage (MS, MC, MR, M+), create a global variable, M, and change its value according to the button pressed.
	To display inputs as a sequence of numbers and arithmetic operation (e.g. 2+3-5+7/2.5), use string concatenation. 
	You can use JS eval() function to directly execute a string as a JS statement. See example below:
var input= “2+3-5+2.5/2.5”;
eval(input);   // output: 1.0
	Keep in mind point 4 on eval(), when “=” button is pressed just call var result = eval(document.getElementByID(“inputTextField”).value);

Solution
Task  Code:
Task  Output Screenshot:
Deliverables
Compile a single word document by filling in the solution part and submit this Word file on LMS. This lab grading policy is as follows: The lab is graded between 0 to 10 marks.  The submitted solution can get a maximum of 5 marks. At the end of each lab or in the next lab, there will be a viva/quiz related to the tasks. The viva/quiz has a weightage of 5 marks.  Insert the solution/answer in this document. You must show the implementation of the tasks in the designing tool, along with your complete Word document to get your work graded. You must also submit this Word document on the LMS. In case of any problems with submissions on LMS, submit your Lab assignments by emailing it to Mr. Aftab Farooq: aftab.farooq@seecs.edu.pk.
