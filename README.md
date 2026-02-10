# Experiment-No.---6
AIM:

To study and implement decision-making statements in Python using if, elif, and else by solving different real-life programs like checking number type, grade system, leap year, salary calculation, date increment, and tax calculation.

THEORY (4–6 lines):

Conditional statements in Python are used to execute different blocks of code based on given conditions. The if statement checks a condition and runs the code if it is true. The elif statement checks multiple conditions when the first condition fails. The else statement runs when none of the conditions are true. These decision-making statements are very useful for solving logical problems such as even-odd checking, largest number, grading, leap year validation, salary computation, and tax calculation.

Algorithm 1: Check Positive / Negative / Zero

Start the program.

Input a number from the user.

If number > 0 print Positive.

Else if number < 0 print Negative.

Else print Zero.

Stop.

 Algorithm 2: Check Even or Odd

Start the program.

Input a number from the user.

Check if num % 2 == 0.

If true print Even, else print Odd.

Stop.

 Algorithm 3: Find Largest of 3 Numbers

Start the program.

Input three numbers num1, num2, num3.

Compare all three using if-elif conditions.

Store the largest number in a variable.

Print the largest number.

Stop.

Algorithm 4: Find Grade Based on Marks

Start the program.

Input marks from the user.

If marks ≥ 90 print Grade A.

Else if marks ≥ 75 print Grade B.

Else if marks ≥ 60 print Grade C.

Else if marks ≥ 40 print Grade D.

Else print Fail.

Stop.

 Algorithm 5: Check Leap Year

Start the program.

Input a year from the user.

Check if year divisible by 4 and not divisible by 100 OR divisible by 400.

If condition true print Leap Year.

Else print Not a Leap Year.

Stop.

 Algorithm 6: Increment Date if Valid

Start the program.

Input date in format dd/mm/yyyy.

Split the date into day, month, year.

Find maximum days in the month (30/31/28/29).

Check if date is valid.

If valid, increment day by 1 (handle month/year change).

Print incremented date.

Stop.

 Algorithm 7: Check Vowel or Consonant

Start the program.

Input a character from the user.

Convert character to lowercase.

If character is in (a,e,i,o,u), print Vowel.

Else if character is alphabet, print Consonant.

Else print Not an alphabet.

Stop.

 Algorithm 8: Calculate Gross Salary

Start the program.

Input basic salary.

If salary ≤ 10000 calculate HRA = 20% and DA = 80%.

Else if salary ≤ 20000 calculate HRA = 25% and DA = 90%.

Else calculate HRA = 30% and DA = 95%.

Calculate Gross Salary = Basic + HRA + DA.

Print gross salary.

Stop.

 Algorithm 9: Calculate Income Tax

Start the program.

Input annual income.

If income ≤ 250000 tax = 0.

Else if income ≤ 500000 tax = 5% of amount above 250000.

Else if income ≤ 1000000 tax = 5% of 250000 + 20% of amount above 500000.

Else tax = 5% of 250000 + 20% of 500000 + 30% of amount above 1000000.

Print tax amount.

Stop.

CONCLUSION :

In this experiment, we learned how dictionaries store values in key–value form and how they can be accessed, updated, modified, and searched. Concepts like retrieving values safely using get(), validating login credentials, and finding the highest marks were successfully implemented. Dictionaries provide fast, flexible, and powerful data handling in Python.
