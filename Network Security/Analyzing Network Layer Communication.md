# Cybersecurity Incident Report: Network Traffic Analysis
> Securing Networks.
> 
> For more information, please refer to the provided [link](https://www.coursera.org/learn/networks-and-network-security?specialization=google-cybersecurity).
## Scenario

You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 

![LKXsnNIhT0e1mAz5AEvxog_d363c94e0a4f4a8b90b0be403f6ee1f1_mMBaLWLyXG2omYBcSdjuR8y5_S59zow1ZEPYdjNyJzA1B0r55nI9KmDosI8QHXcEwE51NxM3N5gNtMgSOyVDHyJVLZvZA7_jJtkzUKfxuqFUJPHs57vVVES-LbG5teR8eir4idaqsxFaYJhhVJZn-a_S-txb7zQNI](https://github.com/user-attachments/assets/b25ee23d-8c9a-416f-9c03-ef3c5a430817)

In the tcpdump log, you find the following information:

1. The first two lines of the log file show the initial outgoing request from your computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.

2. The third and fourth lines of the log show the response to your UDP packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the UDP packet was undeliverable to port 53 of the DNS server.

3. In front of each request and response, you find timestamps that indicate when the incident happened. In the log, this is the first sequence of numbers displayed: 13:24:32.192571. This means the time is 1:24 p.m., 32.192571 seconds.

4. After the timestamps, you will find the source and destination IP addresses. In the first line, where the UDP packet travels from your browser to the DNS server, this information is displayed as: 192.51.100.15 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is the source address, which in this example is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address for the DNS server: 203.0.113.2.domain. For the ICMP error response, the source address is 203.0.113.2 and the destination is your computers IP address 192.51.100.15.

5. After the source and destination IP addresses, there can be a number of additional details like the protocol, port number of the source, and flags. In the first line of the error log, the query identification number appears as: 35084. The plus sign after the query identification number indicates there are flags associated with the UDP message. The "A?" indicates a flag associated with the DNS request for an A record, where an A record maps a domain name to an IP address. The third line displays the protocol of the response message to the browser: "ICMP," which is followed by an ICMP error message.

6. The error message, "udp port 53 unreachable" is mentioned in the last line. Port 53 is a port for DNS service. The word "unreachable" in the message indicates the UDP message requesting an IP address for the domain "www.yummyrecipesforme.com" did not go through to the DNS server because no service was listening on the receiving DNS port.

7. The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 

Now that you have captured data packets using a network analyzer tool, it is your job to identify which network protocol and service were impacted by this incident. Then, you will need to write a follow-up report. 

As an analyst, you can inspect network traffic and network data to determine what is causing network-related issues during cybersecurity incidents. Later in this course, you will demonstrate how to manage and resolve incidents. For now, you only need to analyze the situation. 

This event, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor. 

## Provide a Summary of the Problem Found in the DNS and ICMP Traffic Log

* DNS server is down as a result of port 53 being unreachable. The ICMP request packet indicates that the packet has not been delivered to the port of DNS server successfully. <br>
* As we know, Port 53 is commonly used for DNS. That being said, the most likely issue is the DNS is not responding and it can be caused by DDOS attack against the DNS server. <br>
* The UDP protocol reveals that:  DNS is not responding. <br> 
This is based on the results of the network analysis, which show that the ICMP echo reply returned the error message: at port 53 , UDP port 53 unreachable.
* The port noted in the error message is used for: DNS Server <br>
The most likely issue is: DNS server is not responding. 

## Explain Your Analysis of the Data and Provide at Least One Cause of the Incident

* Time incident occurred: 1.23pm. <br>
* Explain how the IT team became aware of the incident: The customer reported to the company that they were unable to gain access to the company’s website. It was then reported that the message on the web page is “port unreachable”. <br>
* Explain the actions taken by the IT department to investigate the incident:
Security engineers had a look on the webpage and received an error “port being unreachable”. The team used TCPdump (network analyzer) to see the network traffic surrounding the website. <br>
* Note key findings of the IT department's investigation (i.e., details related to the port affected, DNS server, etc.): 
Go to website then load the webpage while monitoring the networks via TCPdump. It received lots of traffic. Sent UDP packets and received ICMP response to return to the host that indicates port 53 unreachable. <br>
* Note a likely cause of the incident:
Determine whether port 53 is working or not. IF it’s fine, then check firewall. <br>
-Firewall: The ability to block network traffic on specific ports. Port blocking can be used to stop or prevent an attack. <br>
-DOS: There could be flood of information being sent to the network device to make it crash or unable to function. The hacker could disable dns server using DOS attack. Or someone within the organization might have disabled port 53 on firewalls. <br>
