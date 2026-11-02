# SSH and Security Practical

This section documents my hands-on practice with SSH and secure remote access using Ubuntu Linux on Killercoda.

## Topics Covered

- Understanding SSH
- Checking the SSH service
- Generating SSH key pairs
- Understanding public and private keys
- Configuring authorized_keys
- Setting SSH file permissions
- Testing SSH key-based authentication

## Commands Practiced

```bash
which ssh
sudo systemctl status ssh
ssh-keygen -t ed25519 -C "devops-practice"
ls -la ~/.ssh
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys
```

## Practical Results

- Generated an ED25519 SSH key pair.
- Configured the authorized_keys file.
- Set appropriate SSH file permissions.
- Successfully tested local SSH public-key authentication.

## Practical Environment

- Platform: Killercoda
- Operating System: Ubuntu Linux

## Learning Outcome

Learned the basics of SSH key generation, secure access, and public-key authentication.
