# Document-Searching

## Task
The program needs to search through a set of word document and find out the name of the student(s) with the highest CGPA.

## Approach
Using the python library docx, you can easliy open and get the data stored in a word document, the doc only contains raw data, so to get the required data which is the CGPA, split and splice the strings at the particular intervels required. From there, it is just a matter of creating a python program to find the max index of the data, and getting the name at that index.
