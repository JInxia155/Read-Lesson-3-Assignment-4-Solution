Download Link : https://programming.engineering/product/read-lesson-3-assignment-4-solution/

# Read-Lesson-3-Assignment-4-Solution
Read Lesson 3 – Assignment 4 Solution
Preparation

    Read Lesson 3

    Read text sections 4.1 – 4.6 (skim 4.1 – 4.4), 5.6, and 5.8 (but skip the section titled “Boolean Logical Expression OR (^)”

    Watch the VideoNotes for chapter 4 in MyProgrammingLab

For Credit

Assignment 4.1 [15 points]

Complete all of the MyProgrammingLab exercises for chapter 4.

Assignment 4.2 [10 points]

Write an interactive program that computes the area of a square (area = side2) or triangle (area = 1/2 * base * height) after prompting the user to type the first character of the figure name (t or s). Note that a square does not have a base and a height. It has only a side. Your variable names should reflect this.

Sample screen output 1:

Enter the type of figure (s or t): t

Enter the base: 4

Enter the height: 3

The area is 6

Sample screen output 2:

Enter the type of figure (s or t): s

Enter the length of a side: 9

The area is 81

You may need to compare two Strings in order to complete this. You can’t compare Strings using the == operator. You’ll need to use the “equals()” method. It will look something like

if (string1.equals(string2))…

Turn in your source code and 2 outputs, one reflecting each of the two sample screen outputs given above.

Assignment 4.3 [10 points]

Write a program to display a message telling the educational level of a student based on his or her number of years of schooling. The user should enter a number indicating the number of years of schooling. The program should then respond with the appropriate message.

	

if years of schooling is
	

the message should be

less than or equal to 0
	

none

1
	

– 6
	

elementary school

7
	

– 8
	

middle school

9
	

– 12
	

high school

> 12
	

college

Each time you run this program, a single line (one of the 5 messages) gets printed. Turn in your source code and your output. A single output is sufficient.

Assignment 4.4 [10 points]

Write a program that serves as a simple calculator. The program should ask the user for a number, an operator, and then a second number. The operator should be either ‘+’, ‘-‘, ‘x’, or ‘/’. The program should then report the answer to the problem. Use a switch statement, not an if statement.

Turn in your source code and your output. A single output is sufficient.

Assignment 4.5 [25 points]

The phone company used the following rate structure for calls from San Francisco to Miami, Florida back in 1995:

Any call started at or after 6:00 pm (1800) but before 8:00 am (800.) is discounted 50%.

All calls are subject to a 4% federal tax.

The regular rate is $0.40 per minute.

Any call longer than 60 minutes receives a 15% discount on its cost (after any other discount is subtracted but before tax is added).

Please do not ask me in which order the calculations are to be done. That information can be deduced from the final bullet point above.

Write a program that reads from the user the start time for a call based on a 24-hour clock and the length of the call in minutes. Both of these will be stored in int variables. The gross cost (before any discount or tax) should be printed, and then the net cost (after discounts and taxes). Turn in 4 outputs for this exercise, showing that your program works in each of the following 4 cases. Use the input examples shown here, don’t make up your own.

Sample output 1:

Enter start time: 2322

Enter length of call in minutes: 67

gross cost: $26.80

net cost: $11.85

Sample output 2:

Enter start time: 759

Enter length of call in minutes: 10

gross cost: $4.00

net cost: $2.08

Sample output 3:

Enter start time: 1300

Enter length of call in minutes: 100

gross cost: $40.00

net cost: $35.36

Sample output 4:

Enter start time: 1300

Enter length of call in minutes: 10

gross cost: $4.00

net cost: $4.16

Turn in your source code and four outputs, one matching each of the four sample outputs given above, all in a single file, as usual.

Submit Your Work

Keep in mind that if your code does not compile you will receive a 0.

Note that the gmail email account is for homework submission only. The account is not monitored for any other purpose.

Assignment 4.6 [5 points]

Participate in the assignment 4 discussion. This could involve asking a question, answering another student’s question, giving an example of something that you struggled with and then overcame (or didn’t!), giving an example of something you found particularly cool, or any other constructive way you can think of to participate.
Solution
