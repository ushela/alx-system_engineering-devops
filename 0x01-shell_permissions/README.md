#su
su was used to switch user

#whoami
prints the username of current user

#groups
all groups of user

#chown 
change the owner of the file

#touch
creates an empty file

#chmod u+x
execute permission to the owner of the file

#chmod +114
adds execute permission to the owner and the group owner, and read permission to other users, to the file

#chmod +111
script that adds execution permission to the owner, the group owner and the other users, to the file

#chmod 007 
other users all have permissions except owener and group

#chmod 753
giving permission

#chmod --reference=olleh hello
sets the mode of the file hello the same as olleh’s mode..

#chmod -R ugo+X*
adds execute permission to all subdirectoriies of the current directory for the owner, the group owner and all other users

#mkdir mydir ....
script that creates a directory

#chgrp .....
script that changes the group owner

#chown ......
script that changes group owner for all files and directories 

#chown -h
changes a specific owner

#chown --from=.....
conditional ownership

