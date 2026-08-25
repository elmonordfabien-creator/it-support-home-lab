<img width="479" height="587" alt="05-labuser-modify-permission png" src="https://github.com/user-attachments/assets/762b9373-5ec9-43bc-a68a-2cb237ef8477" />
<img width="1343" height="601" alt="04-access-denied-test png" src="https://github.com/user-attachments/assets/ca7dedbe-027b-41f6-8890-9c4076449872" />
<img width="472" height="587" alt="03-labuser-read-permissions png" src="https://github.com/user-attachments/assets/1d09ac32-c4a7-4776-8276-610d9cf00e3e" />
<img width="1116" height="714" alt="02-command-prompt-practice png" src="https://github.com/user-attachments/assets/a8e67046-684f-453f-8167-dc3af5f6edd3" />
<img width="951" height="317" alt="01-lab-folder-structure png" src="https://github.com/user-attachments/assets/353690cc-ed71-4175-86c4-213d98354079" />
# Day 3 – Windows Files and Permissions

## Objective

The objective of this lab was to practice Windows file management, Command Prompt navigation, user permissions, and access-denied troubleshooting.

## Activities Completed

- Created a Windows lab folder structure
- Practiced basic Command Prompt commands
- Configured Read permission for a standard user
- Reproduced an access-denied problem
- Identified the missing permission
- Granted Modify permission
- Verified that the user could create and modify a file

## Commands Practiced

- `cd`
- `dir`
- `cd ..`
- `mkdir`
- `type`
- `echo`

## Problem

LabUser could read files but could not create or modify files in the shared folder.

## Solution

I reviewed the folder’s Security settings and granted Modify permission to LabUser.

## Verification

LabUser successfully created and modified a test file.

## Security Principle

I applied the principle of least privilege by granting Modify permission instead of Full control.

## Status

Completed
