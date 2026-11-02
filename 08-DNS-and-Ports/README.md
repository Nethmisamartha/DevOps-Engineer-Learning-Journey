# Linux DNS and Ports Practical

This section documents my hands-on practice with DNS resolution and network ports using Ubuntu Linux on Killercoda.

## Topics Covered

- Understanding DNS
- Checking DNS configuration
- Resolving domain names
- Understanding network ports
- Checking listening ports and services
- Identifying the HTTP port

## Commands Practiced

```bash
cat /etc/resolv.conf
getent hosts google.com
getent hosts github.com
ss -tuln
sudo ss -tuln | grep ':80'
```

## Practical Results

- Checked the DNS resolver configuration.
- Successfully resolved domain names.
- Viewed listening network ports.
- Identified Nginx listening on TCP port 80.

## Practical Environment

- Platform: Killercoda
- Operating System: Ubuntu Linux

## Learning Outcome

Learned the basics of DNS resolution, network ports, and checking listening services in Linux.
