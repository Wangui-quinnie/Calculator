HTML Structure:

We create a simple HTML structure for the calculator with a text input for displaying the numbers and results.
There are buttons for digits (0-9), operations (+, -, *, /), a decimal point (.), an equals sign (=) to compute the result, and a clear button (C) to reset the display.
JavaScript:

We define variables currentOperand, previousOperand, and operation to keep track of the current input, the previous input, and the selected operation.
display is the text input element where we show the numbers and results.
appendNumber(number): This function appends the clicked number to the current operand and updates the display.
chooseOperation(op): This function sets the selected operation. If there is already an operation in progress, it computes the result first.
compute(): This function performs the arithmetic operation based on the selected operation and updates the display with the result.
clearDisplay(): This function clears all the variables and the display.
updateDisplay(): This function updates the display with the current operand.
Usage
Appending Numbers: When you click a number button, the appendNumber function is called, updating the current operand and displaying it.
Choosing Operation: When you click an operation button (+, -, *, /), the chooseOperation function sets the operation and moves the current operand to the previous operand.
Computing Result: When you click the equals button (=), the compute function performs the calculation and updates the display with the result.
Clearing Display: When you click the clear button (C), the clearDisplay function resets everything.

