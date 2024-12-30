# 1.1 Documenting Security Incidents in an Incident Handler's Journal

> An incident handler’s journal provides a chronological record of events during a security incident, aiding in post-incident analysis and legal compliance.

> Detailed documentation helps identify patterns in repeated incidents, enabling better preparation and faster responses to future threats.

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 

A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.

## Step-By-Step Instructions

### Step 1: Access the Template
To use the template for this course item, click the link and select Use Template. 

Link to template: [Incident Handler's Journal](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Incident%20Handler's%20Journal.pdf)

### Step 2: Review the Scenario

Review the details of the scenario. Consider the following key details:

* A small U.S. health care clinic experienced a security incident on Tuesday at 9:00 a.m. which severely disrupted their business operations.

* The cause of the security incident was a phishing email that contained a malicious attachment. Once it was downloaded, ransomware was deployed encrypting the organization's computer files.

* An organized group of unethical hackers left a ransom note stating that the company's files were encrypted and demanded money in exchange for the decryption key

### Step 3: Record a Journal Entry 

Use the incident handler's journal to document your first journal entry about the given scenario. Ensure that you fill in all of the fields:

1. In the **Date** section, record the date of your journal entry. This should be the actual date that you record the entry, not a fictional date.

2. In the **Entry** section, provide a journal entry number. For example, if it is your first journal entry, enter 1.

3. In the **Description** section, provide a description about the entry.

4. In the **Tool(s) used** section, if any cybersecurity tools were used, list them here. 

5. In the **The 5 W's** section, record the details about the given scenario.

  a. Who caused the incident?

  b. What happened?

  c. When did the incident occur?

  d. Where did the incident happen?

  e. Why did the incident happen?

6. In the **Additional notes** row, record any thoughts or questions you have about the given scenario.

### What to Include in Your Response

Be sure to include the following elements in your completed activity: 

  * The journal entry date and number

  * A description of the journal entry

  * 1-2 sentences addressing each of the 5 W's of the scenario:

    * Who caused the incident?

    * What happened?

    * When did the incident occur?

    * Where did the incident happen?

    * Why did the incident happen?

* 1-2 sentences on any additional thoughts or questions about the scenario.

# 2.1 Exploring Network Protocol Analyzers: Wireshark and Tcpdump

> Wireshark provides a user-friendly graphical interface to analyze network packets, making it easier to identify anomalies and troubleshoot issues.

> Tcpdump, a command-line tool, excels at capturing live traffic for quick analysis, especially on systems without graphical capabilities.

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 

Review the following scenario. Then complete the step-by-step instructions.

In your role as a cybersecurity analyst, you have been asked to research the differences and similarities between Wireshark and tcpdump and create a chart that outlines your findings. 

## Step-By-Step Instructions

### Step 1: Access the Template
To use the template for this course item, click the link and select Use Template. 

Link to template: [Diagram Template](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Diagram%20Template.pdf)

### Step 2: Conduct Online Research

