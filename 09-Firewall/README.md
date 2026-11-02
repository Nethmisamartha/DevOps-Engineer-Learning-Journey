# Linux Firewall Practical

This section documents my hands-on practice with firewall rules using Ubuntu Linux on Killercoda.

## Topics Covered

- Understanding Linux firewalls
- Checking UFW firewall status
- Allowing SSH traffic
- Allowing HTTP traffic
- Understanding firewall rules

## Commands Practiced

```bash
sudo ufw status
sudo ufw allow 22/tcp
sudo ufw allow 80/tcp
```

## Practical Results

- Checked the UFW firewall status.
- Added a rule to allow SSH traffic on port 22.
- Added a rule to allow HTTP traffic on port 80.
- Verified that the UFW firewall remained inactive in the Killercoda environment.

## Practical Environment

- Platform: Killercoda
- Operating System: Ubuntu Linux

## Learning Outcome

Learned how to check UFW status and create basic firewall rules for SSH and HTTP traffic.
