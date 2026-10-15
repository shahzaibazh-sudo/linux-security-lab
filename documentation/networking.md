# Linux Networking Fundamentals

## Objective
Inspect network interfaces, routes, listening ports, DNS resolution, and HTTP/HTTPS connectivity on Ubuntu Server.

## Environment
- Operating system: Ubuntu Server
- Virtualization: VirtualBox

## Commands Practised
- `ip addr` — inspect network interfaces and addresses
- `ip route` — inspect routes and default gateway
- `ss` — inspect listening sockets
- `getent hosts` — test hostname resolution
- `ping` — test ICMP connectivity
- `curl` — inspect HTTP/HTTPS responses
- `wget` — retrieve a test web page

## Security Analysis
Explain which services are listening, whether their network exposure is expected, and which additional controls may be appropriate.

## Limitations
A listening port does not automatically mean it is externally reachable. Routing, host and guest firewalls, and VirtualBox network mode affect reachability.

## Lessons Learned

