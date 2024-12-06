## Packet Analysis 

## Task 1. Explore Data with Wireshark
1. To open the packet capture file, I double-clicked the sample file on the Windows desktop and this started Wireshark.

![Open the Packet Capture file](https://github.com/user-attachments/assets/37427b29-195f-4e45-a2f6-cb1000d44407)

2. Once Wireshark started I double-clicked the Wireshark title bar next to the sample.pcap filename in order to maximize the Wireshark application window.

***Note:** Not all the data packets are the same color. Coloring rules are used to provide high-level visual cues to help with quickly classifying the different types of data. Since network packet capture files can contain large amounts of data, we can use coloring rules to quickly identify the data that is relevant. The example packet below lists a group of **light blue** packets that all contain `DNS` traffic, followed by **green** packets that contain a mixture of `TCP` and `HTTP` protocol traffic.*
  
![Capture File](https://github.com/user-attachments/assets/3f1cd043-14c1-4c66-9002-d8fe114b529e)

* A lot of network packet traffic is listed, and this requires the use of filters in order to find the information during an investigation.

An overview of the key property columns listed for each packet: 
* **No.**: The index number of the packet in this packet capture file
* **Time**: The timestamp of the packet
* **Source**: The source IP address
* **Destination**: The destination IP address
* **Protocol**: The protocol contained in the packet
* **Length**: The total length of the packet
* **Info**: Some infomation about the data in the packet (the payload) as interpreted by Wireshark

## Task 2. Apply a Basic Wireshark Filter and Inspect a Packet

### In this task, I had to open a packet in Wireshark for a more detailed exploration and to filter the data in order to inspect the network layers and protocols contained in the packet.

2. After entering and applying `ip.addr == 142.250.1.139` into the search tab the list of packets displayed is now significantly reduced and contain only packets where either the source or the destination IP address matches the address I've entered. Now only two packet colors are used: **light pink** for `ICMP` protocol packets and **light green** for `TCP` (and `HTTP`, which is a subset of `TCP`) packets.

![ip.addr == 142.250.1.139 Search](https://github.com/user-attachments/assets/f958f17d-4a76-44ba-913b-5056ee13b685)

3. After double-clicking the first packet that lists `TCP` as the protocol it opens a packet details pane window as shown below:

![ip.addr == 142.250.1.139 Search TCP Protocol](https://github.com/user-attachments/assets/5eca4994-f9ad-412d-91d3-51fd99049bf6)

The upper section of the window above contains subtrees where Wireshark provides an analysis of the various parts of the network packet. The lower section of the window contains the raw packet data displayed in hexadecimal and ASCII text. There is also placeholder text for fields where the character data does not apply, as indicated by the dot (“.”).

4. Double-clicking on the first subtree in the upper section with the word **Frame** provides details about the overall network packet, or frame. The details include the **frame length** and the **arrival time** of the packet that is information about the entire packet of data.

![Frame view](https://github.com/user-attachments/assets/6d2d0491-ef53-467b-bf4a-4987950dbad4)

5. Double-clicking the Ethernet II subtree, produces an item which contains details about the packet at the Ethernet level, including the **source** and **destination MAC addresses** and the type of **internal protocol** that the Ethernet packet contains.

![Ethernet II subtree view](https://github.com/user-attachments/assets/bf0834d0-59ef-451e-a825-894175b8ca79)

6. Double-clicking the Internet Protocol Version 4 subtree provides packet data about the **Internet Protocol (IP)** data contained in the Ethernet packet. It contains information such as the source and destination **IP addresses** and the **Internal Protocol** (for example, `TCP` or `UDP`), which is carried inside the IP packet.

![Internet Protocol Version 4 subtree](https://github.com/user-attachments/assets/3a4af9b6-25bd-4d94-a0a6-071c6c9a3009)

7. Double-clicking the Transmission Control Protocol subtree produces detailed information about the `TCP` packet, including the source and destination `TCP` ports, the `TCP` sequence numbers, and the `TCP` flags. The **source port** and **destination port** listed here match the **source** and **destination ports** in the info column of the summary display for this packet in the list of all of the packets in the main Wireshark window.

![Transmission Control Protocol subtree](https://github.com/user-attachments/assets/51fa8258-04b4-4bbd-96bc-74096f22b474)

8. In the Transmission Control Protocol subtree, we can scroll down and double-click on the **Flags**. This provides a detailed view of the `TCP` flags set in this packet.

![Transmission Control Protocol subtree Flags](https://github.com/user-attachments/assets/27f86a35-4763-41a7-93d6-d7eeb5efb01c)

## Task 3. Using filters to select packets

### In this task, I used filters to analyze specific network packets based on where the packets came from or where they were sent to. I also explored how to select packets using both their physical Ethernet Media Access Control (MAC) address and their Internet Protocol (IP) address.

1. After entering and applying `ip.src == 142.250.1.139` into the search tab a filtered list is returned with fewer entries than before. It contains only packets that came from `142.250.1.139`.

![ip.src == 142.250.1.139](https://github.com/user-attachments/assets/1fc6c1a9-6afc-4d71-8403-650e6353a74d)

2. After entering and applying `ip.dst == 142.250.1.139` into the search tab a filtered list is returned that contains only packets that were sent to `142.250.1.139`.

![ip.dst == 142.250.1.139](https://github.com/user-attachments/assets/fe009584-70ca-4da2-a904-fed2ef9e8e96)

3. By entering the filter `eth.addr == 42:01:ac:15:e0:02` we can select traffic to or from a specific **Ethernet MAC address**. This filters traffic related to one **MAC address**, regardless of the other protocols involved.

![eth.addr == 42:01:ac:15:e0:02](https://github.com/user-attachments/assets/2ac9bf5b-c9b0-4f31-b4c0-99e2ce545b49)

4. Double-clicking the first packet in the list and then the **Ethernet II** subtree the MAC address specified in the filter is listed as either the source or destination address in the expanded **Ethernet II** subtree.

![Ethernet II](https://github.com/user-attachments/assets/5b98b6ce-7d8a-47e8-8724-b4147b4b6bb0)

5. Double-clicking the **Internet Protocol Version 4** subtree to expand it and scrolling down until the **Time to Live** and **Protocol** fields appear. The **Protocol** field in the Internet Protocol Version 4 subtree indicates which **IP internal protocol** is contained in the packet.

![Internet Protocol Version 4](https://github.com/user-attachments/assets/76d1f8b7-c744-4b54-8b39-806b4a5f1fac)

## Task 4. Using filters to explore DNS packets

### In this task, I used filters to select and examine DNS traffic. Once I‘ve selected sample DNS traffic, I’ll drill down into the protocol to examine how the DNS packet data contains both queries (names of internet sites that are being looked up) and answers (IP addresses that are being sent back by a DNS server when a name is successfully resolved).

1. By entering the filter `udp.port == 53` to select **UDP port 53** traffic will list traffic related to `DNS` queries and responses only because `DNS` traffic uses **UDP port 53**.

![udp.port == 53](https://github.com/user-attachments/assets/a08736a5-0bd4-498c-b46f-2cc6f52bd71a)

2. Double-clicking the **first packet** in the list opens the detailed packet window. 

![First packet](https://github.com/user-attachments/assets/b2991353-d0fb-4fad-aef9-ed1f87ef2e5e)

3. Scrolling down and double-clicking the **Domain Name System (query)** subtree expands it. 

![Domain Name System (query) subtree](https://github.com/user-attachments/assets/f03f4318-63cc-4f55-8ab0-78df4d235635)

4. Scrolling down once again and double-clicking **Queries** expands it.

![Queries](https://github.com/user-attachments/assets/2abd3e61-84de-4d4d-b953-7dda79fd883f)

5. The detailed window clearly shows that the name of the website that was queried is `opensource.google.com.`

![opensource.google.com](https://github.com/user-attachments/assets/75ca68d3-c729-4f40-bf29-632fbbb1b32a)

6. Double-clicking on the **fourth packet** in the list opens the detailed packet window.

![fourth packet](https://github.com/user-attachments/assets/2cf20d11-cddc-48c7-8bf7-e1e5417884d6)

7. Scrolling down and double-clicking the **Domain Name System (query)** subtree to expand it, and double-clicking **Answers**, which is in the **Domain Name System (query)** subtree. The **Answers** data includes the name that was queried `(opensource.google.com)` and the addresses that are associated with that name. 

![Answers](https://github.com/user-attachments/assets/8a288f41-9085-4bec-9ac9-adbe028b3287)

## Task 5

### In this task, I’ll use additional filters to select and examine TCP packets. I’ll practice how to search for text that is present in payload data contained inside network packets. This will locate packets based on something such as a name or some other text that is of interest to me.

1. By entering the filter `tcp.port == 80` we can select **TCP port 80** traffic because **TCP port 80** is the default port that is associated with web traffic. Based on the information shown quite a few packets were created when the user accessed the web page `http://opensource.google.com`.

![image](https://github.com/user-attachments/assets/0017387e-4089-400d-b925-849792eaf594)

2. Double-clicking the **first packet** in the list. The **Destination IP address** of this packet is `169.254.169.254`.

![image](https://github.com/user-attachments/assets/e7cc06d9-9570-40b0-b060-e0816312a4fc)

3. After entering and applying `tcp contains "curl"` into the search tab **TCP packet** data that contains specific text data is returned. The filter, filters to packets containing web requests made with the `curl` command in this sample packet capture file.

![tcp contains "curl"](https://github.com/user-attachments/assets/a8c54604-32b9-4b52-afc3-c0f7abc923df)
