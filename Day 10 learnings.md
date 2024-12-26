# Advent of Cyber 2024: Day 10 - He had a brain full of macros, and had shells in his soul.

**Summary of Task Completion**

### 1. Overview
Day 10 delved into the exploitation of malicious macros embedded in documents to achieve remote code execution (RCE). This task demonstrated how attackers utilize macros to execute payloads and establish reverse shells. The activity provided hands-on experience with creating and analyzing macro-enabled documents while focusing on mitigating risks associated with such attacks.

### 2. Tools Used:
#### Metasploit Framework:
Utilized to create a macro-embedded Word document containing a payload.
Configured to listen for and handle reverse shell connections.
#### Text Editor:
Analyzed the structure of the macro code embedded in the document.
#### Sandbox and Virtual Machine:
Used to execute and observe the behavior of the malicious document in a controlled environment.
#### Email Platform for Phishing Simulation:
Crafted and sent the malicious document to mimic phishing attacks.

### 3. General Topics and Concepts Covered:
#### Macros in Documents:
Understanding how macros can automate repetitive tasks but also be abused for malicious purposes.
Exploration of the VBA (Visual Basic for Applications) scripts often used in macro payloads.
#### Reverse Shells:
Learned how a malicious macro establishes a reverse shell connection to an attacker's machine.
Discussed how attackers can remotely control a compromised system through the reverse shell.
#### Phishing Techniques:
Explored how attackers use social engineering to trick users into opening macro-enabled documents.
Discussed domain typosquatting and email spoofing to increase attack success.
#### Payload Execution and Persistence:
Analyzed the execution flow of a payload triggered by a macro.
Discussed techniques attackers use to maintain access to compromised systems.

### 4. Skills and Lessons Learned:
#### Creating Malicious Macros:
Practiced embedding malicious macros in Word documents using Metasploit.
Understood how macros can be used to execute encoded payloads (e.g., Base64).
#### Analyzing Macro Behavior:
Gained insights into the structure and functions of VBA scripts within malicious macros.
Observed how AutoOpen triggers execute macros automatically when a document is opened.
#### Simulating and Mitigating Phishing Attacks:
Simulated phishing scenarios to understand how attackers craft convincing emails and payloads.
Explored methods for detecting and mitigating phishing attempts.
#### Securing Against Macro Exploits:
Discussed disabling macros by default and enabling only trusted documents.
Highlighted the importance of endpoint detection and response (EDR) solutions to monitor and block suspicious activity.

### 5. Achievement
Day 10 highlighted the critical vulnerabilities posed by macro-enabled documents in phishing attacks. By walking through the process of creating, executing, and analyzing malicious macros, I gained a deeper understanding of how attackers exploit this feature to gain unauthorized access. The task also underscored the importance of awareness training and robust security practices to mitigate these threats.
