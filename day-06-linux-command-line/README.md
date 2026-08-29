# Day 6 – Linux Command Line Fundamentals

## Objective

The objective of this lab was to develop practical Linux command-line skills by navigating the filesystem, creating and managing files and directories, using built-in documentation, and safely performing common administrative operations.

## Why This Lab Matters

Linux is widely used for servers, cloud infrastructure, cybersecurity tools, and remote system administration. Command-line skills allow IT professionals to manage systems efficiently, troubleshoot problems, inspect files, and automate repetitive tasks.

## Lab Environment

- Host operating system: Windows
- Virtualization platform: Oracle VirtualBox
- Guest operating system: Ubuntu Linux
- Network mode: NAT
- Linux user: Standard lab user

## User and System Identification

I used the following commands:

- `whoami` to identify the current user
- `pwd` to display the current working directory
- `hostname` to identify the computer
- `date` to verify the system date, time, and timezone

These commands help an administrator confirm who they are, which system they are managing, and where they are working.

## Filesystem Navigation

I practiced:

- `ls`
- `ls -l`
- `ls -la`
- `cd`
- `cd ..`
- `cd ~`
- `pwd`

I learned the difference between absolute and relative paths. I also learned that hidden Linux files normally begin with a period.

## Directory and File Management

I used:

- `mkdir` to create directories
- `mkdir -p` to create nested directories
- `touch` to create an empty file
- `echo` to write text
- `cat` to display file contents
- `wc` to count lines and words
- `file` to identify a file type
- `find` to locate files and directories

## Redirection

I practiced two output-redirection operators:

- `>` replaces the existing contents of a file
- `>>` adds content without deleting existing content

## Copying and Moving Data

I used:

- `cp` to copy a file
- `cp -p` to copy a file while preserving metadata
- `mv` to move and rename files

Creating a backup before modifying an important configuration file reduces the risk of data loss.

## Safe Deletion

I used:

- `rm -i` to remove a file with confirmation
- `rmdir` to remove an empty directory
- `pwd` to verify my location before deleting anything

Linux command-line deletion can be permanent, so I verified the target and used interactive confirmation.

## Linux Documentation

I practiced:

- `command --help`
- `man`
- `history`
- `clear`

These tools allow administrators to find command documentation instead of depending entirely on memorization.

## Practical Challenge

I created an original technical report, copied it to a backup directory, renamed the backup, and verified both files from the command line.

## Skills Developed

- Linux filesystem navigation
- Directory organization
- File creation and inspection
- Output redirection
- File copying and renaming
- Safe deletion practices
- Command documentation
- Technical troubleshooting
- Portfolio documentation

## Security Lessons

- Always verify the current directory before deleting files.
- Do not place passwords, tokens, or credentials in terminal commands.
- Create backups before modifying important files.
- Use only the permissions and elevated access required for a task.

## Status

Completed<img width="1280" height="800" alt="04-linux-command-challenge png" src="https://github.com/user-attachments/assets/e851348e-e174-4723-98f3-8548368ab123" />
<img width="1280" height="800" alt="03-file-creation-content png" src="https://github.com/user-attachments/assets/ae0d2522-b59e-4956-93c1-ee627d663d67" />
<img width="1280" height="800" alt="02-linux-folder-structure png" src="https://github.com/user-attachments/assets/5a744ab4-86a5-4697-913b-897ab231f332" />
<img width="1280" height="800" alt="01-user-system-identification png" src="https://github.com/user-attachments/assets/f50d6162-4d93-4a0a-ae9a-704ee88f69bf" />
