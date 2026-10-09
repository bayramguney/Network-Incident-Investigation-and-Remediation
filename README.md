# Training and Awareness Through Simulation

## Overview

This repository contains my completed **Assisted Lab: Training and Awareness Through Simulation**, completed as part of my cybersecurity training. The lab demonstrates how phishing and social engineering attacks exploit human behavior to gain unauthorized access to systems. By observing both the attacker and victim perspectives in a controlled environment, I gained a deeper understanding of how these attacks occur and how organizations can defend against them through security awareness and layered security controls.

> **Note:** This lab was performed in a safe, isolated training environment for educational purposes only.

---

## Objectives

- Understand common social engineering attacks
- Observe how phishing campaigns target users
- Learn how reverse shell attacks can occur after user interaction
- Recognize the importance of security awareness training
- Understand how outbound network connections can be abused
- Identify defensive measures to reduce phishing risks

---

## CompTIA Security+ Objectives

- **2.2:** Explain common threat vectors and attack surfaces.
- **5.6:** Given a scenario, implement security awareness practices.

---

## Lab Environment

| Machine | Operating System | Purpose |
|----------|------------------|---------|
| **KALI** | Kali Linux | Simulated attacker workstation |
| **MS10** | Windows Server 2016 | Simulated victim workstation |

---

## Scenario

As a security team member at **Structureality Inc.**, I participated in a security awareness simulation designed to demonstrate how phishing attacks compromise systems. The lab illustrated both the attacker's preparation and the victim's actions that ultimately resulted in a simulated reverse shell connection.

The purpose of this exercise was to understand how attackers manipulate users through believable emails and how organizations can reduce risk through user education and security best practices.

---

# Skills Demonstrated

- Social engineering awareness
- Phishing attack analysis
- Threat vector identification
- Security awareness training
- Reverse shell concepts
- Network communication fundamentals
- User behavior analysis
- Defensive security practices
- Risk identification
- Cybersecurity incident awareness

---

# Lab Activities

## 1. Preparing the Simulated Attack

The attacker workstation was configured to support the simulation by:

- Hosting demonstration files on a web server
- Reviewing supporting scripts
- Starting required services
- Preparing to receive a simulated outbound connection

This phase demonstrated how attackers prepare infrastructure before launching phishing campaigns.

---

## 2. Phishing Email Simulation

The lab presented a realistic phishing email pretending to be from an internal support team.

The message encouraged the victim to:

- Download a configuration update
- Execute the downloaded file
- Ignore operating system security warnings

The email relied on:

- Trust
- Authority
- Urgency
- Technical language

These techniques are commonly used in real phishing campaigns.

---

## 3. Victim Interaction

The simulated victim:

- Opened the phishing link
- Downloaded the file
- Executed the program
- Approved security prompts

Although these actions appeared harmless, they resulted in the victim unknowingly allowing unauthorized remote access.

---

## 4. Reverse Shell Demonstration

After the file executed, the victim system initiated an outbound connection back to the simulated attacker.

This demonstrated an important cybersecurity concept:

- Many organizations block unsolicited inbound traffic.
- Outbound connections are often more permissive.
- Attackers exploit this behavior to establish remote access.

---

## 5. Observing the Connection

Once the connection was established, the simulated attacker verified the remote session by:

- Identifying the computer name
- Confirming the logged-in user
- Observing remote command execution

This portion illustrated the potential impact of a successful phishing attack while remaining entirely within a controlled lab environment.

---

# Key Concepts Learned

## Phishing

Phishing is a social engineering technique that tricks users into performing actions that compromise security.

Common indicators include:

- Unexpected emails
- Urgent requests
- Fake IT support messages
- Suspicious links
- Unexpected attachments

---

## Social Engineering

Social engineering attacks manipulate people instead of exploiting technical vulnerabilities.

Common tactics include:

- Authority
- Trust
- Fear
- Curiosity
- Urgency
- Familiarity

---

## Pretexting

A pretext is the believable story attackers use to convince victims to act.

Examples from this lab included:

- System maintenance
- Equipment upgrades
- Configuration updates
- Internal IT support

---

## Reverse Shell

A reverse shell allows a compromised system to initiate communication with an external attacker.

This approach can bypass traditional firewall protections because the connection originates from inside the network.

---

## Egress Traffic

Egress traffic refers to outbound network communication.

Monitoring outbound traffic helps security teams detect:

- Malware communications
- Remote access attempts
- Command-and-control traffic
- Data exfiltration

---

# Defensive Best Practices

Organizations should implement multiple security controls, including:

- Security awareness training
- Multi-Factor Authentication (MFA)
- Email security filtering
- Web filtering
- Endpoint Detection and Response (EDR)
- Application allow listing
- Network monitoring
- SIEM solutions
- Regular phishing simulations
- User reporting procedures

---

# Real-World Relevance

Phishing remains one of the most common initial access methods used by cybercriminals and ransomware groups.

SOC analysts regularly investigate:

- Suspicious emails
- Malicious downloads
- Endpoint alerts
- User-reported phishing attempts
- Unusual outbound connections
- Indicators of compromise (IOCs)

Understanding the complete attack lifecycle helps security professionals recognize threats earlier and respond more effectively.

---

# Key Takeaways

- Human error is often the weakest link in cybersecurity.
- Successful phishing attacks rely on convincing social engineering rather than technical exploits.
- Reverse shell attacks commonly leverage outbound network connections.
- Security awareness training significantly reduces phishing risk.
- Layered security controls provide stronger protection than relying on a single defense.

---

# Technologies Used

- Kali Linux
- Windows Server 2016
- Apache Web Server
- Netcat (training demonstration)
- Firefox
- Windows Command Prompt

---

# What I Learned

This lab improved my understanding of how phishing attacks succeed through social engineering rather than software vulnerabilities. I learned how attackers use convincing pretexts to influence user behavior and how an outbound connection can establish unauthorized remote access. Most importantly, I gained a greater appreciation for the role of security awareness training, user education, and layered security controls in defending organizations against phishing attacks.

---

## Repository Tags

`cybersecurity` `security-awareness` `social-engineering` `phishing` `reverse-shell` `securityplus` `soc-analyst` `incident-response` `defensive-security` `skillable`
