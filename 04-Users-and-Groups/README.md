# Linux Users and Groups Practical

This section documents my hands-on practice with Linux user and group management using Ubuntu Linux on Killercoda.

## Topics Covered

- Checking the current user
- Creating new Linux users
- Creating groups
- Adding users to groups
- Checking user and group information

## Commands Practiced

```bash
whoami
id
sudo adduser devopsuser
sudo groupadd devops
sudo usermod -aG devops devopsuser
groups devopsuser
getent group devops
```

## Practical Results

- Created a Linux user named `devopsuser`.
- Created a group named `devops`.
- Added `devopsuser` to the `devops` group.
- Verified user and group membership.

## Practical Environment

- Platform: Killercoda
- Operating System: Ubuntu Linux

## Learning Outcome

Gained practical experience managing Linux users and groups.

