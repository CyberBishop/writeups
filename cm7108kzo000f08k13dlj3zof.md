---
title: "Building a Cybersecurity Lab"
datePublished: Tue Feb 11 2025 21:39:13 GMT+0000 (Coordinated Universal Time)
cuid: cm7108kzo000f08k13dlj3zof
slug: building-a-cybersecurity-lab
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1739309829766/40b1cbf7-8685-490a-aacd-9e16e526df77.png
tags: virtual-machine, hacking, active-directory, cybersecurity, infosec-cjbi6apo9015yaywu2micx2eo, cybersecurity-1, homelab, ethicalhacking, information-security, blueteam

---

In this series, I will document the process of setting up a virtual lab environment as part of a technical assessment I received from \[Redacted Company\]. While the assessment outlined specific tasks, it did not provide clear instructions on how to implement them.

For example, the task mentioned deploying GPO policies but did not explicitly state that Active Directory (AD) was required 😑. Due to prior knowledge, I was able to determine that AD was necessary to achieve the intended configuration.

What to Expect in This Series

This series will break down the assessment tasks into clear, step-by-step implementation guides, covering:

🔹 Lab 1: Setting Up a Virtualized Windows Environment

• Installing Windows Server 2019 and Windows 10 Pro in VMware

• Configuring networking and firewall rules

• Implementing Group Policy Objects (GPOs) for system restrictions

• Deploying software packages through GPO

🔹 Lab 2: Deploying Wazuh SIEM for Log Collection

• Setting up Wazuh Manager and Agents

• Configuring Windows Event Log collection

• Testing real-time security monitoring

Beyond just following the assessment requirements, this guide will provide insight into key decisions, troubleshooting steps, and best practices. Whether you’re preparing for a similar technical assessment or looking to build your own cybersecurity lab, this series will offer practical knowledge and a structured approach to virtual lab deployment.

Let’s get started! 🚀