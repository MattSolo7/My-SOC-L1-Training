# My-SOC-L1-Training (A day In the life of a Junior (Associate) Security Analyst (TryHackMe Lab)

As an aspiring SOC analyst, I jumped into TryHackMe’s SOC Level 1 training with a mix of excitement and a bit of nervous anticipation. This wasn’t just theory—it was a deep dive into the real tools and frameworks that power cybersecurity every day. While I expected to work with familiar names like SIEMs, Wireshark, and Snort, I was genuinely thrilled to uncover powerful new tools like Autopsy, Zeek, and OSquery that I’d never even heard of before. Each hands-on challenge pushed me further, turning complex concepts into practical skills. This journey didn’t just expand my technical toolkit—it ignited my passion for defending the digital world.


![THM-RUBDE4ZDKZ SOC L1](https://github.com/user-attachments/assets/af1ad1a4-115f-49cd-bc95-13f315ef41e6)


Key Objectives of SOC Level 1


. Understanding SOC Operations

. Threat Intelligence and Analysis

. Security Tools and Techniques

. Incident Response and Management

. SIEM Fundamentals

. Malware Analysis Basics

. Cyber Defense Frameworks




A day In the life of a Junior (Associate) Security Analyst (TryHackMe Lab)


 Steps to Complete the Lab:
 
 
1. Started the Lab Environment
I began by clicking the green "View Site" button on TryHackMe, which launched a simulated SOC dashboard. This virtual environment included essential tools like the SIEM, IDS/IPS alerts, email logs, and network monitoring panels—all designed to mimic a real-world security operations center.


3. Reviewed Security Tickets and Inspected Alerts
I started by reviewing the security tickets in the SIEM dashboard to identify any new alerts. I carefully inspected each alert, noting important details like:

. Alert name

. Source and destination IPs

. Timestamps

. Detection tool (e.g., IDS, firewall, email)

As instructed, I searched the logs to find the malicious IP address, made note of it, and then clicked on the alert to dive deeper into the investigation. This step helped me focus on real threats right from the start.


3. Investigated the Alert
Using the security monitoring tool, I dug deeper into the alert by cross-checking:

. IDS/IPS logs

. Network traffic data

. Email headers and attachments

I looked for indicators such as:

. Suspicious file attachments

. Malicious IP or domain activity

. Signs of data exfiltration, lateral movement, or brute-force attempts

Each log felt like a puzzle piece—putting them together revealed the nature of the threat.


 4. Conducted Threat Intelligence Lookups
To verify the indicators of compromise (IOCs), I used open-source intelligence (OSINT) tools like:

. VirusTotal

. AbuseIPDB

. Shodan

By searching for suspicious IP addresses and file hashes, I could confirm if the activity was linked to known malicious actors or campaigns. This helped me make confident, evidence-based decisions.


5. Answered the Lab Questions
Once I had enough information, I returned to the TryHackMe interface and answered the questions based on my findings. Some of the questions included:

. What was the suspicious IP address?

. Was there a malicious file involved?

. Was any data exfiltrated?

. Which user or system was affected?

I made sure my answers were backed by the logs and threat intel I'd gathered earlier.


6. Planned Containment and Remediation
Based on the threat, I considered next steps like blocking the malicious IP, isolating the affected system, resetting credentials, and patching vulnerabilities. This reinforced how vital fast, effective response is to limit damage.

![A Day in the Life of a Junior (Associate) Security Analyst](https://github.com/user-attachments/assets/5da59edb-d627-4c00-88c9-0071d13ac98e)
![Websites to check malicious IPs](https://github.com/user-attachments/assets/4865a915-3771-4776-9e7b-2985987b1a7b)
![suspicious IP](https://github.com/user-attachments/assets/bb0ac6e9-d1e6-4bbb-be40-aeefa73864a7)
![Permission to block malicious IP](https://github.com/user-attachments/assets/cf1d4c8d-b1dd-460e-8416-fb8bb98a48c0)
![More Websites to check malicious IPs](https://github.com/user-attachments/assets/3111209e-2a04-4203-8dea-663799253e53)
![IP Scanner ](https://github.com/user-attachments/assets/39e9efb6-9ce6-4469-bb99-336e881ab7d3)
![IP is malicious ](https://github.com/user-attachments/assets/48ceb3c8-f851-44a7-9983-bc414458ecd0)
![Inaert IP](https://github.com/user-attachments/assets/7a56b774-e4a5-4e9b-936b-1a943b46d772)
![Escalating alerts](https://github.com/user-attachments/assets/fa5c1bc7-b45a-451c-93d6-196f11259b04)
![Escalate to the right people ](https://github.com/user-attachments/assets/17663d39-b9d2-4cbb-b24b-c43cc2b8f2f5)
![End of challenge ](https://github.com/user-attachments/assets/d8ffeec0-1105-4931-a48f-0fef876b751f)
![Block IP with a Firewall](https://github.com/user-attachments/assets/b7fc1c16-9413-42c9-9dc2-cc36ed55590e)
![Answer the questions below](https://github.com/user-attachments/assets/d697ecef-369c-42bb-afa1-ab972b980206)

