# Calculator Project

### Requirements
* build a calculator that can add, subtract, multiply and divide.
* write it with clean code
* host it on github pages.


### Extra requirements
* Users should be able to string together several operations and get the right answer: 12 + 7 - 5 * 3 etc.

* You should round answers with long decimals so that they don’t overflow the screen.

* Pressing '=' before entering all of the numbers or an operator should show error message.

* Pressing “clear” should wipe out any existing data.

* Display an error message if the user tries to divide by 0… don’t let it crash your calculator!

### suggested steps

* Create a basic HTML calculator with buttons for each digit, each of the above functions, an “Equals” key, a display screen and a “clear” button.

* Create a function that takes an operator and 2 numbers and then uses the operator on the numbers.

* make the display screen show the numbers you have pressed when you click the number buttons. you should be storing the ‘display value’ in a variable somewhere for use in the next step.

* Make the calculator work! You’ll need to store the first number that is input into the calculator when a user presses an operator, and also save which operation has been chosen and then use the function you created to calculate the answer when the user presses the “=” key.



### Stretch goals
* Add a '.' button and let users input decimals! Make sure you don’t let them type more than one though: 12.3.56.5. (disable the decimal button if there’s already one in the display)

* Make it look nice!

* Add a “backspace” button, so the user can undo if they click the wrong number.
