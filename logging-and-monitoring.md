# Logging and Monitoring Basics

## Common Log Locations
- /var/log/auth.log
- /var/log/syslog
- /var/log/messages

## Viewing Logs
```
cat auth.log
less syslog
tail -f syslog
```

## Authentication Events
```
grep "Failed password" /var/log/auth.log
```

## SOC Perspective
Logs are critical for:
- incident detection
- alert investigation
- timeline reconstruction
