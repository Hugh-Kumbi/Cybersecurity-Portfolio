# Cybersecurity in Action: Detection and Response

This folder contains exercises, solutions, and supporting materials related to managing assets, threats, and vulnerabilities in cybersecurity. It emphasizes understanding the incident response lifecycle and developing practical skills to use tools for detecting and responding to cybersecurity incidents effectively.

## Contents

1.1  **Documenting Security Incidents in an Incident Handler's Journal**

- In this activity, I reviewed the details of a security incident and documented the findings using an incident handler's journal. This exercise emphasized the critical role of documentation in the incident response process.

- I practiced recording key information about the incident, including timelines, actions taken, and outcomes. Maintaining an accurate and detailed incident handler's journal is essential for analyzing and responding to security incidents effectively. It also serves as a valuable resource for learning and improving future incident response processes.

2.1  **Exploring Network Protocol Analyzers: Wireshark and Tcpdump**

- In this activity, I explored the functionalities of two powerful network protocol analyzers: **Wireshark and tcpdump**.

- I gained a foundational understanding of how these tools work and their key features. By using these packet sniffers, I learned how to capture and analyze network traffic, a critical skill for security analysts. These tools enable the examination of network traffic flows, aiding in identifying patterns and investigating potential security issues within a network.

1.3  **Analyzing Artifacts with VirusTotal and the Pyramid of Pain**

- In this activity, I analyzed an artifact using VirusTotal and documented its related Indicators of Compromise (IoCs) by referencing the Pyramid of Pain framework.

- VirusTotal provided me with the ability to scan a suspicious file or URL, gather threat intelligence, and identify any malicious activity associated with it. By leveraging this crowdsourced platform, I gained insights into the artifact's reported malicious properties and how the global cybersecurity community responds to such threats.

- I then categorized the IoCs using the Pyramid of Pain, which helped me evaluate how blocking these indicators affects adversaries. This exercise underscored the importance of understanding the difficulty level malicious actors face when IoCs are effectively mitigated.

- This activity reinforced the role of IoCs in detecting and responding to security incidents and demonstrated how collaborative tools like VirusTotal enhance threat analysis and detection capabilities.

4.1  **Responding to a Phishing Incident with a Playbook**

- In this activity, I responded to a phishing incident involving a malicious **SHA256 file hash** that was previously verified as malicious during an earlier investigation.

- Using a playbook, I followed a structured step-by-step process to investigate and resolve the incident's alert ticket. Playbooks are invaluable resources for guiding incident response efforts, as they ensure coordinated and effective actions are taken while minimizing the impact of the security incident.

**Key steps included:**

1. **Investigating the alert:** Reviewing the malicious file hash and gathering additional context from previously documented investigations.
2. **Verifying IoCs:** Cross-referencing the file hash against security intelligence tools like VirusTotal to confirm its malicious nature.
3. **Mitigating the threat:** Following predefined actions in the playbook to contain and remove the malicious file, such as isolating affected systems or blocking the hash across the organization.
4. **Documenting the response:** Recording every step and outcome in the incident tracking system for future reference and improvement of security processes.

This activity emphasized the importance of playbooks in ensuring a consistent and efficient response to phishing incidents and demonstrated how thorough documentation aids in enhancing organizational security.

5.1  **Security Incident Report: Data Breach via Forced Browsing Attack**
- In this activity, I reviewed an example of a **final report** related to an incident and answered quiz questions to reinforce my understanding of its components and significance.

**Key learning points included:**

1. **Purpose of the Final Report:**

  * The final report is a critical document created during the **Post-incident Activity phase** of the NIST Incident Response Lifecycle.
  * It provides a **comprehensive review of the incident**, including timelines, the root cause, actions taken, and outcomes.
  * The report also includes **recommendations** for future prevention and improving incident response capabilities.

2. **Components of a Final Report:**

  * **Executive Summary:** High-level overview of the incident for stakeholders.
  * **Incident Details:** Timeline, systems affected, root cause, and attack vectors.
  * **Actions Taken:** Steps for containment, eradication, recovery, and lessons learned.
  * **Recommendations:** Strategies for preventing similar incidents in the future, such as patch management, security training, or system updates.

3. **Post-Incident Activity:**

  * Emphasizes learning from the incident to strengthen security processes.
  * Involves stakeholder communication, process improvement, and sharing findings (if appropriate) with industry peers to strengthen collective security efforts.

This activity reinforced the importance of creating detailed and actionable final reports to ensure organizations learn and adapt from incidents, strengthening their overall security posture.

***Note:** For detailed instructions, see* [Instructions](Instructions.md).

## Proposed Resolution
- **Exercise 1:** [Documenting Security Incidents in an Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/1.1%20Incident%20Response-Incident%20Handler's%20Journal.pdf)
- **Exercise 2:** [Exploring Network Protocol Analyzers: Wireshark and Tcpdump](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/2.1%20Exploring%20Network%20Protocol%20Analyzers%3A%20Wireshark%20and%20Tcpdump.md)
- **Exercise 3:** [Analyzing Artifacts with VirusTotal and the Pyramid of Pain](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/3.1%20Analyzing%20Artifacts%20with%20VirusTotal%20and%20the%20Pyramid%20of%20Pain-Incident%20Handler's%20Journal.pdf)
- **Exercise 4:** [Responding to a Phishing Incident with a Playbook](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/4.1%20Responding%20to%20a%20Phishing%20Incident%20with%20a%20Playbook.pdf)
- **Exercise 5.1:** [Security Incident Report: Data Breach via Forced Browsing Attack](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/5.1%20Security%20Incident%20Report%3A%20Data%20Breach%20via%20Forced%20Browsing%20Attack.md)
- **Exercise 5.2:** [Initial Detection of Potential Security Incident-Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/5.2%20Initial%20Detection%20of%20Potential%20Security%20Incident-Incident%20Handler's%20Journal.pdf)
- **Exercise 5.3:** [Incident Escalation and Root Cause Analysis-Incident handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/5.3%20Incident%20Escalation%20and%20Root%20Cause%20Analysis-Incident%20handler's%20Journal.pdf)

## Supporting Materials
- **Incident Handler's Journal:** [Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Incident%20Handler's%20Journal.pdf)
- **Diagram Template:** [Diagram Template](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Diagram%20Template.pdf)
- **Pyramid of Pain:** [Pyramid of Pain](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Pyramid%20of%20Pain.pdf)
- **Alert Ticket:** [Alert Ticket](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Alert%20Ticket.pdf)
- **Phishing Playbook (with Flowchart):** [Phishing Playbook (with Flowchart)](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Phishing%20Incident%20Response%20Playbook.pdf)
- **Final Report:** [Final Report](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Final%20Report.pdf)
