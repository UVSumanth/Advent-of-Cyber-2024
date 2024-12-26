# Advent of Cyber 2024: Day 13 - It came without buffering! It came without lag!

**Summary of Task Completion**

### 1. Overview
Day 13 focused on understanding WebSockets and their vulnerabilities, specifically WebSocket Message Manipulation. This task delved into how WebSockets facilitate real-time communication and how attackers can exploit these connections to tamper with data or gain unauthorized access. Through practical exercises, I explored the risks associated with WebSocket implementations and gained insights into secure development practices.

### 2. Tools Used:
#### Burp Suite:
Used to intercept and manipulate WebSocket messages to demonstrate vulnerabilities.
Explored the WebSocket communication process and identified exploitable parameters.
#### AttackBox and Virtual Machine:
Provided a secure environment to investigate WebSocket interactions in the Reindeer Tracker web app.

### 3. General Topics and Concepts Covered:
#### Understanding WebSockets:
Learned how WebSockets provide real-time, two-way communication between a client and server, minimizing overhead compared to traditional HTTP requests.
#### WebSocket Vulnerabilities:
Explored common vulnerabilities such as weak authentication, message tampering, and Cross-Site WebSocket Hijacking (CSWSH).
#### WebSocket Message Manipulation:
Focused on altering WebSocket messages to modify application behavior or gain unauthorized access.
#### Impact of Insecure WebSocket Implementations:
Highlighted how insufficient validation and security checks can lead to unauthorized actions, data breaches, or privilege escalation.

### 4. Skills and Lessons Learned:
#### Intercepting WebSocket Traffic:
Used Burp Suite to capture and analyze WebSocket messages, identifying key parameters that control application behavior.
#### Manipulating WebSocket Messages:
Successfully altered messages to simulate unauthorized tracking of another user's car in the application.
#### Exploring Real-World Scenarios:
Examined how attackers could exploit message tampering to gain admin privileges, manipulate data, or disrupt application functionality.
#### Mitigation Techniques:
##### Learned best practices to secure WebSocket implementations, including:
Enforcing robust authentication and authorization.
Encrypting WebSocket messages to prevent tampering.
Validating and sanitizing all input at the server level.
Implementing rate limits to mitigate abuse of WebSocket connections.

### 5. Achievement
Day 13 was an enlightening exploration of WebSocket security. It demonstrated how critical real-time communication is for modern applications and the associated risks if not implemented securely. By actively exploiting a simulated vulnerability, I reinforced the importance of rigorous validation and secure design practices for WebSocket-based applications.
