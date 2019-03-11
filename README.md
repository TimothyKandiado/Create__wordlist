# Create__wordlist
-----------------------
Python program to create a word_list file from a set of provided keywords
-----------------------
Requirements: Python 3
-----------------------
Use main.py for basic operations, modify where necessary

================================================================================
The program creates a word_list using keywords stored in a specified input file,

The word_list is written to a specified output file.
================================================================================
-------------------------------------------------------------------------------------------------------------------------------------
Usage:
--> Create an input file and place it in an accessible directory
--> Open Main.py and modify on the input file, output file(out), minimum word length(min), and maximum combination of strings(cycles)
--> Run Main.py
--> Find the output file
-------------------------------------------------------------------------------------------------------------------------------------
Working:
	An input file is converted to a list
	An object of CreateWordlist is instantiated with parameters(min = 1, cycles = 2) these are default values
	Using the instantiated object the function deploy() is called with parameters(list'keywords', out="output.txt")
		A while loop and two for loops (nested loops) are used to cycle through the list to combine each keyword with every other keyword in the list
		for loop 1 cycles through list(arr1) and lfor loop 2 cycles through list(list) the output combinations are appended to list(arr2)
		at the end of the while loop arr1 = arr2, arr2 = []. Outputs of the first cycle will be used as first keywords in the second cycle.
		
	
