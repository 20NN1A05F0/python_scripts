TASK - 1
Q1: Import and Use os Module
Task: Write a script to print the current working directory using the os module.

Q2: Check if a Path is a File or Directory
Task: Given a path, determine if it is a file or a directory.

Q3: Create a Directory (if not exists)
Task: Write a script that creates a new folder called test_folder in the current working directory if it doesn't already exist.

Q4: Loop Through Files and Filter by Extension
Task: List only .txt files in the current directory.

Q5: use the above concepts to complete the below task
Task: Write a Python script that does the following:

  Checks if a directory called reports exists in the current working directory. If it doesn't, create it.

  List all .txt files in the current working directory (not subdirectories).

  For each .txt file found: A) Print the filename. B) Move it into the reports directory.

TASK - 2
 Build a Python script that:
1. Checks if a folder named data_input exists in the current directory. If not, create it and inform the user to add .txt files to it.

2. Reads all .txt files from the data_input folder.

3. For each .txt file:
a) Count the number of lines and number of words
b) Ignore lines that start with # (comments)
c) Replace all instances of the word "temp" with "permanent"
d) Save the modified version into a new folder called data_output with the same filename.

4. At the end, create a summary file called summary.txt inside data_output, showing:
a) Filename
b) Line count (excluding comment lines)
c) Word count (excluding comment lines)
