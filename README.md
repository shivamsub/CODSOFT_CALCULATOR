# CALCULATOR
Python project for a user-friendly Calculator.

1. Importing Modules
    -  We import the Tkinter module which helps us to create a user-friendly GUI.
      
2. Creating a Function for Click Event
    - We create a function named 'on_click' which sets what needs to be done when each button is clicked on the GUI.
    - We first get the current value from the result tab.
    - If '=' is clicked we set the result to the new evaluated value.
    - If 'C' is clicked we cleat the result label.
    - If any other button is clicked we add that text to the current result label.
      
3. Setting up Window
    - We create an interface window and give the title and dimension.
      
4. Setting up Labels
    - We create a result label with its default value empty.
    - We then style this result label using the display label which sets the font, border, relief etc.
      
5. Setting up Calculator Buttons
    - We set up the buttons with the help of a matrix which contains all the numbers and basic arithmetic operators symbol.
    - For each row in the button matrix we create a frame and pack the values and bind them.
    - Lastly, the window is looped.
