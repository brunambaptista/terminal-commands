## Terminal basics

- ls - shows whats inside the folder
- ls -a - includes hidden files
- cd dir1 - goes to the specified folder / directory
- cd - returns to the home folder
- cd .. - goes to the directory above the one you’re currently in
- cd - - goes back to the directory you were in before the last time you issued the cd command
- cp file1 /home/bruna/file1 - copies the file into a new place
- cp file1 file2 dir1 - copies the two files in the new directory
- cp -r dir1 dir2 - copies the new directory under a new name
- cp dir1/* dir2 - copies all files in dir1 into dir2
- mv file1 file2 - renames file1 to file2
- mv file3 dir1/file3 - moves file3 to new directory
- mv * dir2 - moves all files and directories in the current directory to new dir2
- clear - clear the screen
- reset - reset the terminal
- htop - show active process and cores
- touch file1 - creates a new file
- open file1 - opens file1
- mkdir dir1 - creates a new directory
- rm -R dir1 - deletes directory and contents
- sudo rm -rf dir1 - deletes directory and contents

### Search mode
- grep pattern1 - search for all lines that contains the pattern
- grep pattern1 file1
- grep -r pattern1 dir1
- grep -v pattern1 file1 - all lines that do not contain the pattern
- ^R - to search an old command based on the beginning

### Editing mode
- vim file1 - to enter edit mode
  - i - insert mode
  - esc - returns to command mode
  - :w - save the file
  - :q! - quit vim without saving
  - :wq - save then quit
  
### Chaining commands
- [command-a]; [command-b] - runs command A and then B, regardless of success of A
- [command-a] && [command-b] - runs command B if A succeeded
- [command-a] || [command-b] - runs command B if A failed
- [command-a] & - runs command A in background
- [command-a] | [command-b] - runs command A and then pass the result to command B
