# Advent of Cyber 2024: Day 23 - You wanna know what happens to your hashes?

### 1. Overview
Day 23 highlighted the importance of understanding password hashing and the challenges associated with cracking password hashes. The task focused on analyzing password security practices, identifying hashed passwords, and using practical tools to recover plaintext passwords when possible. It emphasized the need for strong password policies and secure storage methods.

### 2. Tools Used:
#### John the Ripper:
A powerful password-cracking tool used to analyze hashes and recover plaintext passwords using various methods like wordlists and rules.
#### Hash Identifier (hash-id):
A tool to identify the type of hash being analyzed, which helps in selecting the appropriate cracking method.
#### pdf2john:
A utility for extracting hash data from password-protected PDF files for further analysis with John the Ripper.
#### Rockyou.txt Wordlist:
A widely used wordlist derived from real-world data breaches, providing common passwords to test during cracking attempts.

### 3. General Topics and Concepts Covered:
#### Hash Functions and Password Security:
Understanding the purpose and structure of hash functions like SHA-256.
Exploring why hashed passwords are stored instead of plaintext to improve security.
Learning about the importance of salting passwords to defend against precomputed attacks (e.g., rainbow tables).
#### Password Cracking Basics:
Techniques for recovering plaintext passwords using wordlists and brute force.
Understanding how rules and transformations enhance password cracking capabilities by simulating common user behaviors like substitutions or appending numbers.
#### Analyzing and Breaking Protected Files:
Exploring password-protected files and methods to extract hashes for analysis.
Investigating common mistakes users make when setting weak or predictable passwords.

### 4. Skills and Lessons Learned:
#### Hash Identification and Analysis:
Gained hands-on experience identifying hash types and understanding their properties.
#### Password Cracking Techniques:
Learned to use wordlists effectively and apply rules to enhance password recovery rates.
#### Creating Custom Wordlists:
Explored the importance of tailored wordlists, including user-specific patterns and likely password variations.
#### File Security Practices:
Understood the vulnerabilities of password-protected files when weak or reused passwords are used.
#### Importance of Salting:
Reinforced the critical role of salting in thwarting attacks on hashed passwords.

### 5. Achievement
Day 23 provided valuable insights into how hashed passwords work and the common pitfalls in securing sensitive information. It was fascinating to see how tools like John the Ripper work to uncover weak security practices. The task underscored the importance of strong password policies, proper salting, and user education. It also reinforced ethical practices in analyzing security and respecting boundaries while investigating breaches or protected files. This task was both a technical challenge and a reminder of the responsibility that comes with understanding these concepts.
