Activity Overview

In this activity, you will create an incident report using the knowledge you’ve gained about networks throughout this course to analyze a network incident. You will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Creating a quality cybersecurity incident report and applying the CSF can demonstrate a proactive approach to security, improving communication and transparency with stakeholders, and improve security practices within your organization. You can also add the incident report you create to your cybersecurity portfolio when  you complete it.

The CSF is scalable and can be applied in a wide variety of contexts. As you continue to learn more and refine your understanding of key cybersecurity skills, you can use the templates provided in this activity in other situations. Knowing how to identify which security measures to apply in response to business needs will help you determine which are the best available options when it comes to network security.

Be sure to complete this activity before moving on. In the next course item, you will be able to self-assess your response. After that, there will be a completed exemplar to compare to your own work. It will also provide an opportunity for you to answer rubric questions that allow you to reflect on key elements of your professional statement.

Scenario

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

### Summary
Our organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved. During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.

### NIST CSF
| No | Description |
|---|---|
| 1 | `Identify` the following: <br> - Technology/Asset: Which system and devices were affected? <br> - Process/Business environment: Which business processes were affected in the attack? <br> - People: Who needs access to the affected systems? <br><br> Here is my respond: During the attack, the organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. | 
| 2 | `Protect` and implement safeguards: <br> - Access controls: Who needs to the affected items? How are non-trusted sources blocked from having access? <br> - Awareness/Training: Who needs to be made aware of this attack and how to prevent it from happening again? <br> - Data security: Is there any affected data that needs to be made more secure? - Information protection and procedures: Do any procedures need to be updated or added to protect data assets? <br> - Maintenance: Do any of the affected hardware, OS or software need to be updated? <br> Protective Technology:  Are there any protective technologies, like a firewall or an intrusion prevention system (IPS), that should be implemented to protect against future attacks? <br><br> Here is my respond: To protect the organization from future attacks the network security team implemented the following: <br> A new firewall rule to limit the rate of incoming ICMP packets. <br> Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. <br> Network monitoring software to detect abnormal traffic patterns. <br> An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.|
| 3 | `Detect` threats and attacks: <br> - Anomalies and events: What tools could be used to detect and alert IT security staff of anomalies and security events, such as a security information and event management system (SIEM) tool? <br> - Security continuous monitoring: What tools or IT processes are needed to monitor the network for security events? <br> - Detection process: What tools are needed to detect security events, such as an IDS? <br><br> Here is my respond: The cybersecurity team could configure source IP address verification on the firewall, analyze the spoofed IP address on WIRESHARK or TCPdump on incoming ICMP packets, and implemented network monitoring software (SIEM, such as Splunk, Chronicle) to detect abnormal traffic patterns. |
| 4 | `Respond` to threats and attacks: <br> - Planning: What action plans need to be implemented to respond to similar attacks in the future? <br> - Communications: How will security event response procedures be communicated within the organization and with those directly affected by the attack, including end users and IT staff? <br> - Analysis: What analysis steps should be followed in response to a similar attack? <br> Mitigation: What responding steps could be used to mitigate the impact of an attack, such as offlining or isolating affected resources? <br> Improvements: What improvements are needed to improve response procedures in the future? <br><br> Here is my respond: The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a DDoS attack. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.  |
| 5 | `Recover` affected systems or data: <br> - Recovery planning: How will resources be restored following an attack? <br> - Improvements: Do any improvements need to be made to the current recovery systems or processes? <br> - Communications: How will restoration procedures be communicated within the organization and with those directly affected by the attack, including end users and IT staff? <br><br> Here is my respond:   To begin with, we need to address the issue of ICMP flooding to ensure uninterrupted access to network services. The team may use a firewall to block ICMP flood attacks. In practice, the critical network services should be the top priority, while the non-critical networks could go offline. Finally, once the flood of ICMP packets has timed out, all non-critical network systems and services can go back online. |
