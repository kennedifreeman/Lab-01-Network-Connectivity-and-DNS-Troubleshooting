# Lab-01-Network-Connectivity-and-DNS-Troubleshooting
Objective: Verify local IP configuration, test connectivity to a public IP address, and confirm DNS name resolution using macOS Terminal.

**Environment**\
Operating System: macOS\
Device: Mac\
Tools: ipconfig, ping, nslookup

**Test and Results**\
<h1>Test 1: Identify Local IP Addresses</h1>
**Command:** ipconfig getifaddr en0\
**Result:** 192.168.1.161\
**Finding:** The mac has a private IPv4 address assigned to its network interface

<h1>Test 2: Test Network Connectivity</h1>
**Command:** nslookup Google.com\
**Result:** Resolved all four ICMP replies. Response times ranged from 6.846 ms to 11.517 ms\
**Finding:** The Mac successfully reached a public ip address using ICMP

<h1>Test 3: The DNS Resolution</h1>
**Command:** nslookup Google.com\
**Result:** DNS returned multiple IPv4 addresses for Google.com\
**DNS server reported:** 2600:4040:2f64: 5c00::1\
**Finding:** DNS resolution was successful. The non authoritative answer is normal when a recursive DNS resolver provides cached or retrieved DNS information

<h1>Conclusion</h1>
All three intial checks produced successful results. The mac had a local IPv4 address, reached a public IP address, and resolved a domain name through DNS\
These results establish a baseline for future troubleshooting exercises\ 

<h1>Skills Demonstrated</h1>
-Basic IP Addressing\
-Network Connectivity Testing\
-DNS Troubleshooting\
-MacOS command-line utilities\
-Technical documentation and evidence-based analysis

<h1>Next Steps</h1>
-Identify the default network gateway\
-Inspect DNS configuration\
-Simulate a connectivity issue and document the troubleshooting process\

<img width="865" height="492" alt="image" src="https://github.com/user-attachments/assets/afe517d4-ca17-45b6-b5c2-a9f37f92aa31" />
