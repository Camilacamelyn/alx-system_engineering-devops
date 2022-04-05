## Shell, basics
## Tasks
#### [Write a script that prints the absolute path name of the current working directory.] (0. Where am I?)
#### [Display the contents list of your current directory.] (1. What’s in there?)
#### [Write a script that changes the working directory to the user’s home directory.] (2. There is no place like home)

- You are not allowed to use any shell variables
#### [Display current directory contents in a long format] (3. The long format)
#### [Display current directory contents, including hidden files (starting with .). Use the long format.] (4. Hidden files)
#### [Display current directory contents] (5. I love numbers)

- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)
#### [Create a script that creates a directory named my_first_directory in the /tmp/ directory.] (6. Welcome)
#### [Move the file betty from /tmp/ to /tmp/my_first_directory.] (7. Betty in my first directory)
#### [Delete the file betty.] (8. Bye bye Betty)

- The file betty is in /tmp/my_first_directory
#### [Delete the directory my_first_directory that is in the /tmp directory.] (9. Bye bye My first directory)
#### [Write a script that changes the working directory to the previous one.] (10. Back to the future)
#### [Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.] (11. Lists)
#### [Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.] (12. File type)
#### [Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.] (13. We are symbols, and inhabit symbols)
#### [Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.] (14. Copy HTML files)

You can consider that all HTML files have the extension .html
####  [Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.] (15. Let’s move) 

You can assume that the directory /tmp/u will exist when we will run your script
#### [Create a script that deletes all files in the current working directory that end with the character ~.] (16. Clean Emacs) 
#### [Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.] (17. Tree) 

You are only allowed to use two spaces (and lines) in your script, not more.
#### [Write a command that lists all the files and directories of the current directory, separated by commas (,).] (18. Life is a series of commas, not periods)

- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line
#### [Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.](19. File type: School)
