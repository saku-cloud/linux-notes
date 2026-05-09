# Basic Linux Permissions 

## 1. Types of Permissions

## Read (r)
Files: Allows viewing or copying the file contents.
Directories: Allows listing the files within the directory using commands like ls.

## Write (w)
Files: Allows modifying or overwriting the file contents.
Directories: Allows creating, deleting, or renaming files within that directory.

## Execute (x)
Files: Allows running the file as a program or script.
Directories: Allows "entering" or traversing the directory using the cd command.

# 2. User Categories
Permissions are assigned to three distinct levels of ownership:

## Owner (u)
The specific user who owns the file.Group (g): A set of users who share the same permissions for that file.

## Others (o)
Every other user on the system who is not the owner or in the group.

# 3. Special Permissions
Beyond basic rwx, Linux uses special bits for advanced access control

## SUID (Set User ID)
When set on an executable, it runs with the privileges of the file's owner rather than the user running it.

## SGID (Set Group ID) 
On a directory, files created inside inherit the directory’s group ID instead of the creator's primary group.

## Sticky Bit (t)
 Typically applied to shared directories (like /tmp) to ensure only a file's owner or the directory's owner can delete or rename it.

# 4. Numeric Representation (Octal)
Permissions are often represented by a three-digit number where each digit is the sum of its permission values
4: Read
2: Write
1: Execute

# 5. Managing Permissions
You can manage these via the command line

## chmod 
Changes file or directory permissions (e.g., chmod 755 file.sh).

## chown 
Changes the owner and/or group of a file.

## chgrp 
Changes only the group ownership.

## ls -l 
Displays the current permissions of files in a long listing format.

