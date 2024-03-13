<!--# [JSL01] Submission: Syntax-Engine Interaction Challenge

You will: 
1. Use the Starter Code Repo, 
2. Code your solution,
3. Commit changes to your repo
3. Submit GitHub Repo Link to LMS [JSL01] Submission Project Tab

Imagine you are building a virtual pet adoption website, and you need to create a JavaScript function that checks if the user has entered valid pet adoption details. Write a function that takes a string as input and validates if it follows a specific syntax, such as starting with "pet_" followed by a combination of letters and numbers. If the input follows the syntax, return "Valid Syntax," otherwise, return "Invalid Syntax."

![alt text](jsl_01_final_result.gif)

## Challenge Instructions
1. In the script.js file, complete the validateSyntax function to check if the input string starts with "pet_" and is followed by a combination of letters and numbers.
2. If the input follows the correct syntax, set result to "Valid Syntax." Otherwise, set it to "Invalid Syntax."
3. Test your function by entering different strings in the input box and clicking the validate button.

## How to Test 
- Run the index.html challenge in a browser.
- Enter different pet adoption details in the input box and click the validate button to see the results.
- Make sure your solution works for a variety of inputs.
- Open the console and debug your code until there are no errors.

## Instructions for Running the Code
1. Save the HTML, CSS, and JavaScript files in a folder.
2. Open the folder in VSCode.
3. Right-click on index.html and open with a browser (use Live Server if available).
4. Modify the script.js file to correct the syntax errors and save the file.
5. Refresh your browser to view the changes.

This challenge helps students practice basic string manipulation and validation in JavaScript, along with simple DOM manipulation to create an interactive and user-friendly interface.

Check out the practice challenges on Scrimba here: https://scrimba.com/playlist/pqPae6ZH7-->


The `validateSyntax` function is used to validate input strings to ensure they follow a specific syntax. It checks if the input starts with "pet_" followed by a combination of letters and numbers. If the input follows the syntax, it returns "Valid Syntax"; otherwise, it returns "Invalid Syntax".

## Function Description

The `validateSyntax` function performs the following steps:

1. **Input Retrieval**: Retrieves the input string from an HTML input element with the ID `petInput`.
2. **Validation**: Uses a regular expression pattern to match the input against the syntax requirement of starting with "pet_" followed by alphanumeric characters.
3. **Result Assignment**: Determines the validation result based on whether the input matches the pattern.
4. **Display Result**: Updates the content of an HTML element with the ID `result` to display the validation result.

## Usage

To use the `validateSyntax` function:

1. Ensure that you have an HTML input element with the ID `petInput` for user input.
2. Include an HTML element with the ID `result` to display the validation result.
3. Call the `validateSyntax` function whenever input validation is required.











