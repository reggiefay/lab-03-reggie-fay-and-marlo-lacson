# Lab03
Decisions
# Lab 3

**Due:** See Moodle

## Problem

The *Fast Freight Shipping Company* charges the following rates:

| Weight of package                  | Rate per 500 miles (or fraction) |
|:-----------------------------------|:---------------------------------|
| 2 kg or less                       | $1.10                            |
| Over 2 kg but not more than 6 kg   | $2.20                            |
| Over 6 kg but not more than 10 kg  | $3.70                            |
| Over 10 kg but not more than 20 kg | $4.80                            |

Write a program that asks for the weight of the package and the distance it is to be shipped, and then displays the charges.

**Input Validation:** Do not accept values of 0 or less for the weight of the package. Do not accept weights of more than 20 kg (this is the maximum weight the company will ship). Do not accept distances of less than 10 miles or more than 3,000 miles. These are the company’s minimum and maximum shipping distances. In such cases, the program should output an appropriate message and end normally.

**Note:** The math module contains the function **math.ceil** which will round up a floating point number; e.g. math.ceil(2.7) returns 3.

## Instructions

1. Create a new Python file and place **intro comments** using the template below. 
2. Use comments to **write the algorithm** your program will follow.
3. Draw a **flowchart** and label the possible control paths. You can use graph-drawing software or you can draw it using pen and paper and then submit a picture.
4. Create an Excel file with at least one **test case for each control path**. Use one row per test case with one column for the case's label matching the flowchart, one column for each input, and one column for each corresponding output.
5. Write the Python **code** corresponding to each of your algorithm's steps. You will need to import the math module and use the `ceil` function to round up.

**Test** your program using your test cases. If the output doesn't match, correct your program.

**Commit** and **push** changes and check your repository on github.com to confirm your updates before leaving lab (even if not finished).

### Intro comments template

```
# Programmers: [your names]
# Course: CS151, Prof. Mehri 
# Date:
# Lab Number:
# Program Inputs: [What information do you request from the user?]
# Program Outputs: [What information do you display for the user?]
```

## Submission

One submission per team including all member names.

* GitHub: Completed .py file (including comments).
* Moodle: 
	1. An image file with **flowchart** (if hand-drawn, submit a picture of the page).
	2. An Excel file with **test cases**.
