# CodeGeneratingMacros  

Contains excel based macros for use in generating code templates for arduino and processing.  
not well enough documented for public use.

GenerateArduinoCode_10Jan18.xlsm  
========  
Generates arduino code in the same folder as itself.
declare the pins in the excel sheet, and use the checkboxes to generate template code for various shields and add-on boards.
I'm adding code for various things as O find them/see them as useful


ProcCodeManager10Jan17.xlsm  
========  
This will take a folder and output the names and last modified dates of each file in the folder.
on sheet 2 there is a list of "Good Classes".
if you press the "Replace" button, then each instance of a "Good Class" will be replaced with a copy of the newest copy among copies.
the idea is that when I write processing3 and arduino code with classes that live in their own files, I can easily update all my copies of those
classes to the latest copy.


SerialConnector_14Jan17.xlsm  
========  
This is the start of macro to generate a template processing3 and arduino code to show data in the processing file.
idea is to make creating data logging type programs easier.
