# Calculator-ankitt
Created a simple calculator using HTML, CSS and Javascript.
Access the calculator through this link: https://calculator-ankit.netlify.app/

Inside the folder, there are three files – index.html, styles.css and script.js

This is the Javascript functions I have added: I started by creating a variable called equal_pressed which is set to zero. Every time the equal to the button is pressed, the value of the equal_pressed variable is changed to one.
So once any evaluation is completed and equal to the button is pressed, the display will clear itself when the user enters a new number or operator for evaluation.
I added a click event listener to the clear button. When "clear" button is pressed the whole display is cleared. Similar to this, I added a click event listener to "del" button. Here, we use the substr method to delete/remove the last entered digit from the display.
