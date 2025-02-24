# Infrastructure Monitoring and Automation Project

A system that monitors server health, network performance, and service uptime while automating routine checks, alerts, and common issue remediation.

**Key Skills Demonstrated:**
- System Monitoring
- Automation Scripting (PowerShell)
- Proactive Maintenance
- Security Best Practice

## Requirements Analysis

### System Performance Metrics
1. **CPU Utilization**  
   Monitor overall processing load to detect performance spikes.
2. **Memory Usage**  
   Track memory consumption to ensure applications run efficiently.
3. **Disk I/O & Disk Space**  
   Assess disk input/output and available storage to prevent bottlenecks.
4. **Network Throughput & Latency**  
   Evaluate data transfer speeds and response times to diagnose network issues.
5. **Uptime/Availability**  
   Measure system uptime to verify consistent availability and quickly identify outages.

### Windows Server-Specific Metrics
1. **Event Logs Monitoring (System, Application, Security)**  
   Track errors, warnings, and significant system events to facilitate troubleshooting.
2. **Active Directory Health**  
   Monitor replication status, authentication failures, and domain controller response times to ensure proper user and service authentication.
3. **Group Policy Processing**  
   Verify policy update frequency and detect errors in policy application to maintain consistent configurations.
4. **DNS and DHCP Metrics**  
   Monitor query response times, lease allocation, and error rates to ensure reliable network communications.
5. **DFS (Distributed File System) Replication**  
   Track replication latency and error counts to guarantee consistent file synchronization across servers.

### Virtualization and Infrastructure Metrics
1. **VM Resource Utilization**  
   Monitor CPU, memory, and disk usage per virtual machine (e.g., using VMware) to assess VM health and performance.
2. **Host Performance Metrics**  
   Evaluate aggregated resource consumption and load balancing across hosts to ensure optimal hardware utilization.

### Security and Patch Management Metrics
1. **Security Event Monitoring**  
   Track failed login attempts, unauthorized access, and firewall events to detect potential security breaches.
2. **Patch Compliance and Update Status**  
   Monitor the percentage of systems that are up to date, pending patches, and the success rate of patch deployments to maintain security.
3. **Script Execution and Remediation Success**  
   Evaluate the frequency and success of PowerShell automation scripts and review error logs from automated tasks to ensure reliable remediation.

### Infrastructure Components

#### Server Infrastructure
1. **Windows Server Health**  
   Monitor core performance metrics (CPU, memory, disk I/O) on Windows Servers.
2. **Active Directory**  
   Track domain controller performance, replication status, and authentication to ensure smooth operations.
3. **Event Logs**  
   Regularly review System, Application, and Security logs for any errors or warnings.

#### Network Infrastructure
1. **Core Networking Devices**  
   Monitor routers, switches, and firewalls to ensure stable and reliable connectivity.
2. **DNS and DHCP Services**  
   Ensure fast, accurate responses and proper lease management for network devices.
3. **Network Performance**  
   Track latency, throughput, and error rates to identify and resolve potential bottlenecks.

#### Virtualization Environment
1. **VM Hosts and Virtual Machines**  
   Monitor resource utilization (CPU, memory, storage) for both hosts and individual VMs.
2. **Hypervisor Health**  
   Ensure optimal performance and effective load balancing within the virtualized environment.

#### Remote Desktop and User Services
1. **Remote Desktop Services (RDS)**  
   Monitor session performance, connection stability, and resource usage to support remote work.
2. **User Authentication Services**  
   Validate performance and reliability of systems supporting user access and identity management.

#### File and Storage Systems
1. **Distributed File System (DFS)**  
   Track replication latency and error counts to maintain consistent file synchronization.
2. **Storage Capacity and Disk I/O**  
   Monitor trends in storage usage and disk performance for critical data stores.

#### Automation and Patch Management
1. **Automation Scripts**  
   Track the execution and success of PowerShell scripts that perform routine health checks and remediate common issues.
2. **Patch Management Systems**  
   Monitor patch deployment success, compliance status, and update frequency (using tools like BigFix or custom scripts).

#### Security and Compliance
1. **Security Event Monitoring**  
   Monitor failed logins, unauthorized access attempts, and firewall events to promptly detect breaches.
2. **Compliance Checks**  
   Regularly assess system configurations and patching practices to ensure adherence to security best practices.
