# Building Resilience: Detection and Incident Response

This folder contains exercises, solutions, and supporting materials focused on detection and incident response in cybersecurity. It emphasizes understanding the incident response lifecycle and utilizing tools like Intrusion Detection Systems (IDS) and Security Information and Event Management (SIEM) platforms to detect, analyze, and respond to cybersecurity incidents effectively.

## Contents
1.1  **Exploring Suricata Alerts and Logs: A Hands-on Experience**
- In this lab activity, I gained hands-on experience with **Suricata**, an open-source intrusion detection, prevention, and network analysis tool. This lab focused on understanding alerts, logs, and the process of rule creation.

**Key Learnings:**

1. **Suricata Overview:**
   * Suricata monitors network interfaces and evaluates traffic against predefined rules.
   * Rules can define actions like **alerting**, **dropping**, **rejecting**, or **allowing** packets.
   * Configuration involves specifying **source and destination networks** to monitor.

2. **Rule Examination and Creation:**
   * Rules consist of components like **action, protocol, source/destination IP and port**, and **conditions** (e.g., payload content).
   * Example of a basic rule:
    `alert tcp any any -> any 80 (msg:"HTTP traffic detected"; sid:100001; rev:1;)` 
   * **Action: Alert.**
   * **Protocol: TCP.**
   * **Source/Destination: Any IP and port.**
   * **Message: "HTTP traffic detected."**
   * **SID (Signature ID): 100001.**
   * **Revision Number: 1.**

3. **Analyzing Alerts and Logs:**
   * **fast.log:**
      * Provides a concise summary of triggered alerts.
      * Useful for quick review of incident timelines.

   * **eve.json:**
      * A JSON-formatted log file containing detailed information about events.
      * Includes metadata like timestamp, source/destination IPs, ports, protocol, and payload details.

4. **Triggering Alerts:**
   * By generating specific types of traffic matching prewritten rules, I observed Suricata’s ability to identify and log alerts.

5. **Insights on IDS Rules:**
   * Effective rule writing ensures accurate identification of suspicious traffic while minimizing false positives.
   * Rules should balance detail and performance to avoid excessive system resource consumption.

**Practical Applications:**
Understanding Suricata’s alerting and logging processes is essential for:
   * Detecting suspicious network activity in real time.
   * Investigating potential breaches using detailed logs.
   * Fine-tuning IDS rules for optimal security and efficiency.

This lab emphasized the critical role of tools like Suricata in monitoring and defending networks against cyber threats.
  
2.1  **Introduction to Splunk and Search Processing Language (SPL)**
- In this activity, I explored **Splunk Cloud**, a SIEM platform, and its querying language, **Search Processing Language (SPL)**. I set up a Splunk account, uploaded sample data, and performed basic searches to analyze logs.

**Key tasks included:**
  * Filtering and sorting data using SPL syntax, wildcards (`*`), and pipe operators (`|`).
  * Executing time-based queries and statistical commands like `stats count by host` to group and summarize data.

**Key Insights:**
  * SIEM tools like Splunk streamline incident response and data analysis.
  * SPL enables quick identification of patterns, anomalies, and trends.

**Applications:**
  * SPL enhances efficiency in incident response by helping analysts pinpoint affected systems, trace anomalies, and generate actionable insights from large datasets.

3.1  **Chronicle SIEM Activity Summary**
- In this activity, I investigated a **phishing security incident** using **Chronicle**, a cloud-native SIEM tool. Chronicle's platform aggregates, analyzes, and reports on data from multiple sources to aid in incident response.

**Key steps included:**

  * Leveraging Chronicle’s features to collect and interpret logs and alerts.
  * Identifying indicators of compromise (IoCs) related to phishing.
  * Responding to questions about the incident based on data insights from Chronicle.

**Key Insights:**

  * SIEM tools like Chronicle centralize security data for efficient analysis.
  * Chronicle’s cloud-native approach simplifies investigation by automating data correlation and providing real-time threat insights.

**Applications:**
  * Chronicle is a vital tool for identifying and mitigating phishing attacks and other incidents, enhancing an organization’s ability to detect threats and respond swiftly.

1.4  **Xxxxx**
- xxxxxxxxxxxxx

1.5  **Xxxxx**
- xxxxxxxxxxxxx

1.6  **Xxxxx**
- xxxxxxxxxxxxx 

1.7  **Xxxxx**
- xxxxxxxxxxxxx

1.8  **Xxxxx**
- xxxxxxxxxxxxx

1.9  **Xxxxx**
- xxxxxxxxxxxxx

2.1  **Xxxxx**
- xxxxxxxxxxxxx

2.2  **Xxxxx**
- xxxxxxxxxxxxx

2.3  **Xxxxx**
- xxxxxxxxxxxxx

2.4  **Xxxxx**
- xxxxxxxxxxxxx

2.5  **Xxxxx**
- xxxxxxxxxxxxx

2.6 **Xxxxx**
- xxxxxxxxxxxxx

***Note:** For detailed instructions, see* [Instructions](Instructions.md).

## Proposed Resolution
- **Exercise 1:** []()
- **Exercise 2:** []()
- **Exercise 3:** []()
- **Exercise 4:** []()
- **Exercise 5:** []()
- **Exercise 6:** []()
- **Exercise 7:** []()
- **Exercise 8:** []()
- **Exercise 9:** []()
- **Exercise 10:** []()
- **Exercise 11:** []()
- **Exercise 12:** []()
- **Exercise 13:** []()
- **Exercise 14:** []()
- **Exercise 15:** []()

## Supporting Materials
- **Apply filters to SQL queries.pdf:** []()
- **Current file Permissions.pdf:** []()
- **File Permissions in Linux.pdf:** []()
- **Instructions for Including Linux Commands.pdf:** []()
- **Instructions for including SQL queries.pdf:** []()
- **Table formats.pdf:** []()
