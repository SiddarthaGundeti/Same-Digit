# Same-Digit

Question Explanation:

Input: 222

Output: True

The program is designed to determine if all the digits in a given three-digit number N are the same.

Logical Approach:

Read Input:

Read the three-digit number N as a string.

Extract Individual Digits:

Extract the first, second, and third digits from the string N.

Check if All Digits are Equal:

Convert the extracted digits to integers.
Compare the digits to check if they are all equal. This comparison is done using the logical expression first_digit == second_digit == third_digit, which evaluates to either True or False. Store this result in is_equal.

Output:

If is_equal is True, print "True". This indicates that all digits in N are the same.
If is_equal is False, print "False". This indicates that not all digits in N are the same.

Example for Clarity:

If the input N is 222:

The first digit (2) is equal to the second digit (2), and the second digit (2) is equal to the third digit (2).

Therefore, is_equal is True.

The output will be:True
