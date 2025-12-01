# Load-Balancer-of-Web-Servers-on-Azure

## Features:
1. Traffic Distribution: Azure Load Balancer routes HTTP requests to healthy backend VMs.
2. High Availability: VMs deployed in an availability set with automatic health probes.
3. Fault Tolerance: Automatic failover when a backend server becomes unresponsive.
4. Secure Access: Network Security Groups (NSGs) restrict traffic to essential ports.

## Architecture:
Client → Azure Load Balancer (Public IP) → Backend Pool (VM-01, VM-02) → IIS Web Server

## Future Enhancements
1. Enable HTTPS with SSL/TLS.
2. Implement autoscaling with Virtual Machine Scale Sets.
3. Integrate a Web Application Firewall (WAF).
4. Extend to multi-region deployment using Azure Traffic Manager.
