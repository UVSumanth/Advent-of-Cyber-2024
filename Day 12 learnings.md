# Advent of Cyber 2024: Day 12 - If I can’t steal their money, I’ll steal their joy!

**Summary of Task Completion**

### 1. Overview
Day 12 revolved around understanding and exploiting race conditions in web applications. The task highlighted how concurrent requests can lead to vulnerabilities, allowing attackers to manipulate transactions and cause unintended behavior. Through a practical exercise, I explored how race conditions occur and learned methods to identify and mitigate them effectively.

### 2. Tools Used:
#### Burp Suite:
Used to intercept, analyze, and manipulate HTTP requests during the task.
Leveraged the Repeater tool to send multiple concurrent requests.
#### AttackBox and Virtual Machine:
Provided a secure, controlled environment to simulate and exploit race conditions in a banking application.

### 3. General Topics and Concepts Covered:
#### Understanding Race Conditions:
Learned how race conditions occur when multiple requests attempt to access and modify shared resources simultaneously.
Explored a real-world example involving fund transfers in a banking application.
#### Time-of-Check to Time-of-Use (TOCTOU) Flaws:
Discussed the vulnerability caused by delays between validating a condition and acting on it, allowing exploitation in that window.
#### Impact of Race Conditions:
Highlighted the risks, such as financial loss, data corruption, and application instability, when race conditions are exploited.
#### Atomic Transactions:
Understood the importance of atomic operations in preventing race conditions by ensuring all steps are completed as a single, indivisible action.

### 4. Skills and Lessons Learned:
#### Intercepting and Manipulating Requests:
Gained hands-on experience in capturing HTTP requests and analyzing the parameters to identify vulnerabilities.
#### Simulating Race Conditions:
Successfully exploited a race condition by sending simultaneous fund transfer requests, causing inconsistent account balances.
#### Analyzing Source Code for Vulnerabilities:
Reviewed provided source code to identify gaps in transaction handling, such as the lack of atomic operations or proper locking mechanisms.
#### Mitigating Race Conditions:
Learned preventive measures, including:
Implementing atomic transactions.
Using mutex locks to ensure sequential processing of critical operations.
Applying rate limiting to reduce the likelihood of concurrent exploit attempts.

### 5. Achievement
Day 12 provided valuable insights into the subtle yet critical nature of race conditions in web applications. By exploiting a simulated vulnerability, I understood the real-world consequences of improper transaction handling and the importance of designing secure, robust applications. The task reinforced the need for meticulous testing and secure coding practices to mitigate such risks.
