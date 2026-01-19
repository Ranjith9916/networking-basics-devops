# Network Analysis Report

## System IP Details
- Command used: ip a
- IPv4 Address: 192.168.x.x
- Interface: eth0

## Connectivity Test
- Command: ping 8.8.8.8
- Result: Successful
- Average latency: 41.4 ms

## Open Ports
- Command: ss -tuln
- Active ports: 22, 80

## DNS Resolution
- Command: nslookup google.com
- Resolved IP: 142.250.193.46

## Traceroute
- Command: traceroute google.com
- Total hops: 30

## Network Failure Test
- Interface disabled and enabled successfully
- Internet unavailable during downtime

## Final Conclusion
This task helped understand how systems communicate over IP networks using DNS, routing, and ports.
