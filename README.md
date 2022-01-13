# Java Assessment Coding Prompts

Complete all of the coding prompts below within the com.galvanize package. You may createa additional classes or files as needed.

## Prompts

1. Write a Method with the signature public static String longestString(String a, String b). 
   1. The longestString Method you are creating will determine which of the two inputs has the greatest length, and return that string.
   2. If both inputs are the same length, it will return the string "Same length!". 
   3. longestString will have two parameters: 
      1. String a, String b, both strings to be compared 
   4. If the length of string a is greater than string b, return string a. 
   5. If the length of string a is less than string b, return string b. 
   6. If the length of string a is equal to string b, return string Same length!. 
   7. Assume that the inputs will always be valid strings
   

2. Using a for loop, complete the method below so that it that prints every element of the Array that is passed in.


3. Given the following array:  
```
      String[][] rowsOfLetters = {
         {"A", "B", "C"},
         {"D", "E", "F"},
         {"G", "H", "I"},
         {"J", "K"},
         {"L"},
      }; 
```
Use two nested loops to go through rowsOfLetters and print out each letter.

4. Write a Method with the signature public static HashMap<String, Integer> characterCount(String letters){ 
   1. The characterCount Method you are creating will return a HashMap where the the keys are the letters in the string passed in to the method, and the values are the count of occurences of each letter in the string. 
      1. Example Result: 
`      characterCount("helloooo") // {e=1, h=1, l=2, o=4}`
5. Create a new class called Book with default access. 
   1. It should have 2 fields, String title and String author that are updated when a new instance of Book is created. 
   2. Book should also have a class method called contents. The contents method should return the String "Hello Reader!". 
   3. Try to answer as best as you can, the closer to the solution you can get, the more points you will receive

## Submitting your code

In order to submit your assessment, make sure you have committed all of your changes and push your repository to your Github account. Once completed, paste the url for your repository in the box provided on the assessment page.
