# Pick the Target
| Example | Description |
| :------:|:-----------:|
| nmap 192.168.34.3 | Scan that single IP specifified |
| nmap 192.168.43.5 192.168.34.3 | Scan many IPs at once |
| nmap 192.168.43.1-255 | Scan a range of IPs |
| nmap -iL (file_name) | Scan targets listed in a file |
| nmap -iR 100 | Scan random hosts (100) | 
| nmap -exclude 192.168.3.1 | Excluded the listed hosts |
| nmap www.youtube.com | Scan a domain |

# Picking Ports
| Switch | Example | Description |
|:------:|:-------:|:-----------:|
| -p | nmap 192.168.56.2 -p 22 | Scan a certain port (SSH port) | 
| -p | nmap 192.168.43.3. -p 1-100 | Scan a port range |
| -p | nmap 192.168.32.26 -p HTTP | Scan a port based on it's service name |
| -p- | nmap 192.169.234.6 -p- | Scan all ports | 
| -F | nmap 192.168.45.63 -F | Fast scan (100 ports) |
| -top-ports | 192.169.39.61 | -top-ports 1000 | Scan the top x ports |
