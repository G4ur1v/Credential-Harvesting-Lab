# Credential-Harvesting-Lab
Technical analysis and Proof-of-Concept (PoC) of phishing simulations using Termux and Ngrok for educational research and vulnerability study.








🛡️ 𝗣𝗵𝗶𝘀𝗵𝗶𝗻𝗴 𝗦𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻 & 𝗦𝗼𝗰𝗶𝗮𝗹 𝗘𝗻𝗴𝗶𝗻𝗲𝗲𝗿𝗶𝗻𝗴 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀.
-------------------------------------------------------------------------------
𝐄𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭.: Android (Termux) 

𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤.: Zphisher 

 𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠.: Ngrok
 
 
📖 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰.
This repository serves as a Proof of Concept (PoC) for educational purposes. It documents a series of simulations performed during my early years (11th-12th grade) to understand how Social Engineering and WAN Tunneling are used to harvest credentials.
The objective was to analyze the vulnerabilities in the "Human Element" of cybersecurity and study the technical infrastructure of automated phishing frameworks.
-------------------------------------------------------------------------------
🛠️ 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐒𝐭𝐚𝐜𝐤.
Platform: Termux (Linux environment for Android)
𝐂𝐨𝐫𝐞 𝐓𝐨𝐨𝐥:. Zphisher (v2.2)
𝐓𝐮𝐧𝐧𝐞𝐥𝐢𝐧𝐠: Ngrok (Secure Tunneling Protocol)
𝐁𝐚𝐜𝐤𝐞𝐧𝐝::: PHP & Apache (Local Server)
𝐁𝐚𝐜𝐤𝐞𝐧𝐝:: HTTP/HTTPS via Ngrok Tunnel
-------------------------------------------------------------------------------
🚀 𝐒𝐢𝐦𝐮𝐥𝐚𝐭𝐢𝐨𝐧 𝐌𝐞𝐭𝐡𝐨𝐝𝐨𝐥𝐨𝐠𝐲
The simulation was divided into three core phases:
1. Environment & Dependencies
Setting up the Termux environment by installing git, php, and curl. Cloning the Zphisher framework and configuring executive permissions.
2. WAN Port Forwarding (Ngrok Integration)
Instead of a Local Area Network (LAN) attack, Ngrok was utilized to expose the local PHP server to the Wide Area Network (WAN).  
-------------------------------------------------------------------------------
𝐓𝐡𝐢𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝:
Authenticating the Ngrok token.
Mapping local port 8080 to a public Ngrok URL.
Analyzing the latency and stability of the secure tunnel.
-------------------------------------------------------------------------------
3. Credential Harvesting & Log Analysis
A cloned UI (User Interface) was deployed to simulate a login portal. Upon user interaction:
POST Requests were intercepted.
Data was logged into local flat files (usernames.dat).
Metadata Analysis: Captured IP addresses, User-Agents, and device specifications of the connecting client.
-------------------------------------------------------------------------------
🛡️ 𝐌𝐢𝐭𝐢𝐠𝐚𝐭𝐢𝐨𝐧 & 𝐃𝐞𝐟𝐞𝐧𝐬𝐞 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐞𝐬
The primary goal of this research was to build better defense mechanisms:
Multi-Factor Authentication (MFA): The most effective defense against credential harvesting.
Domain Reputation Analysis: Using tools to identify suspicious Ngrok or obfuscated URLs.
Email Header Inspection: Identifying spoofed sources.
-------------------------------------------------------------------------------
⚖️ 𝐋𝐞𝐠𝐚𝐥 𝐃𝐢𝐬𝐜𝐥𝐚𝐢𝐦𝐞𝐫
This project is for EDUCATIONAL PURPOSES ONLY. I do not support or encourage illegal activities. All simulations were conducted in a controlled environment with full consent for research purposes.
