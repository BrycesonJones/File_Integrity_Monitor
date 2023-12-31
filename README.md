# File Integrity Montitor for Data Security, Integrity, and Confidentiality

## A fully Functional Example Project Written in PowerShell Showing how to Create a File Integrity Monintor.

This project is an example that was built to implement a risk mitigation and strengthen security posture for data management. Every part of this project is sample code which shows how to do the following:

*Ask the user if they want to collect a new baseline or begin monitoring files with the saved baseline

*Collect a new baseline by calculating a HASH value from target files and then storing the file|hash pairs in a baseline.txt file

*Begin monitoring files with a saved baseline.txt file by loading the file hash pairs from the file

*Loop throough each target file to calculate the hash and compare the file|hash to what is in the baseline.txt file

*Notify the user if a file is changed or deleted

## How to Implement this Project to Maintain the Intergity of Files

This project is written in PowerShell. Use an operating system that is appropriate for this language.

1. This project can be ran from the command line using a text editor to write, save, and run the program
2. The files being secured should have a known and clear path

## Find a Bug?

If you found an issue or would like to submit an improvment to this project, please submit an issue using the issue tab above. If you would like to submit a pull request with a fix, reference the issue you created.

*Make sure to squash all commits when you submit a pull request

*Make sure to file an issue that this resolves before submitting a pull request

## Ways to Improve this Project (in progress)
1. Accounting for the situation when a baseline file is to be monitored but the baseline file does not exist and redirecting the user to create a baseline file
2. Letting the user pick which folder to monitor
3. Implement recursive file monitoring that allows for deep diving into the file structure to monitor all files in a folder
4. Email notifications to user rather than soley printing to the screen
