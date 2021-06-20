### Hello There.

## Global Variable Access

This repo contains the modules that will be able to access a global declared variable from a file to 2 different class
and update the variable value and yet retain it in main file.

### How To Run..

Just run the main.py file to get the output.

#### How it works

The global variable is present in globals.py module.
This module is imported in subtract.py file to minus the original value.
The subtract.py module is called by classes.py file which have 2 separate classes.
These classes can be called seperately in a single file and the value will continue to be accessible.
There won't be any original value displayed even when called form separate classes.
