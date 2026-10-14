# Linux Processes, Services, and Logs

## Objective
Learn how to inspect Linux processes, manage systemd services, and investigate system logs.

## Environment
- Operating system: Ubuntu Server
- Virtualization: VirtualBox
- Service investigated: OpenSSH

## Commands Practised
- `ps` — list processes
- `pgrep` — locate processes
- `top` — monitor system activity
- `systemctl` — inspect and manage services
- `journalctl` — examine system logs
- `ss` — inspect listening sockets

## Investigation
1. Inspected running processes and their owners.
2. Started and safely terminated a test process.
3. Checked SSH service status and startup configuration.
4. Reviewed recent service and system logs.
5. Inspected listening network sockets.

## Findings
SSH status active and running, on startup as well. No failed services, listening enabled on all ports (0.0.0.0)

## Security Relevance
Unexpected processes, unnecessary services, exposed listening ports, and unusual log activity can indicate misconfiguration or suspicious activity. Each finding requires investigation and context.

## Remediation
Disable unnecessary services only after confirming they are not required. Investigate unexpected processes and errors before taking action. Restrict network exposure and preserve relevant logs during an investigation.
