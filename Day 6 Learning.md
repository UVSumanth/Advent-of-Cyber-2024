# Advent of Cyber 2024: Day 6 - If I can't find a nice malware to use, I'm not going.

**Summary of Task Completion**

### 1. Overview
Day 6 focused on understanding the fundamentals of malware analysis, particularly how malicious programs operate, their characteristics, and the techniques used to identify and analyze them. This task emphasized recognizing malware behavior to enhance detection and response capabilities.

### 2. Tools Used:
#### Static Analysis Tools:
Utilities like strings for extracting readable content from binaries.
File property analyzers to gather metadata about malicious files.
#### Dynamic Analysis Tools:
Sandboxing environments (e.g., Cuckoo Sandbox) to execute malware safely and observe its behavior.
Process monitoring tools to track system changes in real-time.
#### Hex Editors: 
To inspect binary content and identify patterns or embedded resources.
#### Online Services: 
Platforms like VirusTotal to identify known malware signatures.

### 3. Concepts Covered:
#### Malware Types:
Differentiating between types of malware, such as trojans, ransomware, and worms.
Understanding their purpose and the damage they can inflict.
#### Indicators of Compromise (IoCs):
Identifying clues like suspicious IP addresses, unusual file extensions, and encoded payloads.
Extracting hashes to compare files against known malware databases.
#### Behavioral Analysis:
Observing changes to files, registry entries, and network activity during malware execution.
Capturing and analyzing traffic to detect command-and-control (C2) communication.
#### Anti-Analysis Techniques:
Recognizing methods malware uses to evade detection, such as obfuscation or virtual machine checks.

### 4. Skills and Lessons Learned:
#### File Inspection:
Extracting key details from executable files, such as headers, strings, and embedded resources.
Using hashes and metadata to classify malware.
#### System Monitoring:
Tracking process creation, file system changes, and network connections.
Understanding how malware persists on a system or spreads across a network.
#### Behavioral Understanding:
Identifying malicious actions, such as encryption routines in ransomware or data exfiltration.
Recognizing patterns in malware behavior to develop detection rules.
#### Mitigation and Response:
Learning how early detection of IoCs can prevent further compromise.
The importance of isolating infected systems and analyzing malware in controlled environments.

### 5. Achievement
Day 6 provided valuable insights into the lifecycle of malware and how to analyze it effectively. By leveraging both static and dynamic analysis techniques, I was able to identify suspicious characteristics, observe malware behavior, and understand how to mitigate its impact. The task reinforced the importance of continuous vigilance and the role of proactive detection in preventing cyber threats.
