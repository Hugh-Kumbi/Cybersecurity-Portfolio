# 1.1 Analyzing Network Traffic with Wireshark

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 

In this scenario, you’re a security analyst investigating traffic to a website.

You’ll analyze a network packet capture file that contains traffic data related to a user connecting to an internet site. The ability to filter network traffic using packet sniffers to gather relevant information is an essential skill as a security analyst.

You must filter the data in order to:
1. Identify the source and destination IP addresses involved in this web browsing session.
2. Examine the protocols that are used when the user makes the connection to the website.
3. Analyze some of the data packets to identify the type of information sent and received by the systems that connect to each other when the network data is captured.

### Task 1: Exploring Data With Wireshark

In this task, you must open a network packet capture file that contains data captured from a system that made web requests to a site. You need to open this data with Wireshark to get an overview of how the data is presented in the application.

### Task 2: Applying a Basic Wireshark Filter and Inspect a Packet

In this task, you’ll open a packet in Wireshark for more detailed exploration and filter the data to inspect the network layers and protocols contained in the packet.

### Task 3: Using Filters to Select Packets

In this task, you’ll use filters to analyze specific network packets based on where the packets came from or where they were sent to. You’ll explore how to select packets using either their physical Ethernet Media Access Control (MAC) address or their Internet Protocol (IP) address.

### Task 4: Using Filters to Explore DNS Packets

In this task, you’ll use filters to select and examine DNS traffic. Once you‘ve selected sample DNS traffic, you’ll drill down into the protocol to examine how the DNS packet data contains both queries (names of internet sites that are being looked up) and answers (IP addresses that are being sent back by a DNS server when a name is successfully resolved).

### Task 5: Using Filters to Explore TCP Packets

In this task, you’ll use additional filters to select and examine TCP packets. You’ll learn how to search for text that is present in payload data contained inside network packets. This will locate packets based on something such as a name or some other text that is of interest to you.

### Expectations

By completing this activity, you will:

1. Gain practical experience using Wireshark to:
  * Open saved packet capture files.
  * View high-level packet data.
  * Use filters to inspect detailed packet data.
2. Achieve an important milestone on your journey toward understanding how to use network packet analysis tools to examine network traffic.

# Capturing and Filtering Network Traffic with tcpdump

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 

In this scenario, you’re a network analyst who needs to use `tcpdump` to capture and analyze live network traffic from a Linux virtual machine.

The lab starts with your user account, called `analyst`, already logged in to a Linux terminal.

Your Linux user's home directory contains a sample packet capture file that you will use at the end of the lab to answer a few questions about the network traffic that it contains.

## Task 1: Identify Network Interfaces

In this task, you must identify the network interfaces that can be used to capture network packet data.

## Task 2: Inspect the Network Traffic of a Network Interface with Tcpdump

In this task, you must use `tcpdump` to filter live network packet traffic on an interface.

### Exploring network packet details 

In this example, you’ll identify some of the properties that `tcpdump` outputs for the packet capture data you’ve just seen.

## Task 3: Capture Network Traffic with Tcpdump

In this task, you will use `tcpdump` to save the captured network data to a packet capture file.

## Task 4: Filter the Captured Packet Data

In this task, use `tcpdump` to filter data from the packet capture file you saved previously.











