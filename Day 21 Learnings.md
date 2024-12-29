# Advent of Cyber 2024: Day 21 - HELP ME...I'm REVERSE ENGINEERING!

**Summary of Task Completion**

### 1. Overview
Day 21 introduced the fundamentals of reverse engineering and provided practical experience in analyzing binaries to uncover their functionality. The task emphasized the importance of understanding how applications behave and how to extract critical insights from compiled code.

### 2. Tools Used:
#### ILSpy:
A decompiler used to convert binaries into high-level code for easier analysis.
#### PEStudio:
A tool to gather static information about binaries, such as hashes, architecture, and embedded indicators.
#### Sandbox Environment:
Safely executed suspicious binaries in a controlled setup to observe their behavior.

### 3. General Topics and Concepts Covered:
#### Reverse Engineering Basics:
Understanding the purpose of reverse engineering in cybersecurity, such as analyzing malware or uncovering hidden functionality in applications.
Exploring the structure of binary files, including code sections, data sections, and import/export tables.
#### Disassembly vs. Decompiling:
Learning the difference between disassembly (viewing low-level machine instructions) and decompiling (converting binaries into high-level readable code).
Understanding the pros and cons of each approach and when to use them.
#### Multi-Stage Binaries:
Exploring how attackers use multi-stage binaries to evade detection and execute malicious payloads.
Gaining insights into dropper and payload behavior.

### 4. Skills and Lessons Learned:
#### Binary Analysis:
Developed the ability to examine and interpret binary structures, such as headers, code, and data sections.
#### Decompiling:
Used ILSpy to reverse engineer a binary and understand its flow and functionality in a high-level programming language.
#### Static Analysis:
Practiced extracting metadata, hashes, and indicators from binaries without execution.
#### Dynamic Analysis:
Safely executed a binary in a sandbox to observe its behavior and validate findings from static analysis.
#### Identifying Malicious Behavior:
Gained experience spotting unusual patterns in binary execution, such as downloading unexpected files or connecting to external URLs.

### 5. Achievement
Day 21 was an exciting dive into the world of reverse engineering. It was fascinating to break down a binary into readable components and uncover its intended behavior. The combination of static and dynamic analysis reinforced the importance of a methodical approach to reverse engineering. This task honed my investigative skills and deepened my understanding of how binaries interact with systems, preparing me for more advanced analysis in cybersecurity scenarios.
