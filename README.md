# Home SOC Lab

Build a small security lab at home, with free tools, so you can learn detection by doing it, not just by watching videos.

Total cost target: $0 for software. Hardware can be an old PC, a mini PC, or a virtual machine on a machine you already own.

## What you will learn

- How logs flow from a machine to a detector
- How to write a detection for a real attack technique
- How to investigate an alert without guessing
- How to present a finding clearly, the way a SOC analyst would

## Lab layout

1. One attacker machine: Kali Linux, virtual, isolated from your home network.
2. One target machine: Windows or Linux, virtual, with logging turned on.
3. One detector: Wazuh or Security Onion, virtual, collecting logs from the target.
4. One notes file: every alert you investigate, what you found, and what you would do next.

Keep the lab on its own virtual network. Do not point lab attacks at real systems, real employers, or the public internet.

## Week by week

Week 1: Install the virtual machines, get logs flowing, and confirm one clean login shows up in the detector.
Week 2: Run a simple password spray in the lab, find it in the logs, and write a detection for it.
Week 3: Run a phishing simulation in the lab (your own mailbox only), trace the attachment, and write up the investigation.
Week 4: Pick one MITRE ATT&CK technique, execute it safely in the lab, and document the detection and the gap.

## Rules

- Lab only. Never test against a system you do not own and control.
- No real credentials, no real company data, no real customer data in the lab.
- Every experiment ends with a write-up: what you did, what you saw, what you learned.

## Free tools to start with

- Wazuh: https://wazuh.com/
- Security Onion: https://securityonionsolutions.com/
- Kali Linux: https://www.kali.org/
- MITRE ATT&CK: https://attack.mitre.org/

A lab that only runs attacks is a toy. A lab that ends with detections and write-ups is a portfolio.
