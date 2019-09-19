# Hackathon - 2019 - CS301

You are working for Elon Musk (CEO of SpaceX) to send rockets to Mars. You will be working on a webpage for the press to sign up and attend the launching event of a new spaceship.  
Your job is to complete the code inside `index.html` to make the webpage functional.   
  
In the HTML page, you will find two sections: 
* **Left section**: where users fill out their details 
* **Right section**: once the users click on "Launch" button, they will see their details in the badge. 
  
The challenge requirements are: 
1. Replace all the `{{FILL_OUT}}` placeholders in the HTML `<body>`. 
2. Write JavaScript code in the `<head>` section to validate all users input based on the following criteria: 
  * Full name:  
    * Must be at least two words, separated by one whitespace or more. 
    * Each word must start with a capital letter, if not, convert the first letter of each part to be capital. 
  * Email: 
    * Must include one `@` character. 
    * After the `@` character we must have one dot `.` character. 
  * Phone: 
    * Must be `string` with the following format: `nnn-nnn-nnnn` (numbers separated by `-` sign) 
    * Make sure `n` is a valid number *(optional)*
  * Company: 
    * A required field 
  * State: 
    * Must consist of two capital letters (example: `IA`), if not, convert the them to capital. 
3. In case any of the above validation rules is invalid, display an `alert()` message to inform the user about the problem.  
4. When all of the input values are valid, then replace all the `{{FILL_OUT}}` placeholders of the badge with the appropriate values. 
  
  
### Evaluation Criteria: 
* Valid HTML and JS code 
* Meaningful and consistent naming 
* Proper code indentation 
* Adding descriptive comments to your code 
* Minimal access to the DOM 
* Logic you use for validating each input value 
* Performance of the code 
* Finishing all requirements 
* How much time spent to finish the challenge 
  
**Note: Maximum time to solve the challenge is 1 hour.**
  
To submit your code, please push your solution to your remote repository. 

 

 

 
