# CECS 326 Project 4

### Project Description
C program that implements the First Come First Served (FCFS), Priority, and Round Robin scheduling algorithms for tasks.

### Technologies
- Windows 11 (directions specifically for Windows, but program should run in any UNIX based system)
- VSCode
- WSL

### How to Run the Program
1. Download and unzip  **project4** into a folder.
2. Open the folder in VSCode
3. Open WSL in VSCode by either:
   - Pressing F1, selecting "WSL: Open Folder in WSL"
   - Clicking the search bar, typing in ">WSL: Open Folder in WSL"
4. Make sure the project folder is open in the WSL terminal and a new WSL terminal is open.
5. Compile and run the scheduling algorithms by calling the make file then the outputed scheduler
   - To test FCFS:
       - start with *make fcfs*
       - then *./fcfs schedule.txt*
   - To test Priority:
       - start with *make priority*
       - then *./priority schedule.txt*
   - To test Round Robin:
       - start with *make rr*
       - then *./rr schedule.txt*
