Name:S.Mukesh
Company:CODETEECH IT SOLUTIONS
Domain:Cyber Security
Duration:July to August 2025



Objective

     To design and implement a personal firewall on Parrot OS using iptables, which controls incoming and outgoing network traffic based on user-defined security rules. The         goalis to protect the system from unauthorized access while allowing legitimate communication.

Tools & Technologies

     Parrot OS (Debian-based Linux distribution for security professionals)

     iptables (Linux firewall utility)

     netfilter-persistent (to save firewall rules across reboots)

     Optional: bash scripting (to automate firewall configuration)

Implementation Steps

     Understand firewall concepts: INPUT, OUTPUT, FORWARD chains.

     Flush old rules to start with a clean slate.

     Set default policies: Drop all traffic by default.

      Allow loopback traffic for local system processes.

     Allow established and related connections (so replies to your requests are accepted).

     Whitelist essential services:

     DNS (port 53)

     Web browsing (HTTP port 80, HTTPS port 443)

     SSH (port 22, optional)

     Log dropped packets for monitoring suspicious activity.

     Save rules permanently using iptables-persistent.

Example Ruleset

     Default: Deny all traffic

     Allow: Outgoing DNS, HTTP, HTTPS

     Allow: Incoming SSH (if remote access needed)

     Allow: Loopback traffic

     Log: Dropped packets

Expected Output

     System will block all unauthorized traffic by default.

     User can browse the web (HTTP/HTTPS), resolve domains (DNS).

     SSH connections allowed (if configured).

     Logs show details of blocked attempts.

Skills Learned

     Linux firewall configuration with iptables

     Network traffic filtering (whitelisting vs blacklisting)

     Security hardening in Parrot OS
 
     Automation using shell scripting

     Logging and monitoring dropped packets

     
     Security lab experiments in Parrot OS

     Base project for advanced intrusion detection or monitoring tools

✅ This makes your project a hands-on security exercise showing how to build and manage a firewall from scratch, not just using a prebuilt GUI.
