# python_automation_kali_linux
Python scripting within the Kali Linux environment to automate common preliminary cybersecurity task, such as a network scan - preliminary penetration test.


1. Initiating Parallel DNS Resolution: This indicates that Nmap is resolving the DNS of the target system.

2. Initiating Connect Scan: Nmap is performing a TCP connect scan on the target system, scanning 1023 ports.

3. Connect Scan Timing: This provides the progress of the connect scan, showing the percentage completed and the estimated time remaining.

4. Completed Connect Scan: Indicates the completion of the connect scan, showing the elapsed time and the total number of ports scanned.

5. Initiating Service Scan: Nmap is initiating a service scan to detect open ports and services running on the target system.

6. NSE (Nmap Scripting Engine): Nmap scripting engine is being used to gather additional information about the target system.

7. Nmap Scan Report: Provides a summary of the scan results, indicating that the target system is up, but all scanned ports are in ignored states.

8. Filtered Ports: Indicates that all 1023 scanned TCP ports are in a filtered state, meaning they didn't respond to the scan.

(Note that a 1-1023 port scan was done because of minimizing the computer's workload per scan. Completing the 65,000+ port scans can be scanned
 in a segmented fashion ex. 1-1023, 1024-2025, 2026-3027, etc. Each scan should be completed and labeled in order to reduce the stress on 
 the CPU to peform the scan. Scanning all 65,000+ ports on a system is not feasible especially with a common testing system).