To begin, conduct online research to learn more about tcpdump and Wireshark. You can begin by using the official Wireshark documentation and tcpdump documentation: 

  * [Tcpdump - Resources and documentation](https://www.tcpdump.org/index.html#documentation)
  * [Wireshark - Official user guide](https://www.wireshark.org/docs/wsug_html/)

You can also perform an internet search to find resources that explain how these tools work. Try searching for information using these terms: 

  * Wireshark features and functionalities
  * Tcpdump features and functionalities
  * Comparison between tcpdump and Wireshark

Be sure to critically evaluate the search results and select reliable and authoritative sources such as official documentation, reputable cybersecurity websites, or technical forums that provide accurate and factual information about the tools.

Explore these resources to gather information on tcpdump and Wireshark and focus on understanding the different features and functionalities that each tool has.

**Consider these questions to help you compare the two tools:** 

  * What software or equipment is required to access and use the tool? Is the tool open-source or proprietary? 
  * What type of user interface or layout does the tool use?
  * How do security analysts typically use the tool? What are the recommended usage scenarios for each tool?
  * How does the tool handle capturing, analyzing, and filtering network traffic?
  * Are there any limitations or considerations for using this tool?

### Step 3: Fill in the Diagram

After you've completed your research on Wireshark and tcpdump, fill out the template and include at least two features for each tool. These could be related to the tool's capabilities, the type of analysis they perform, contrasting features, user interfaces, usage scenarios, and any other notable distinctions. Then, include three similarities between tcpdump and Wireshark. 

### What to Include in Your Response

**Be sure to address the following elements in your completed activity:** 

  * At least 2 differences between Wireshark and tcpdump

  * At least 3 similarities between Wireshark and tcpdump 

# 3.1 Analyzing Artifacts with VirusTotal and the Pyramid of Pain

> VirusTotal aggregates results from multiple antivirus engines to quickly analyze files, URLs, or IPs for known threats.

> The Pyramid of Pain highlights the increasing difficulty for attackers as defenders improve detection, from simple hash blocking to identifying attacker techniques.

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 1

You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a **hash function** is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint. 

Now that you have the file hash, you will use VirusTotal to uncover additional IoCs that are associated with the file.

## Step-By-Step Instructions

### Step 1: Access the Template

To use the template for this course item, click the link below and select Use Template.

Link to template: [Pyramid of Pain](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Pyramid%20of%20Pain.pdf)

### Step 2: Review the Details of the Alert

The following information contains details about the alert that will help you complete this activity. The details include a file hash and a timeline of the event. Keep these details for reference as you proceed to the next steps.

**SHA256 file hash:** `54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b`

**Here is a timeline of the events leading up to this alert:**

* **1:11 p.m.:** An employee receives an email containing a file attachment.

* **1:13 p.m.:** The employee successfully downloads and opens the file.

* **1:15 p.m.:** Multiple unauthorized executable files are created on the employee's computer.

* **1:20 p.m.:** An intrusion detection system detects the executable files and sends out an alert to the SOC.

### Step 3: Enter the File Hash into Virus Total

Go to the [VirusTotal website](https://www.virustotal.com/gui/file/54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b). Click **SEARCH**, enter the SHA256 file hash in the search box, and press enter. The SHA256 file hash is listed in Step 2 of this activity.

***Note:** For the purpose of this activity, you'll focus on evaluating VirusTotal results. However, no single tool can detect all types of malicious activity. Security analysts will often use a combination of other tools to carefully evaluate the results of a scan before making a decision about the file.*

### Step 4: Analyze the VirusTotal Report

Once you've retrieved VirusTotal's report on the file hash, take some time to examine the report details. You can start by exploring the following tabs:

1. **Detection:** This tab provides a list of third-party security vendors and their detection verdicts on an artifact. Detection verdicts include: malicious, suspicious, unsafe, and others. Notice how many security vendors have reported this hash as malicious and how many have not.

2. **Details:** This tab provides additional information extracted from a static analysis of the IoC. Notice the additional hashes associated with this malware like MD5, SHA-1, and more. 

3. **Relations:** This tab contains information about the network connections this malware has made with URLs, domain names, and IP addresses. The **Detections** column indicates how many vendors have flagged the URL or IP address as malicious.

4. **Behavior:** This tab contains information related to the observed activity and behaviors of an artifact after executing it in a controlled environment, such as a sandboxed environment. A sandboxed environment is an isolated environment that allows a file to be executed and observed by analysts and researchers. Information about the malware's behavioral patterns is provided through sandbox reports. Sandbox reports include information about the specific actions the file takes when it's executed in a sandboxed environment, such as registry and file system actions, processes, and more. Notice the different types of tactics and techniques used by this malware and the files it created.

***Pro tip:** Sandbox reports are useful in understanding the behavior of a file, but they might contain information that is not relevant to the analysis of the file. By default, VirusTotal shows all sandbox reports in the Behavior tab. You can select individual sandbox reports to view. This is helpful because you can view the similarities and differences between reports so that it's easier to identify which behaviors are likely to be associated with the file.* 

### Step 5: Determine Whether the File is Malicious

Review the VirusTotal report to determine whether the file is malicious. The following sections will be helpful to review before making this determination:

The **Vendors' ratio** is the metric widget displayed at the top of the report. This number represents how many security vendors have flagged the file as malicious over all. A file with a high number of vendor flags is more likely to be malicious.

The **Community Score** is based on the collective inputs of the VirusTotal community. The community score is located below the vendor's ratio and can be displayed by hovering your cursor over the red **X**. A file with a negative community score is more likely to be malicious.

Under the **Detection** tab, the **Security vendors' analysis** section provides a list of detections for this file made by security vendors, like antivirus tools. Vendors *who have not* identified the file as malicious are marked with a checkmark. Vendors who *have* flagged the file as malicious are marked with an exclamation mark. Files that are flagged as malicious might also include the name of the malware that was detected and other additional details about the file. This section provides insights into a file's potential maliciousness.

Review these three sections to determine if there is a consistent assessment of the file's potential maliciousness such as: a high vendors' ratio, a negative community score, and malware detections in the security vendors' analysis section. 

In the first slide of your **Pyramid of Pain template**, indicate whether this file is malicious. Then, explain your reasoning based on your findings.

***Note:** The Vendors' ratio is based on security vendors' detections and vendors might not always detect malicious files. The Community Score is based on the opinions and insights from the VirusTotal community. If a file's scores are low, it doesn't necessarily mean that the file is safe. It is recommended to use multiple sources of information when evaluating files.*

### Step 6: Fill in the Template with Additional Indicators of Compromise

After you've explored the sections in the VirusTotal report, you will uncover additional IoCs that are associated with the file according to the VirusTotal report.

Identify *three* **indicators of compromise (IoCs)** that are associated with this file hash using the tabs in the VirusTotal report. Then, enter the IoCs into their respective sections in the Pyramid of Pain template.

Indicators of compromise are valuable sources of information for security professionals because they are used to identify malicious activity. You can choose to identify any three of the six types of IoCs found in the Pyramid of Pain: 

**Hash value:** Hashes convert information into a unique value that can't be decrypted. Hashes are often used as unique references to files involved in an intrusion. In this activity, you used a SHA256 hash as the artifact for this investigation. Find another hash that's used to identify this malware and enter it beside the **Hash values** section in the Pyramid of Pain template. You can use the **Details** tab to help you identify other hashes.

**IP address:** Find an IP address that this malware contacted and enter it beside the **IP addresses** section in the Pyramid of Pain template. You can locate IP addresses in the **Relations** tab under the Contacted IP addresses section or in the **Behavior** tab under the IP Traffic section.

**Domain name:** Find a domain name that this malware contacted and enter it beside the **Domain names** section in the Pyramid of Pain template. You can find domain name information under the Relations tab. You might encounter benign domain names. Use the **Detections** column to identify domain names that have been reported as malicious.

**Network artifact/host artifact:** Malware can create network-related or host-related artifacts on an infected system. Find a network-related or host-related artifact that this malware created and enter it beside the **Network/host artifacts** section in the Pyramid of Pain template. You can find this information from the sandbox reports under the **Behavior** tab or from the Relations tab.

**Tools:** Attackers can use tools to achieve their goal. Try to find out if this malware has used any tool. Then, enter it beside the **Tools** section in the Pyramid of Pain template.

**Tactics, techniques, and procedures (TTPs):** TTPs describe the behavior of an attacker. Using the sandbox reports from the Behavior tab, find the list of tactics and techniques used by this malware as identified by MITRE ATT&CK® and enter it beside the **TTPs** section in the Pyramid of Pain template. 

***Note:** VirusTotal reports can contain legitimate domains and IP addresses that are not considered malicious.* 

***Pro tip:** To learn more about a section in VirusTotal, hover your cursor over the information icon to display information on what that section includes.*

### What to Include in Your Response

**Be sure to include the following points in the template of your completed activity:** 

  * A statement explaining whether the file hash is malicious  

  * Three different types of indicators of compromise

# 4.1 Responding to a Phishing Incident with a Playbook

> Incident response playbooks for phishing often include steps to isolate affected systems, block malicious URLs, and educate users on recognizing phishing attempts.

> Automated email analysis tools can speed up playbook execution by identifying phishing emails and quarantining them before they reach users.

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario 2: Follow-Up Analysis and Actions 

You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.

## Step-By-Step Instructions

### Step 1: Access the Template

To use the template for this course item, click the link and select Use Template.

Link to template: [Alert Ticket](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Alert%20Ticket.pdf)

### Step 2: Access Supporting Materials
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

Link to supporting materials: [Phishing Playbook (with Flowchart)](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Phishing%20Incident%20Response%20Playbook.pdf)

## Step 3: Review the Playbook and Flowchart

Before you begin investigating the alert, take a moment to review the playbook and flowchart because you'll be using them throughout the investigation.

The **Phishing Playbook** instructions provide detailed, written instructions about each step represented in the flowchart.

The **Phishing Flowchart** provides a high-level overview and visual representation of the sequence of steps and substeps you'll take to respond to a phishing alert.

***Note:** The steps in this playbook are not a definitive guide to responding to a phishing incident. Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.*

### Step 4: Updating the Alert Ticket Status

In the **Alert ticket** template, begin the investigation by updating the **Ticket status** dropdown list to **Investigating.**

### Step 5: Evaluating the Alert

For this exercise, begin with the second step in the playbook, **Evaluate the alert,** because you've already received and accessed the phishing alert ticket. 

As a security analyst, you'll want to gain a complete understanding of why the alert was triggered. Create a new entry in your incident handler's journal to record the details of this security incident and gather your thoughts. You'll refer to these notes as you progress through the steps in the playbook. 

Then, evaluate the contents of the **Alert ticket,** including the content in the **Additional information** section. Here are some examples of elements to examine when you are evaluating the alert ticket details:

* **Alert severity:** According to the playbook instructions, an alert severity of Medium or High is a good indication that a ticket might require escalation.

* **Sender details:** Analyzing the sender details of an email is important because it can reveal inconsistencies that can indicate a phishing attempt. Often, phishing emails try to impersonate trusted entities. For example, if there is a mismatch between the sender's email address and the sender's name, this is a good indication that the email might be a phishing email.

* **Message body:** It's important to analyze the message body (and subject line) of an email because phishing emails often contain grammatical errors, which can be an indication of a phishing attempt.

* **Attachments or links:** Phishing emails contain malicious links or attachments that are used to steal sensitive information or download malicious software or code on the recipient's device. Check to see whether a file has been attached to this email.

After you've evaluated the contents of the alert ticket, answer the 5 W's of this incident to gather the information you need to understand the nature of the alert. The 5 W's are:

  * Who caused the incident?

  * What happened?

  * When did the incident take place?

  * Where did the incident occur?

  * Why did it happen?

At the end of this step, you should have 2-3 reasons on why you believe the phishing alert is or isn't legitimate. 

### Step 6: Determine Whether the Alert Should be Escalated

After evaluating the alert details, use the Phishing Playbook's **Step 3.0** and **Step 3.1** to determine whether the email contains links or attachments and whether these links or attachments are malicious. Remember you've already determined that the email contains an attachment that has been verified as malicious through its file hash. 

Proceed to the Phishing Playbook's **Step 3.2** if you've determined that the alert should be escalated. If you've determined that the alert should not be escalated, proceed to the Phishing Playbook's **Step 4.**

### Step 7: Updating the Alert Ticket Status

Now that you've examined the email details, complete the final step of the playbook and update the alert ticket in the activity template. Depending on whether you want to escalate or close the alert:

  * Under the **Ticket status** column of the alert ticket template, update the status of the ticket to either **Closed** or **Escalated**.

  * Under the **Ticket comments** column of the alert ticket template, use the details you've found to explain the steps taken and why you chose to escalate or close the ticket. Include 2-3 reasons as to why you believe this alert should be escalated or closed.

### What to Include in Your Response

**Be sure to address the following steps in your completed activity:**  

  * In the **Alert ticket**, update the **Ticket status** column using the dropdown list.

  * In the **Ticket comments** section in the **Alert ticket**, provide a sentence briefly describing the alert and what happened.

  * In the **Ticket comments** section in the **Alert ticket**, provide 2-3 sentences describing the reasons why you chose to escalate or close the ticket. Support your reasons using specific details from the alert ticket.

# 5.1 Reviewing a Final Report and Analyzing Post-Incident Activities

> A final report after an incident often includes lessons learned, helping organizations refine their defenses and response plans.

> Post-incident analysis typically identifies gaps in existing controls, driving improvements in policies, tools, and team training.

> Please visit this [link](https://www.coursera.org/learn/detection-and-response) for further information.

## Scenario

You recently joined the security team as a level-one security operation center (SOC) analyst at a mid-sized retail company. Along with its physical store locations, your company also conducts operations in e-commerce, which account for 80% of its sales.

You are spending your first week of training becoming familiar with the company's security processes and procedures. Recently, the company experienced a major security incident involving a data breach of over one million users. Because this was a recent and major security incident, your team is working to prevent incidents like this from happening again. This breach happened before you began working at the company. You have been asked to review the final report.

**To gain an understanding of the incident's life cycle, your goals for your review are as follows:**

  * Goal 1: Identify exactly what happened.

  * Goal 2: Identify when it happened. 

  * Goal 3: Identify the response actions that the company took.

  * Goal 4: Identify future recommendations.

## Step-By-Step Instructions

### Step 1: Access Supporting Materials

The following supporting materials will help you complete this activity. Keep them open as you proceed to the questions.

To use the supporting materials for this course item, click the link and select “Use Template.” 

Link to supporting materials: [Final report](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/V.%20Detection%20and%20Response/Final%20Report.pdf)

### Step 2: Answer Questions About the Final Report

1. What type of security incident was the organization affected by?

2. Which section of the report includes an explanation of the root cause of the incident?

3. What did the attacker use to exploit the e-commerce web application vulnerability?

4. What recommendations did the organization implement to prevent future recurrences? Select two answers.
