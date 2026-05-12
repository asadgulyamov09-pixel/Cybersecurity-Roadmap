# Logging and Journalctl

## Overview

Logs are one of the most important security controls in cybersecurity and GRC.

During this lab, I practiced:
- journalctl
- error logs
- critical logs
- live monitoring
- log analysis

---

# What Are Logs

Logs are records of activity inside a Linux system.

They help organizations:
- monitor systems;
- detect attacks;
- investigate incidents;
- provide audit evidence.

---

# Why Logging Matters

Without logging:
- attacks may go unnoticed;
- investigations become difficult;
- organizations lose visibility;
- there is no audit evidence.

Logging supports both security and compliance.

---

# journalctl

`journalctl` is used to view and analyze system logs in Linux.

---

# Commands Practiced

# Error Logs


sudo journalctl -p err -b

Shows errors since boot.

Critical Logs
sudo journalctl -p crit

Shows critical events.

Live Monitoring
sudo journalctl -f

Displays logs in real time.

---

# Important Linux Directories
|Directory|Purpose|
|---|---|
|/home|User directories|
|/etc|System configuration files|
|/var/log|System and security logs|
|/tmp|Temporary files|
|/var/www|Website files|

Security Perspective

Directories such as /etc and /var/log are important for system security.

If attackers gain unauthorized access to configuration files or logs, it may lead to:

data exposure;
privilege escalation;
system compromise;
operational disruption.

---

# GRC Perspective

In GRC, logs are considered:

audit evidence

Logs help demonstrate:

accountability;
monitoring;
operational security;
compliance.

---

# ISO 27001 Mapping
|Logging Control|ISO 27001|
|---|---|
|journalctl|A.12 Operations Security|
|monitoring logs|A.12 Logging and Monitoring|

---

# Conclusion

Logging is not only a technical feature.

It is a critical security and compliance control that helps organizations reduce business risks.
