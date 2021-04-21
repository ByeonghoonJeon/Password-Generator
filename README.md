# Password-Generator
Code for generating passwords.

# 3 steps to use.

1. Decide lenth of your password.
2. Decide how many alphabet do you want in your password.
3. Decide how mayn numbers do you want in your password.

# How it works?
Every user input is evaluated for the validity. If user input letters when they need to input number, it does not proceed to next step.
First, to practice [try and exceptions], user's input is tried to devide by one.
If user's input is zero, it will cause ZeroDivisionError, and then this program will require new input from user.
If user's input is letters, it will cause ValueError, and then this program will require new input from user.

If user's input corresponds as I intended, the number is set as total digit and decreases along with the following inputs, lenth of alphabet and numbers.

Since limit of total digitis already determined at the first input, sum of alphabets and numbers are needed to be contained within the total digit.
After inputting lenth of numbers, if there are still available digit, the rest of digits are automatically assigned to symbols. 

By checking all the input from user, remove all the possible errors and


