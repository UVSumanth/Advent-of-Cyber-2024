# Advent of Cyber 2024: Day 11 - If you'd like to WPA, press the star key!

**Summary of Task Completion**

### 1. Overview
Day 11 focused on understanding Wi-Fi security and exploring vulnerabilities in WPA/WPA2 protocols through a practical demonstration of a Wi-Fi Protected Access (WPA) handshake capture and password-cracking attack. The task emphasized the risks associated with weak passwords and the importance of strong encryption for securing wireless networks.

### 2. Tools Used:
Wireless Network Adapter in Monitor Mode:
Configured the network adapter to capture Wi-Fi traffic, specifically targeting WPA handshakes.
Aircrack-ng Suite:
Used tools like airodump-ng to capture the WPA handshake and aircrack-ng to perform dictionary attacks on the captured handshake.
Aireplay-ng:
Sent deauthentication packets to force a client to reconnect, triggering the handshake process.
RockYou Wordlist:
Utilized as a dictionary for cracking the WPA password.
Virtual Machine (VM):
Served as a controlled environment for practicing and analyzing Wi-Fi attacks.

### 3. Concepts Covered:
#### Wi-Fi Security Overview:
Discussed the role of WPA/WPA2 in securing wireless communications.
Explored the significance of SSIDs, BSSIDs, and channels in Wi-Fi networks.
#### WPA Handshake:
Understood the four-step handshake process that authenticates a device to a wireless network.
Highlighted how this handshake can be captured for offline analysis.
#### Dictionary and Brute-Force Attacks:
Learned about leveraging pre-existing wordlists to guess passwords based on the captured handshake data.
#### Deauthentication Attacks:
Explored how deauth packets can force a client to disconnect, making it easier to capture a handshake.

### 4. Skills and Lessons Learned:
#### Configuring Monitor Mode:
Learned how to switch a network adapter to monitor mode for capturing wireless traffic.
#### Capturing and Cracking WPA Handshakes:
Practiced capturing handshakes and analyzing them to extract encrypted password data.
Successfully performed a dictionary attack to retrieve the pre-shared key (PSK).
#### Understanding Wi-Fi Channels and Signal Strength:
Gained insights into choosing the appropriate channels for effective network monitoring.
#### Recognizing Weak Password Risks:
Highlighted the vulnerability of networks with weak or predictable passwords to dictionary attacks.
#### Security Best Practices:
Emphasized using strong, complex passwords and avoiding default SSIDs to minimize attack surfaces.
Discussed the importance of regularly updating network security protocols.

### 5. Achievement
Day 11 reinforced the critical role of secure practices in protecting wireless networks. By engaging in practical activities, I developed a comprehensive understanding of Wi-Fi vulnerabilities and how attackers exploit them. This experience also highlighted the importance of proactive defense measures, such as enabling WPA3, enforcing strong password policies, and monitoring for suspicious activities.
