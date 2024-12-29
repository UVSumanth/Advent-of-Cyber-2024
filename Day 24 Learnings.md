# Advent of Cyber 2024: Day 24 - You can’t hurt SOC-mas, Mayor Malware!

**Summary of Task Completion**

### 1. Overview
Day 24 delved into analyzing communication between IoT devices using the MQTT protocol. The goal was to reverse-engineer malicious commands sent to smart devices, understand their communication patterns, and take corrective action to restore functionality. This task emphasized securing IoT environments and understanding the risks posed by misconfigured or compromised smart devices.

### 2. Tools Used:
Wireshark:
A powerful network protocol analyzer used to capture and dissect MQTT traffic.

mosquitto_pub Command-Line Utility:
Used to publish MQTT messages to a broker, simulating client communication.

challenge.pcapng File:
A pre-captured packet file containing MQTT messages for analysis.

### 3. General Topics and Concepts Covered:
#### IoT and MQTT Protocol:
Explored how IoT devices communicate using the MQTT (Message Queuing Telemetry Transport) protocol, a lightweight publish/subscribe messaging framework.
Understood the roles of MQTT components: brokers, clients, and topics.
Analyzed the vulnerabilities of IoT systems when not properly secured.
#### Network Traffic Analysis with Wireshark:
Used Wireshark to capture and analyze MQTT traffic.
Filtered for MQTT-specific data to examine message topics, payloads, and communication patterns.
Identified malicious commands and deciphered their impact on smart devices.
#### Reverse Engineering and Corrective Actions:
Learned to reverse-engineer commands sent to smart devices to understand their effects.
Applied knowledge of MQTT to construct and send corrective commands to restore normal functionality.
Highlighted the importance of secure configurations and authentication for IoT systems.

### 4. Skills and Lessons Learned:
#### Understanding MQTT Protocol:
Gained hands-on experience working with MQTT topics, brokers, and clients.
Learned how publish/subscribe models operate in real-world IoT environments.
#### Network Traffic Analysis:
Enhanced skills in using Wireshark to investigate specific protocols and troubleshoot communication issues.
#### Command Construction and Execution:
Learned to craft MQTT messages to interact with smart devices securely and effectively.
#### Securing IoT Systems:
Reinforced the importance of secure authentication, encrypted communication, and isolating IoT devices to mitigate risks.
#### Reverse Engineering in Action:
Practiced identifying and countering malicious actions by understanding how the attacker’s commands impacted the system.

### 5. Achievement
Day 24 was a fascinating exploration into the world of IoT and MQTT. It was both challenging and rewarding to analyze the captured traffic, reverse-engineer the malicious commands, and successfully restore the sabotaged devices. This task served as a reminder of the growing importance of securing IoT systems as they become integral to modern infrastructure. It highlighted how vulnerabilities in IoT can be exploited and underscored the need for proactive measures to safeguard these devices. This experience has deepened my understanding of IoT security and the practical application of network analysis tools.
