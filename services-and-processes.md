# Services and Processes

## Running Processes
```
ps aux
top
```

## Active Services
```
systemctl list-units --type=service
```

## Listening Services / Ports
```
ss -tulnp
```

## SOC Perspective
Unexpected or unknown services may indicate:
- misconfiguration
- persistence mechanisms
- potential compromise
