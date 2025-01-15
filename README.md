# CHEME-545-HW1
## Homework 1 Problem 3

The functions contained within this repository are from problem 1 and 2 of Homework 1.


Both functions utilize try and except in order to catch errors when accessing a dictionary.
The extract parameter function is intended to be used with the unit operations data dictionary, and takes in the unit name, parameter name, and index as its parameters.
It is used to extract the information for a given unit and parameter.

The calculate solution weights function is intended to be used alongside a molecular weights dictionary and a solutions needed list, where the list elements are strings formatted as "chemicalFormula-concentrationM".

This function is passed the dictionary and list of solutions needed as its parameters.

It returns a modified list containing strings of the form "chemicalFormula-concentration-weight", where weight is the weight (in g) of the chemical needed to obtain the desired concentration in 2 liter solution.


The complete code for this homework can be found in Gradescope. It can be run using software such as JupyterLab.
