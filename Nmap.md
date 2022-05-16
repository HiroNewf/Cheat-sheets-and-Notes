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
