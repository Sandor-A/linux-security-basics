# System Inspection Basics

## Goal
Understand the current state of a Linux system from a security perspective.

## Key Checks

### OS & Kernel Information
```
uname -a
cat /etc/os-release
```

### Uptime & System Load
```
uptime
top
htop
```

### Disk Usage
```
df -h
lsblk
```

### Network Information
```
ip a
ip route
ss -tulnp
```

## SOC Perspective
System inspection is often the first step during incident response to understand:
- system health
- unexpected services
- suspicious network activity
