Q1) Write a function highwayNumberInfo that accepts an highway number(int) and returns a string contaning infomation about the highway number. Primary U.S. interstate highways are numbered 1-99. Odd numbers (like the 5 or 95) go north/south, and evens (like the 10 or 90) go east/west. Auxiliary highways are numbered 100-999, and service the primary highway indicated by the rightmost two digits. Thus, I-405 services I-5, and I-290 services I-90. Note: 200 is not a valid auxiliary highway because 00 is not a valid primary highway number.

Parameter:  highway number (int)
Return:  highway number info (string)
Example1
Input: 90
Output: I-90 is primary, going east/west.
Example 2
Input: 290
Output: I-290 is auxiliary, serving I-90, going east/west.
Q2) Write a function Num2Binary that takes as an input a positive integer, and returns a string of 1's and 0's representing the integer in reverse binary. For an integer x, the algorithm is:

As long as x is greater than 0
   Output x % 2 (remainder is either 0 or 1)
   x = x / 2
Parameter:  number (int)
Return: binaryRep (string)
Example1
Input: 6
Output: 011 
Q3) Write a function CharCount that takes as an input a character and a string, and returns an int indicating the number of times the character appears in the string. The output should include the input character and use the plural form, n's, if the number of times the characters appears is not exactly.

Parameter:  char (string) and string (string)
Return:  count (int)
Example1
Input: n Monday
Output: 1 n
Example 2
Input: n It's a sunny day
Output: 2 n's
Q4) Write a function wordFrequency that takes as an input a list of words, and returns a dictionary with words and their frequencies.

Parameter:  listOfWords(list)
Return:  wordFreq(dict)
Example1
Input: [hey,hi,Mark,hi,mark]
Output: {hey :1 ,hi :2 , Mark:1 ,  mark:1}
Q5) Given a list of integers, create a new list comprehension that contains all integers less than or equal to 50 in the original list.

Q6) Write a function coinFlip that takes as an input an int (0,1), and returns a string ("Heads" or "Tails") according to a random value of 1 or 0.  Assume the value 1 represents "Heads" and 0 represents "Tails". 

Parameter: num(int)
Return:  coin(string)
Example
Input: 0
Output: Tails
Given the following list [0,1,1,0,1,0,0] call coinFlip()  with each value in the list

Q7)Write function  Statistics that accepts three floating-point numbers x, y, and z, return a tuple of x to the power of z, x to the power of (y to the power of z), the absolute value of y, and the square root of (xy to the power of z).

Parameter: x(float), y(float), z(float), 
Return: tuple
Example
Input: 10 2 3
Output: (1000, 100000000, 2, 89.4427191)
Q8) Write a function calCalories that takes no input and returns a float of calculated calories. Inside the function reads the inputs age (years), weight (pounds), heart rate (beats per minute), and time (minutes), respectively. Then calculate the average calories burned by a person using the following equation

Screenshot 2024-02-27 at 12.57.19 PM.png

Parameter: None
Return: calories (float)
Example
Input: None
9Output: calories (float)
Q9) Write a function calChange  that takes an int representing the total change amount in pennies , and returns the change  as string using the fewest coins, one coin type per line. The coin types are Dollars, Quarters, Dimes, Nickels, and Pennies. Use singular and plural coin names as appropriate, like 1 Penny vs. 2 Pennies.

Parameter: changeAmount(int)
Return: change (string)
Example
Input: 45
Output: 1 Quarter 2 Dimes
Q10) Write a function inList that takes input a list of words, and a character and returns a list comprehension with words having the passed character.

Parameter: listOfWords(list), char(string)
Return: list
Example
Input: ["hello", "zoo", "sleep", "drizzle"] , 'z'
Output: [ "zoo", "drizzle"]
