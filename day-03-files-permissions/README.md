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
