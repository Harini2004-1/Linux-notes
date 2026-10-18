## Purpose:
chmod stands for Change Mode.
It is used to change the permissions of files and directories in Linux.

## Linux permissions control who can:
r — Read a file
w — Write or modify a file
x — Execute a file or script

## Linux File Permissions
Example output of ls -l:
-rw-r--r-- 1 root root 30 Jul 24 12:56 file_name

| Command | Meaning|
| chmod +r file_name | Add read permission
| chmod -r file_name | Remove read permission |
| chmod +w file_name | Add write permission |
| chmod -w file_name | Remove write permission |
| chmod +x file_name | Add execute permission |
| chmod -x file_name | Remove execute permission |
| ls -l | Check file permissions |

 ## Practice Commands
touch practice.txt
ls -l practice.txt
chmod +x practice.txt
ls -l practice.txt
chmod -w practice.txt
ls -l practice.txt
chmod 644 practice.txt
ls -l practice.txt

## Real-Life Example
Imagine a company has a file named Salary.txt.
The company wants:
HR: Read and write access
Employees: Read-only access
Others: No access
Linux permissions can help enforce these rules.
