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

3.2  **Performing a Query With Chronicle-Incident Handler's Journal**

**Objective:**
This report details an investigation into phishing activity targeting company employees. The primary focus is on:
1. Identifying impacted assets**
2. Determining employee interactions with the malicious domain
3. Uncovering indicators of compromise (IoCs)

**Key Findings:**
  * **Impacted Assets:** Devices and accounts that interacted with or accessed the malicious domain were identified as potentially compromised.
  * **Employee Interaction:** Logs and SIEM data revealed instances of employee engagement with phishing emails or URLs, including clicks and file downloads.
  * **Indicators of Compromise:** IoCs such as malicious file hashes, URLs, and domains were documented for further analysis and mitigation.

**Next Steps:**
  * **Containment:** Block the identified malicious domain and quarantine affected assets.
  * **Eradication:** Remove malware or phishing artifacts from compromised systems.
  * **Employee Awareness:** Provide phishing awareness training and reinforce email security best practices.
  * **Continuous Monitoring:** Update detection rules to identify similar phishing patterns in the future.

This investigation emphasizes the importance of proactive monitoring and employee vigilance in mitigating phishing threats

***Note:** For detailed instructions, see* [Instructions](Instructions.md).

## Proposed Resolution
- **Exercise 1:** [Exploring Suricata Alerts and Logs: A Hands-on Experience](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/1.1%20Exploring%20Suricata%20Alerts%20and%20Logs%3A%20A%20Hands-on%20Experience.md)
- **Exercise 2:** [Introduction to Splunk and Search Processing Language (SPL)](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/2.1%20Introduction%20to%20Splunk%20and%20Search%20Processing%20Language%20(SPL).md)
- **Exercise 3:** [Splunk Query-Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/2.2%20Splunk%20Query-Incident%20Handler's%20Journal.pdf)
- **Exercise 4:** [Chronicle SIEM Activity Summary](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/3.1%20Chronicle%20SIEM%20Activity%20Summary.md)
- **Exercise 5:** [Performing a Query with Chronicle-Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/3.2%20Performing%20a%20Query%20with%20Chronicle-Incident%20Handler's%20Journal.pdf)

## Supporting Materials
- **Splunk Sign-Up:** [Splunk Sign-Up](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/Splunk%20Sign-Up.pdf)
- **Tutorialdata:** [Tutorialdata.](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VII.%20IDS%20%26%20SIEM/Tutorialdata.zip)
