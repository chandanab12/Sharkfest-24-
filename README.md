# Sharkfest-24-

- Gerald Comb - creator of wireshark

  Capturing Traffic - CLI

 - tcpdump - packet capture utility available on unix systems
 - windump - tcpdump ported to windows
 - tshark - Wireshark in CLI form
 - Dumpcap - raw packet capture utility (used seldom) captures packets to a file, without any interpretation.

Network tap - allows our ethernet connection into a device - makes a copy of everybit that comes through without disturbing the flow of traffic. 

ARP - Address Resolution protocol

To get the destination MAC Address 


**TCP**
Conversation completeness - it tells you whether a conversation has been captured completely or not. 
The no. beside data[] is the data captured. 

![image](https://github.com/chandanab12/Sharkfest-24-/assets/54497878/d4d54a28-2033-4195-8bad-320b48d93283)


It is added in a binary seq. 1-32 and then resets. 1,2,4,8,16,32....... 


Sake Blok - Pre conf class II

Filter types - 2 - capture and filter

Berkeley packet filter (BPF) 


all tcp.port gt 5000         all tcp.port>5000 both give the same value. all packets with port no greater than 5000. 


ip.src#2==162.159.25.5   Layer and occurrences 
The layers are the protocol layers found under frame information. Protocols in frame: []
Most common one is ICMP. it goes left to right. 



-------------------------------------------------------------------------------------------------------------------------------------------------------------------

logray - can use AWS CloudTrail logs - read more abt it 


Real-World Post Quantum TLS - Peter Wu 

TLS decryption in wireshark using the TLS key log file 
edit - pref - protocols - TLS - (pre) Master secret log filename
Ensure Protocol preferences - TCP - Reassemble out of order segments. 

Read about khyber - post quantum 

PQ KEX - readdddddd 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Monitoring and troubleshooting without Packet traces - Leveraging Cyber Tools - Chris Hull - Capital One  

N/w performance monitoring - expensive but provides great insights. 

Open source cyber tools 
- Wireshark
- Nagios Core (IDS)
- Snort
- Zeek (IDS)

https://github.com/b-yond-infinite-network/sharkfest-us-2024/tree/main

https://colab.research.google.com/github/b-yond-infinite-network/sharkfest-us-2024/blob/main/notebooks/wifi-health-checks-analysis.ipynb?authuser=2#scrollTo=UvGPFfsscTFl

Lab answers from Ross Class

https://www.dropbox.com/scl/fi/esk8g9j029yicsgssosna/WiresharkSkills1.zip?rlkey=h49yfkgat8cmiqicxs13uvhum&e=4&dl=0

https://blog.packet-foo.com/2015/03/tcp-analysis-and-the-five-tuple/
https://www.zama.ai/about

https://en.wikipedia.org/wiki/Kyber

https://pq.cloudflareresearch.com/

https://lekensteyn.nl/logitech-unifying.html

https://zeek.org/

https://packetbomb.com/category/text/

https://www.b-yond.com/comparative-analysis

https://mininet.org/
https://blog.codavel.com/http2-multiplexing

https://github.com/packetpioneer/sfus24/blob/main/sf24us_quic.pcapng

https://www.fastly.com/blog/minimizing-ossification-risk-is-everyones-responsibility/
 


