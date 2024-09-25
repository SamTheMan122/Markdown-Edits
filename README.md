# CECS 326 Project 1

### Project Description
C program that copies the contents of one file to another through interprocess communications using ordinary pipes. Here's a rundown of how to compile and run the program through VSCode on Windows to produce the expected output.

### Technologies
- Windows 11 (directions specifically for Windows, but program should run in any UNIX based system)
- VSCode
- WSL

### How to Run the Program
1. Download and unzip the files containing the **FileCopy.c**, **input.txt**, and **copy.txt** into a folder.
2. Open the folder in VSCode
3. Open WSL in VSCode by either:
   - Pressing F1, selecting "WSL: Open Folder in WSL"
   - Clicking the search bar, typing in ">WSL: Open Folder in WSL"
4. Make sure the project folder is open in the WSL terminal and a new WSL terminal is open.
5. Compile the program by typing in *gcc -o filecopy FileCopy.c*
6. Run the program by typing in *./filecopy input.txt copy.txt*
7. Check the contents of the files by running _$ cat input.txt_ and _$ cat copy.txt_

