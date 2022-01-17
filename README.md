# Chronicalc - a calculator

The Chronicalc web app is a free advanced calculator that can be installed as a progressive web app on iOS and Android.

## Features

|invalid expression|valid expression|
|:---:|:---:|
|![invalid expression](invalid_expression.png)|![valid expression](valid_expression.png)|

- when no valid expression is on screen, the result area displays a "?" mark; clicking on this mark will take you to this readme page
- when no valid expression is written on screen, and the result field display a "?" mark, clicking on "=" will refresh the page
- when a valid expression is written on screen, and a number is displayed in the result field, clicking on "=" will copy the result to clipboard
- clicking on "M+" will save the current expression and result to memory
- clicking on "M" will open the memory screen

### On the memory screen

|memory screen|
|:---:|
|![memory screen](memory_screen.png)|

- saved expressions are displayed in two rows, with the name and delete button of the expression on the first row and the expression and the result value on the second row
- each expression saved in memory has a name, which by default is the date and time when the expression was saved
- the expression name can be clicked and edited
- expressions in memory are ordered in alphabetical order of their name
- clicking the red "x" button will delete the expression from memory
- clicking on the yellow expression or result will insert either of them in the expression field on the calculator screen, at the last caret position
- if a saved expression is invalid, it will not have a result button, but it can still be inserted in the expression field on the calculator screen
- if a saved entry is only a number without an expression, only the number will be displayed in the memory screen and can be inserted in the expression field on the calculator screen
- the memory screen can be closed by pressing the "close" button