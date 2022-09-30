# Holberton School Shell Project

## This directory was made to store the tasks and work done as part of the "Shell Permissions Project"

### Includes scripts with permission commands within the shell

#### Script Descriptions:

	0. su betty (Switches the current user to betty)
	1. whoami (Prints name of current user)
	2. groups (Prints all the groups the current user is part of)
	3. sudo chown betty hello (Changes the owner of the file hello to the user betty)
	4. touch hello (Create an empty file called hello)
	5. chmod u+x hello (Adds execute permission to the owner of the file hello)
	6. chmod 754 hello (Adds execute permission to owner, groupowner, and read to other users)
	7. chmod ugo+x hello (Adds execute permission to the owner, groupowner, other, over file hello)
	8. chmod 007 hello (Adds all the permissions to other users)
	9. chmod 753 hello (Sets mode of file to rwxr-x-wx)
 	10. chmod --reference=olleh hello (Mirrors the mode of the file hello to the file olleh)
	11. chmod -R a+X . (Adds execute permission to all subdirectories but no files are changed)
	12. mkdir -m 751 my_dir (Creates a directory called my_dir with permissions 751)
	13. chown :school hello (Changes the group owner to school for the file hello)
	14. chown vincent:staff * (Changes the owner to vincent and group owner to staff)
	15. chown -h vincent:staff _hello (Changes owner to vincent and groupowner to staff of _hello,
	a symbolic link)
	16. chown --from=guillaume vincent hello (Changes the owner of the file hello to vincent only if 	it is owned by the user guillaume)
