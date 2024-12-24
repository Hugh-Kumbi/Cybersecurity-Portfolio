# 1.1 Intrusion Detection Systems (IDS) - Suricata

> Please visit this [link](https://www.coursera.org/learn/assets-threats-and-vulnerabilities?specialization=google-cybersecurity) for further information.

## Scenario

Review the following scenario. Then, complete the step-by-step instructions.

One of the most valuable assets in the world today is information. Most information is accessed over a network. There tend to be a variety of devices connected to a network and each is a potential entry point to other assets.

An inventory of network devices can be a useful asset management tool. An inventory can highlight sensitive assets that require extra protection.

![Network devices](https://github.com/user-attachments/assets/8359b017-a3c6-4304-99a6-67b440457182)

You’re operating a small business from your home and must create an inventory of your network devices. This will help you determine which ones contain sensitive information that require extra protection.

To do this, you will start by identifying three devices that have access to your home network. This might include devices such as:

* Desktop or laptop computers

* Smartphones

* Smart home devices

* Game consoles

* Storage devices or servers

* Video streaming devices

Then, you’ll list important characteristics of each device such as its owner, location, and type. Finally, you will assign each device a level of sensitivity based on how important it is to protect.

## Step-By-Step Instructions

### Step 1. Access the Template

To use the template for this course item, click the link below and select Use Template. 

Link to template: [Home asset inventory](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/IV.%20Assests%20Threats%20and%20Vulnerabilities/Home%20Asset%20Inventory.xlsx)

### Step 2: Identify Assets

In the asset inventory spreadsheet, find the **Asset** column header. Consider the devices that may be connected to the home network. Examine devices in the scenario graphic to help you brainstorm.

Choose three devices that are not already listed in the spreadsheet and add them to the empty rows in the **Asset** column.

***Note:** A few devices, like a network router, desktop, and a guest smartphone have already been added for your reference.*

### Step 3: Fill in the Characteristics of Each Asset

List important characteristics, including **Network access**, **Owner**, and **Location** for each asset that you’ve identified.

Here’s an explanation of each characteristic: 

* **Network access** describes how often the device is connected to the network.

* **Owner** describes the person responsible for the device.

* **Location** describes where the device is located in relation to the router.

### Step 4: Evaluate the Access of Network Devices 

Review the information that you’ve listed in the **Network access**, **Owner**, and **Location** columns.

In the **Notes** column, record 1 or 2 details or characteristics of each device. Do this by asking yourself questions about each:

* *What kind of information is stored on the device?*

* *How does it connect to the network?*

* *Is the owner careful about securing it?*

For example, the desktop computer contains sensitive information, like photos, that only the owner should have access to. In contrast, the network router uses one frequency for smart home devices and another for all other devices.

***Note:** Keep in mind that there might be some variation within each category. Try to identify details that could impact the confidentiality, integrity, or availability of information that’s connected to the network.*

## Step 5: Classify the Sensitivity of Network Devices

It’s time to classify assets based on the information you’ve collected. Do this by thinking about how an asset could impact your business if its security was compromised:

* *What types of information would be disclosed or stolen?*

* *Could an attacker alter information on the device?*

* *What would happen to the business if this information were destroyed?*

For example, the network router is classified as confidential because the owner has granted limited access to the device to specific users.

Find the **Sensitivity** column in the asset inventory. Type one of the four levels of sensitivity you previously learned about.

***Note:** You can use the Categories table as a guide for choosing an appropriate classification.*

### What to Include in Your Response 

* Develop and implement custom rules in Suricata.
* Analyze network traffic using packet capture (PCAP) files.
* Review and interpret output logs, including `fast.log` and `eve.json`.

# Conducting a Risk Assessment for Business Operations   

> Please visit this [link](https://www.coursera.org/learn/assets-threats-and-vulnerabilities?specialization=google-cybersecurity) for further information.

## Scenario 

You've joined a new cybersecurity team at a commercial bank. The team is conducting a risk assessment of the bank's current operational environment. As part of the assessment, they are creating a risk register to help them focus on securing the most vulnerable risks.

A **risk register** is a central record of potential risks to an organization's assets, information systems, and data. Security teams commonly use risk registers when conducting a risk assessment.

Your supervisor asks you to evaluate a set of risks that the cybersecurity team has recorded in the risk register. For each risk, you will first determine how likely that risk is to occur. Then, you will determine how severely that risk may impact the bank. Finally, you will calculate a score for the severity of that risk. You will then compare scores across all risks so your team can determine how to prioritize their attention for each risk.

## Step-By-Step Instructions

### Step 1. Access the template
To use the template for this course item, click the following link and select Use Template. 

Link to template: [Risk register](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/IV.%20Assests%20Threats%20and%20Vulnerabilities/Risk%20Register.pdf)

### Step 2. Understand the Operating Environment

When conducting a risk assessment, it's important to consider the factors that could cause a security event. This often starts with understanding the operating environment.

In this scenario, your team has identified characteristics of the operating environment that could factor into the bank's risk profile:

*The bank is located in a coastal area with low crime rates. Many people and systems handle the bank's data—100 on-premise employees and 20 remote employees. The customer base of the bank includes 2,000 individual accounts and 200 commercial accounts. The bank's services are marketed by a professional sports team and ten local businesses in the community. There are strict financial regulations that require the bank to secure their data and funds, like having enough cash available each day to meet Federal Reserve requirements.*

### Step 3.  Consider Potential Risks to Assets

Security events are possible when assets are at risk. The source of a risk can range from malicious attackers to accidental human errors. A risk source can even come from natural or environmental hazards, such as a structural failure or power outage.

The bank's funds are one of its key assets. Your team has listed five primary risks to the bank's funds:

* Business email compromise

* Compromised user database

* Financial records leak

* Theft

* Supply chain attack

Consider these potential risks in relation to the bank's operating environment. Then, write **2-3 sentences (40-60 words)** in the **Notes** area of the template describing how security events are possible considering the risks facing the funds in this operating environment.

### Step 4. Score Risks Based on their Likelihood

As you might recall, risk can be calculated with this simple formula:

**Likelihood x Impact = Risk**

In order to calculate the score for a security risk, you must first estimate and score the likelihood of the risk causing a security event. The likelihood of a risk can be based on available evidence, prior experience, or expert judgment. A common way to estimate the likelihood of the risk is to determine the potential frequency of the risk occurring:

* *Could the risk happen once a day?*

* *Could the risk happen once a month?*

* *Could the risk happen once in a year?*

For example, the bank must have enough funds available each day to meet its legal requirements. A potential risk that could prevent the bank from replenishing its funds is a supply chain disruption. Being located in a coastal area, there's a likelihood that the bank may experience supply chain disruptions caused by hurricanes. However, a hurricane might only impact the bank every few years, so you can score the likelihood as low.

In this instance, the team is scoring the likelihood of an event on a scale of 1-3:

* **1** represents an event with a *low* chance of occuring.

* **2** represents an event with a *moderate* chance of occuring.

* **3** represents a *high* chance of occuring.

Review the **Risk(s)**, **Description**, and **Notes** of the risk register template. Refer to the risk matrix and use it to estimate a likelihood score for each risk. Then, enter a **score (1-3)** for each risk in the **Likelihood** column of the register.

### Step 5.  Score Risks Based on their Severity

A severity score is an estimate of the overall impact that might occur as a result of an event. For example, damage can occur to a company's reputation or finances and there may be a loss of data, customers, or assets. Evaluating the severity of a risk helps businesses determine the level of risk they can tolerate and how assets might be affected. 

When evaluating the severity of a risk, consider the potential consequences of that risk occurring:

* *How would the business be affected?*

* *What's the financial harm to the business and its customers?*

* *Can important operations or services be impacted?*

* *Are there regulations that can be violated?*

* *What is the reputational damage to the company's standing?*

Use the top row of the risk matrix and consider the potential impact of each risk. Estimate a severity score for each risk. Then, enter a **score (1-3)** for each risk in the **Severity** column of the register:

* **1** *(low severity)*

* **2** *(moderate severity)*

* **3** *(high severity)*

For example, a leak of financial records might lead to a loss of profits, a loss of customers, and heavy regulatory fines. A risk such as this might receive a severity score of 3 because it greatly impacts the bank's ability to operate.

### Step 6.  Calculate on Overall Risk Score

Ultimately, the goal of performing a risk assessment is to help security teams prioritize their efforts and resources.

Using the risk formula, multiply the likelihood and severity score for each risk. Then, enter a priority **score (1-9)** for each of the risks in the **Priority** column of the register.

### What to Include in Your Response 

Be sure to address the following criteria in your completed activity: 

* 2-3 sentences describing the risk factors

* 5 likelihood scores

* 5 severity scores

* 5 overall risk scores
