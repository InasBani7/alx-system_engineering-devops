This readme file contains my solution for the project 0x01. Shell, permissions.
Below is the description for each command used.
Task0
su betty				switches the current user to the user betty

Task1
whoami 				prints the effective username of the current user.

Task2
Groups					prints all the groups the current user is part of.

Task3
sudo chown betty hello			changes the owner of the file hello to the user betty

Task4
touch hello				creates an empty file called hello

Task5
chmod ug+x,o+r  hello			Write a script that adds execute permission to the owner of the file hello.

Task6
chmod ug+x,o+r  hello	adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

Task7
chmod ugo+x hello	adds execution permission to the owner, the group owner and the other users, to the file hello


Task8
chmod 007 hello			sets the permission to the file hello as Owner: no permission at all,Group: no permission at all,Other users: all the permissions

Task9
chmod 753 hello			sets the mode of the file hello to rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

Task10
chmod --reference=olleh hello	sets the mode of the file hello the same as olleh’s mode.


Task11 
chmod -R +X ..	adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users..

Task12
mkdir -m 751 my_dir	Create a script that creates a directory called my_dir with permissions 751 in the working directory.	
Task13
chgrp school hello			changes the group owner to school for the file helloworking directory.

