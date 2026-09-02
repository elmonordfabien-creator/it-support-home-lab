# Day 7 – Linux Users, Groups, and Permissions

## Objective

The objective of this lab was to manage Linux users, groups,
file ownership, and permissions while applying the principle
of least privilege.

## Why This Lab Matters

Linux permissions protect files, directories, applications, and
system resources. IT and cybersecurity professionals must ensure
that users receive only the access required for their assigned
responsibilities.

## Lab Environment

- Host operating system: Windows
- Virtualization platform: Oracle VirtualBox
- Guest operating system: Ubuntu Linux
- Primary lab user: fabienlab
- Security group: cyberteam
- Authorized test user: analyst1
- Unauthorized test user: visitor1

## User and Group Identification

I used `whoami`, `id`, `groups`, and `getent passwd` to identify
users, group memberships, IDs, home directories, and shells.

## Linux Permissions

I learned that Linux permissions apply to:

- Owner
- Group
- Others

The primary permissions are:

- `r` – read
- `w` – write
- `x` – execute

For directories, execute permission allows a user to enter or
traverse the directory.

## Managing Permissions

I used `chmod` in symbolic and numeric modes.

I configured a protected file with permission value `640`:

- Owner: read and write
- Group: read only
- Others: no access

## Managing Ownership

I used `chown` to assign:

- Owner: fabienlab
- Group: cyberteam

Ownership and permissions work together to determine access.

## User and Group Management

I created a `cyberteam` group and two test users. The authorized
user was added to the group, while the unauthorized user was
excluded.

I used `usermod -aG` to add a supplementary group without
removing existing group memberships.

## Least-Privilege Testing

I verified that:

- The owner could read and modify the protected file.
- The cyberteam member could read but not modify it.
- A user outside cyberteam could not read the file.

The expected Permission denied results confirmed that the access
controls were working correctly.

## Practical Challenge

I created and protected an incident report. I assigned the
correct owner and group, configured `640` permissions, and tested
access with both authorized and unauthorized users.

## Skills Developed

- Linux user identification
- Group management
- File and directory permissions
- Symbolic chmod
- Numeric chmod
- Ownership management with chown
- Access-control testing
- Least privilege
- Troubleshooting Permission denied errors
- Technical documentation

## Security Lessons

- Users should receive only the access required for their roles.
- Group permissions simplify access management.
- Permission denied can be an expected security result.
- File ownership and permissions must both be verified.
- Administrative access should be used only when necessary.

## Status

Completed<img width="1280" height="800" alt="04-permissions-security-challenge" src="https://github.com/user-attachments/assets/9464857b-2514-49dc-8811-9c0760135dcd" />
<img width="1280" height="800" alt="03-least-privilege-testing" src="https://github.com/user-attachments/assets/36e5e9ee-651c-45a0-b72c-131ff4807ce8" />
<img width="1280" height="800" alt="02-chmod-file-permissions" src="https://github.com/user-attachments/assets/b6f7b9d8-5ec8-43fc-a87a-349973a7b7bf" />
<img width="1280" height="800" alt="01-user-and-group-identification" src="https://github.com/user-attachments/assets/998bba60-9853-4dc2-af90-40782c24abd7" />
