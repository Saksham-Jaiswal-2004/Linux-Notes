## Chapter 8: Linux Networking Commands

1. ping - to check connection and data transfer
2. netstat - give info and stats about your network
3. ifconfig - All network interfaces in your system connected with NIC (Network Interface Card)
4. traceroute - gives the complete route through all ip addresses from your device to destination
5. tracepath - does the same thing as traceroute but in a clean way
6. mtr - (My Trace Route) its like the combination of ping + tracepath
7. nslookup - gives your ip address along with the destination's ip and name addresses
8. telnet - it is a network utility used to establish connections to remote hosts or test port connectivity using the Telnet protocol.  It operates primarily on **port 23** but is commonly employed by system administrators to verify if specific service ports (e.g., HTTP port 80, SMTP port 25) are open and responsive.
9. hostname - Returns the hostname and helps to change hostname
10. ip - To check your device's ip address, 
    ex. ip address show
11. iwconfig - Shows wireless connections in your device
12. ss - same as netstat
13. arp - (Address Resolution Protocol) to find MAC addresses of netowrking hardwares connected
14. dig - To get all the details about ip address of any site
15. nc (netcat) - 
16. whois - To get all the domain details of any site
17. ifplugstatus - Tells if our interfaces are working or not


18. curl - to call API endpoints, 
    ex. curl -X GET {endpoint}
    ex. curl -X GET {endpoint} | jq - to get pretify response
19. wget - to download something, ex. wget {link}
20. iptables - is a user-space utility program used to configure the **IP packet filter rules** of the Linux kernel firewall, which is implemented via the **Netfilter** framework.  It allows system administrators to define, manage, and inspect rules that control how network traffic is handled, including filtering, **Network Address Translation (NAT)**, and packet alteration.
21. watch - to recursively monitor output of any command and refreshes output every 2s,
    to change time - watch -n {new time in sec} {command to watch}
22. nmap - Network map, to scan a website
23. route - it is a tool for manipulating the Linux IP routing table