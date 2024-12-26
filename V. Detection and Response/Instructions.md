# 1.1 Documenting Security Incidents in an Incident Handler's Journal

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

## Scenario 

Review the following scenario. Then complete the step-by-step instructions.

In your role as a cybersecurity analyst, you have been asked to research the differences and similarities between Wireshark and tcpdump and create a chart that outlines your findings. 

## Step-By-Step Instructions

Follow the instructions and answer the question to complete the activity.

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

## Scenario

You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a **hash function** is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint. 

Now that you have the file hash, you will use VirusTotal to uncover additional IoCs that are associated with the file.

## Step-By-Step Instructions

Follow the instructions to complete the activity.

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

