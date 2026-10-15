# Lab-01-Network-Connectivity-and-DNS-Troubleshooting
Objective: Verify local IP configuration, test connectivity to a public IP address, and confirm DNS name resolution using macOS Terminal.

**Environment**\
Operating System: macOS\
Device: Mac\
Tools: ipconfig, ping, nslookup

**Test and Results**\
<h1>Test 1: Identify Local IP Addresses</h1>
<b>Command:</b> ipconfig getifaddr en0<br>
<b>Result:</b> 192.168.1.161<br>
<b>Finding:</b> The mac has a private IPv4 address assigned to its network interface

<h1>Test 2: Test Network Connectivity</h1>
<b>Command</b> nslookup Google.com<br>
<b>Result:</b> Resolved all four ICMP replies. Response times ranged from 6.846 ms to 11.517 ms<br>
<b>Finding:</b> The Mac successfully reached a public ip address using ICMP

<h1>Test 3: The DNS Resolution</h1>
<b>Command:</b> nslookup Google.com<br>
<b>Result:</b> DNS returned multiple IPv4 addresses for Google.com<br>
<b>DNS server reported:</b> 2600:4040:2f64: 5c00::1<br>
<b>Finding:</b> DNS resolution was successful. The non authoritative answer is normal when a recursive DNS resolver provides cached or retrieved DNS information

<h1>Conclusion</h1>
All three intial checks produced successful results. The mac had a local IPv4 address, reached a public IP address, and resolved a domain name through DNS.
These results establish a baseline for future troubleshooting exercises<br> 

<h1>Skills Demonstrated</h1>
1. Basic IP Addressing<br>
2. Network Connectivity Testing<br>
3. DNS Troubleshooting<br>
4. MacOS command-line utilities<br>
5. Technical documentation and evidence-based analysis

<h1>Next Steps</h1>
1. Identify the default network gateway<br>
2. Inspect DNS configuration<br>
3. Simulate a connectivity issue and document the troubleshooting process<br>

<img width="865" height="492" alt="image" src="https://github.com/user-attachments/assets/afe517d4-ca17-45b6-b5c2-a9f37f92aa31" />
