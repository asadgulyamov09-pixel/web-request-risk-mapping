# Web Request Lifecycle: My First Risk & Control Analysis

## Project Overview
This is my very first project on the **Technical GRC Roadmap**. As a 10th-grade student and aspiring GRC Engineer, I am learning to bridge the gap between technical web protocols and risk management.

**Note:** I am currently in the "Learning & Research" phase. This project represents my initial research into how network stages relate to potential security threats and industry standards.

## What I Researched This Week
- **The Lifecycle of a Web Request:** From DNS lookup to data transfer.
- **Threat Awareness:** I studied theoretical attacks like DNS Spoofing, MitM, and SYN Floods to understand *why* we need security controls.
- **Introduction to Frameworks:** I began exploring how technical solutions (like TLS) align with global standards such as **ISO 27001** and **NIST**, even though I am just starting to study these frameworks in detail.

## Initial Risk & Control Matrix (Research Draft)
| Step | Protocol | Threat Studied | Potential Control | Why it matters (CIA) |
| :--- | :--- | :--- | :--- | :--- |
| **DNS** | DNS | DNS Spoofing | DNSSEC | Integrity |
| **Connection** | TCP | SYN Flood (DDoS)| Firewalls/WAF | Availability |
| **Encryption** | TLS | MitM Attack | TLS 1.3 | Confidentiality |
| **Data** | HTTP | Session Theft | Secure Cookies | Confidentiality |

## Methodology
- **Research:** Used documentation and AI to identify common vulnerabilities at each stage of a web request.
- **Risk Thinking:** Practiced thinking about "What could go wrong?" at every step.
- **Documentation:** Learning to use Markdown and GitHub to present technical findings clearly.
**Author:** Asadbek
**Level:** Beginner / Student
**Date:** May 2026
