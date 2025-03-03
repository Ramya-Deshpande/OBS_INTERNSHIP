Python program assignment
Table of contents:
1.Sum of Digits - The Magical Book
2.Temperature Converter - The Weather Scientist
3.Check for Palindrome - The Time Machine Code
4.Fibonacci Series - The Alien Signal
5.Count Vowels and Consonants - The Cryptic Scroll
6.Find the Second Largest Number - The Treasure Hunt
7.Matrix Multiplication - The Quantum Experiment
8.Data Visualization - Election Poll Analysis
9.Data Cleaning and Transformation - The Football Analyst
10.Data Visualization - The Meteorologist’s Report

1. Sum of Digits - The Magical Book
Story: A little girl named Maya finds an old magical book in her attic. The book contains a puzzle that asks her to find the sum of the digits of a number. Only by solving it can she reveal the book’s next secret.
Task: Write a Python program that takes an integer as input and returns the sum of its digits.
Solution: Convert integer to string. Initialize a variable to zero, iterate over string, convert each digit to integer and add it ti the variable earlier initialized to zero.

2. Temperature Converter - The Weather Scientist
Story: A junior weather scientist is struggling to convert temperatures from Celsius to Fahrenheit and vice versa. His boss has assigned him the task of creating a converter tool to simplify the process.
Task: Write a Python program that takes temperature input in Celsius or Fahrenheit, detects the
unit, and converts it to the other unit.
Solution: Ask for input with C for celsius and F for Fahrenheit e.g 23C. Extract content of last index by slicing. Use conditional statements to check it is C or F and then apply respective functions for conversion.

3. Check for Palindrome - The Time Machine Code
Story: A young scientist finds an ancient time machine manual with a secret code. The manual says that only palindromic words can activate the machine. Can you help the scientist check if a word is a palindrome?
Task: Write a Python program that checks whether a given string is a palindrome (reads the same
forward and backward).
Solution: Take a string input. Use conditional statement to check if given string is equal to it's slicing from backwards, if yes it is a palindrome.

4. Fibonacci Series - The Alien Signal
Story: A group of scientists at NASA has received a mysterious signal from space. The numbers in the signal follow a pattern that looks like the Fibonacci series. To decipher the message, they need to generate the first n numbers in the Fibonacci sequence.
Task: Write a Python program that generates the Fibonacci sequence up to n terms.
Solution: Take input for how many numbers are required in series. Initialize two variables: one to zero and other to one, these are the first and second element of series. Initialize a variable to zero, this can be named sum. Use loop keeping range between 2 to limit, 2 because we want series from third element and upto the number of input limit.Add earlier initialized variables and store in sum variable. Swap such that first variable gets second variable value and second variable gets sum value and print sum value.

5. Count Vowels and Consonants - The Cryptic Scroll
Story: A historian finds an ancient scroll written in an unknown language. The first step to translating it is to count the number of vowels and consonants in a given text.
Task: Write a Python program that takes a string input and counts the number of vowels and
consonants in it.
Solution: Take string as input. Store the vowels in lower letters in a list. Create two variables one for vowel count and other for consonant count and initialize them to zero. Iterate throughout the string and check if it is an alphabet, if yes check if the alphabet is in the list created, if yes it is a vowel so add 1 to vowel count variable else add one to consonant count variable.

6. Find the Second Largest Number - The Treasure Hunt
Story: A pirate finds a map with coordinates leading to treasure. However, to reach the exact location, he must find the second largest number in a given list of coordinates.
Task: Write a Python program that finds the second largest number in a list of integers.
Solution: Ask for input of integers from user and store them in a set. Convert set to list. Sort the list and extract element at index at -2 to get second largest element. Storing in a set is required so that duplicate elements can't be stored, if duplicate elements are stored and largest element appears more than once then after sorting we can't find second largest element by extracting element using index as -2.

7. Matrix Multiplication - The Quantum Experiment
Story: A physicist is conducting a quantum mechanics experiment that requires multiplying two matrices. He needs a program to quickly compute the product of two matrices to continue his research.
Task: Write a Python program that performs matrix multiplication using NumPy.
Solution: Take input of number of rows and colums for two 2D arrays. Check if number of columns of first 2D array is equal to number of rows of second 2D array. If no, print error message. If yes, import numpy and use dot function of numpy for 2D array multiplication.

8. Data Visualization - Election Poll Analysis
Story: A journalist is covering an election and wants to visualize polling data for different candidates. She needs a bar chart showing the number of votes each candidate received.
Task: Write a Python program that takes a dictionary of candidate names and vote counts and creates a bar chart using Matplotlib.
Solution: Take input of candidate name and count of votes from user and store it in a dictionary. Extract candidates and count of votes from dictionary and store it in two respective lists. import matplotlib, use bar function to create bargraph and pass the lists as parameters.

9. Data Cleaning and Transformation - The Football Analyst
Story: A sports analyst is analyzing football player statistics but finds the data messy. Some player scores are in string format, some values are missing, and there are duplicate entries. Before making predictions, the analyst must clean and standardize the dataset.
Task: Write a Python program that:
• Converts string numbers to integers where needed.
• Replaces missing values with the average score.
• Removes duplicate player entries.
• Sorts players based on performance.
Solution:Create a data or download related data. Import pandas. Create dataframe from data using DataFrame function. Convert required columns to numeric by using to_numeric function passing the column as parameter. Find the average of score column using mean function. Use fillna function with average sore stored variable as parameter to replace NaN by average score. Drop duplicate player names by using dropna and paramerter as subset=["column name"]. To remove duplicate players use drop_duplicates. Use sort_values and pass the parameter as column name according to which sorting is to be done.

10. Data Visualization - The Meteorologist’s Report
Story: A meteorologist is tracking daily temperature variations for a month. He wants to analyze how the temperatures are distributed and find outliers to predict extreme weather conditions.
Task: Write a Python program that:
• Generates 30 random temperature values between 10°C and 40°C.
• Creates a histogram to show the frequency of temperature ranges.
• Draws a box plot to detect outliers.
Solution:Import numpy and matplotlib. Generate 30 values between 10 and 40 using random.randit(30,10,40) function of numpy. Use subplot to display both histogram and boxplot in a single figure. Use hist function and pass random tempertaures generated as a parameter. Use boxplot function and pass random tempertaures generated as a parameter.

Requirements:
1.Python 
2.Pandas
3.Numpy
4.Matplotlib
5.Jupyter notebook

