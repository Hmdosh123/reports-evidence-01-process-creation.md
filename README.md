# SOC Analyst Lab — Day 16: Brute-Force Detection with Splunk

## 📌 Project Overview

This project is part of my hands-on **30-Day SOC Analyst Training Lab**, focused on security monitoring, log analysis, threat detection, and incident investigation using Splunk on Kali Linux.

For Day 16, I investigated Windows failed-logon events to identify suspicious authentication activity and assess whether the evidence indicated a possible brute-force attack.

The goal was to practice a real SOC analyst workflow: collecting evidence, writing SPL queries, investigating suspicious activity, and documenting findings.

## 🎯 Objectives

- Investigate Windows failed-logon events (Event ID 4625).
- Identify the targeted account and source IP address.
- Count failed authentication attempts.
- Investigate the timeframe and frequency of failed logons.
- Check whether multiple accounts were targeted.
- Identify the Windows logon type and relevant event fields.
- Document findings and determine appropriate next investigative steps.

## 🛠️ Tools and Technologies

- **Splunk:** SIEM searches and log analysis
- **Kali Linux:** Lab environment
- **Windows Security Events:** Authentication investigation
- **SPL:** Search Processing Language
- **MITRE ATT&CK:** Framework for mapping validated behavior to attack techniques

## 🔎 Investigation Summary

During the investigation, I identified Windows failed-logon events and extracted the following initial evidence
