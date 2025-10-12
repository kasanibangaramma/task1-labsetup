1. Reconnaissance
2. Passive Recon:
3. whois example.com        
dig example.com         
nslookup example.com     
theHarvester -d example.com -l 100 -b google  
shodan host 8.8.8.8      
Google Dorking: site:example.com filetype:pdf
Active Recon:
nmap -sS ip    
nmap -sU ip
nmap -sV ip   
nmap -O ip     
OpenVAS scan (example):
omp -u admin -w password --scan-target ip
2. Network Traffic Analysis
Wireshark: Start capture on interface, apply filters like http or tcp.port==80
tcpdump -i eth0 -w capture.pcap
3. Firewall Basics
4. sudo iptables -L                   
sudo iptables -A INPUT -p tcp --dport 22 -j DROP    
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT  
