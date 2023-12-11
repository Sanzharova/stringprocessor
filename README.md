isStrongPassword Method:
This method checks whether a provided password is strong. A strong password is defined as having the following characteristics:

At least 8 characters in length.
Contains at least one uppercase letter.
Contains at least one lowercase letter.
Contains at least one digit.
Contains at least one special symbol.
isSpecialChar Method:
This is a helper method used by isStrongPassword to determine if a given character is a special symbol. Special symbols are typically characters like '@', '#', '$', '%', etc.

calculateDigits Method:
This method counts the number of digits in a given sentence. It iterates through the characters in the sentence and keeps track of how many of them are digits.

calculateWords Method:
This method calculates the number of words in a given sentence, considering words as separated by spaces. It counts the spaces between words to determine the total number of words.

testIsStrongPassword Method:
This method contains test cases for the isStrongPassword method. It uses assertions to validate that the actual results match the expected results. Test cases should cover different scenarios to ensure the method works correctly.

testCalculateDigits Method:
This method contains test cases for the calculateDigits method, checking if the actual digit count matches the expected count. Test cases should cover various combinations of digits in the input sentence.

testCalculateWords Method:
This method contains test cases for the calculateWords method, checking if the actual word count matches the expected count. Test cases should include sentences with different numbers of words and edge cases, such as an empty sentence.
