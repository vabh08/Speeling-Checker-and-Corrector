# Spelling-Checker-and-Corrector
What is a Spell Corrector?

Writing should always have no spelling errors to let the reader get the correct understanding. But being humans, it is common for all of us to make some errors. And that’s the reason the spell correctors are developed. These check the spelling of words and suggest the correct word if wrong. We will be building a prototype of a spelling corrector using Python.

Spell Checker using Python

We will be using the Tkinter module and TextBlob modules from Python. We use the Tkinter module to build the GUI for taking input from the user and showing the output based on the spelling typed. And to do this check we will be using the TextBlob module.

Steps to build the Spell Checker & Corrector Project in Python

    First we import the Tkinter and the TextBlob modules
    Then we create the GUI and add the required widgets
    Finally, we write the function to check the spelling and give the corresponding output.

A) Importing the module

The first step is to import the modules tkinter and the TextBlob class from the textblob module.

B) Creating the GUI

Then we create an empty GUI for adding the widgets.
 
C) Adding the required widgets

Now it’s time to add the widgets. We need

1. An Entry() to get the input of word from the user of which the spell check is to be done.
2. A button to run the function that does the spell check.
3. A Label() to show the corrected word.

D) Writing the function to check the spelling show output.

This function runs when the user clicks the button.

1. We first take the input word.
2. Then we create an object for this word.
3. Then we show the correct word in the label.
