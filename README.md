# GHS_number_to_full_statements
A simple project with the only objective of taking in a string of GHS hazard and precautinary statements as numbers (e.g. "H210, P315") and returns these numbers extended by their full statements.

# Requirements
Python 3.13.0
Although it should most likely work with any modern python version, because it is a very simple script.

# Installation
1. Download the source of this repository into a safe location.
2. (Optional) Set up a virtual environment for python, in case you don't want to run into dependency issues.
3. Install dependencies from `requirements.txt`. (a) Open the terminal of your PC. (b) Use the `cd` command to navigate into the downloaded repository. (c) Run `pip install -r requirements.txt`
5. Run the python script from the command line.

The results will be printed to the console as well as be copied into your clipboard, so you can paste them wherever you need them.

# Why does this exist?
As a chemist who regularly has to label bottles of solvent or small vials of dangerous chemicals, I have wasted a lot of time in just copying H/P statements from wikipedia onto my labels and then having to manually fill them out.
This script took me like 20min to write, so I hope it will save me (and maybe others) atleast 20min during the span of my/their carrier(s).
