# Sudoku Input Validator

Name:    Mestayer, Austin
Email:    amesta2@lsu.edu
Project:  PA-1 (Multithreading) 
Instructor:  Feng Chen 
Class:    cs4103-sp21 
Login ID:  cs410371
LSU ID: 89-320-6669

1. Run the .jar by navigating to the directory where it is contained, use command "java -jar sudoku.jar"
2. Your argument should be the local location of the input file (contained within my submission directory is    the file "file.txt", your argument should simply be "file.txt"

Expected input: .txt file containing a 2d 9x9 array of numbers (whitespace is delimited)
Expected output: the program operates by creating 3 threads:
                 -one for checking column validity
                 -one for checking row validity
                 -one for checking subgrid validity
                 
                 Output should be in the form of:
                 "Thread 1, Row 1, Valid" if given valid input
                 "Thread 1, Row 1, Invalid" if given invalid input
                 
                 "Thread 2, Column 1, Valid" if given valid input
                 "Thread 2, Column 1, Invalid" if given invalid input
                 
                 "Thread 3, Sub-Grid R123-C123, Valid" if given valid input
                 "Thread 3, Sub-Grid R123-C123, Invalid" if given invalid input




