'Below is a describtion of what each script is doing
Task0
pwd
prints the absolute path name of the current working directory

Task1
Ls
Displays the contents list of your current directory
                               
Task2
cd ~ 
changes the working directory to the user’s home directory

Task3
ls –l 
Displays current directory contents in a long format

Task4
ls –al
Displays current directory contents, including hidden files

Task5
ls –al 
Display current directory contents.
•	Long format
•	with user and group IDs displayed numerically
•	And hidden files (starting with .)

Task6
mkdir /tmp/my_first_directory/ 
creates a directory named my_first_directory in the /tmp/ directory.

Task7
mv /tmp/betty /tmp/my_first_directory/betty : 
Moves the file betty from /tmp/ to /tmp/my_first_directory.

Task8
rm /tmp/my_first_directory/betty :
	Deletes the file betty in /tmp/my_first_directory

Task9
rm -rf /tmp/my_first_directory :
	Deletes the directory my_first_directory that is in the /tmp directory.

Task10
cd - :
changes the working directory to the previous one

Task11
ls -la . .. /boot :
lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

Task12
file /tmp/iamafile : 
	prints the type of the file named iamafile. The file iamafile will be in the /tmp directory

Task13
ln -s /bin/ls __ls__ :
	Creates a symbolic link to /bin/ls, named __ls__ in the current working directory

Task14
cp -un *.html ../ :
copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.'

