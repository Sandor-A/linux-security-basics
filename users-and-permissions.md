# Users and Permissions

## User & Group Enumeration
```
cat /etc/passwd
cat /etc/group
```

### Currently Logged-in Users
```
who
w
```

## File Permissions
```
ls -la
```

Permission format:
- r = read
- w = write
- x = execute

## Sensitive Files
- /etc/passwd
- /etc/shadow
- /etc/sudoers

## SOC Perspective
Misconfigured permissions and excessive privileges are common security risks and escalation paths.
