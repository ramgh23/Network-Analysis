# Network-Analysis
This report summarizes a local network security assessment to find vulnerabilities and enhance security. Tools like Nmap, Nikto, Zenmap, Wireshark, Netcat, and OpenVAS were used to scan devices, check ports, and identify weaknesses. A network map is included, along with recommendations to close open ports, secure services, and monitor traffic.

#commands
Get IP of network using command >ifconfig
Nmap command to find hosts in network >nmap 10.0.2.6/24
Nmap command to find OS of hosts >nmap 10.0.2.6/24 –O

vulnerability scanning >nmap --script vuln <target IP>
using nikto tool >nikto –h <target IP>

Manual port scan using Netcat utility >nc –zv <target ip> <port range>

wireshark filters
>tcp - for TCP traffic.
>ssh - for SSH traffic.
>http - to see HTTP traffic
>ftp - for FTP traffic.
>icmp - for ICMP traffic
>dns - to view DNS requests and responses
>tcp.port = = <port number> -to show traffic on specific port 
>ip.addr = = <target ip> - to display traffic involving a specific IP address






