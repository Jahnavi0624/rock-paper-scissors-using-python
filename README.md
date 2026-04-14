# rock-paper-scissors-using-python
The object of the rock-paper-scissor python project is to build a game for a single player that plays with a computer, anywhere, and anytime. This project is build using tkinter, random modules, and the basic concept of python.
1. First step is to import libraries
Tkinter is a standard GUI library which is one of the easiest ways to build a GUI application.
random module use to generate random numbers
2. Initialize Window
Tk() use to initialized Tkinter to create window
geometry() sets the window width and height
resizable(0,0) by this command we can fix the size of the window
title() used to set the title of the window
bg = ‘’ use to set the color of the background
Label() widget used when we want to display text that users can’t modify.
root is the name of our window
text which displays on the label as the title of that label
font in which form the text is written
pack used to the organized widget in form of block
3. For User Choice
user_take is a string type variable that stores the choice that the user enters.
Entry() widget used when we want to create an input text field.
4.For Computer Choice
random.randint() function will randomly take any number from the given number.

Here we give the if-else() condition to play rock paper scissors

If the computer choose 1 then the rock will set to comp_pick variable
If the computer choose 2 then the paper will set to comp_pick variable
If the computer choose 3 then scissors will set to comp_pick variable
5. Function to Start Game
6.  Function to Reset
user_take is a string type variable that stores the choice that the user enters.
We give if-else() condition to check who wins between user choice and computer choice.
In this rock paper scissors game,  a player who chooses rock will win by another player who chooses scissors but loose by the player who chooses paper; a player with paper will loose by the player with the scissors. If both choose the same then the game will tie.
7.Function to Exit
This function set all variables to an empty string.
root.destroy() will quit the rock paper scissors program by stopping the mainloop().
8. Define Buttons
Button() widget used when we want to display a button.
command called the specific function when the button will be clicked.
root.mainloop() method executes when we run our program.
