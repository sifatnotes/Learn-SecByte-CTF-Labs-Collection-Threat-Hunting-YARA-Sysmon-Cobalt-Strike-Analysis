# Learn-SecByte-CTF-Labs-Collection-Threat-Hunting-YARA-Sysmon-Cobalt-Strike-Analysis
A curated collection of hands-on threat hunting and malware investigation CTF labs covering Cobalt Strike, Qakbot, TrickBot, Emotet, WannaCry, NotPetya, YARA, Sigma, and Sysmon telemetry from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on threat hunting, malware investigation, and detection engineering labs designed for cybersecurity students, CTF players, threat hunters, SOC analysts, and incident response engineers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Proactive threat hunting and rapid malware triage are essential skills in modern Security Operations Centers (SOC). Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of threat hunting challenges focuses on identifying adversary indicators before full compromise occurs.

From tracking down Cobalt Strike C2 beacons, dissecting major malware botnets and destructive wiper strains (Qakbot, TrickBot, Emotet, WannaCry, NotPetya), to crafting custom YARA signatures, Sigma detection logic, and analyzing Windows Sysmon telemetry, these labs provide real-world training to refine your defense capabilities.

---

## Lab Collection & Index

Below is the complete, searchable index of all threat hunting and malware analysis challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Malware Case Study: Cobalt Strike Beacon Hunting** | Threat Hunting | Memory inspection, named pipe detection, C2 beacon hunting, reflective DLLs | [Access Lab](https://learn.secbyte.org/ctf/malware-case-study-cobalt-strike-beacon-hunting) |
| 2 | **Malware Case Study: Qakbot** | Botnet Analysis | Modular botnet execution, DLL injection, email thread hijacking, exfiltration | [Access Lab](https://learn.secbyte.org/ctf/malware-case-study-qakbot) |
| 3 | **Malware Case Study: TrickBot Deep Dive** | Botnet Analysis | Web inject modules, domain enumeration, webmail harvesting, privilege escalation | [Access Lab](https://learn.secbyte.org/ctf/malware-case-study-trickbot-deep-dive) |
| 4 | **Malware Case Study: Emotet** | Botnet Analysis | Polymorphic loader triage, VBA macro delivery, automated spam propagation | [Access Lab](https://learn.secbyte.org/ctf/malware-case-study-emotet) |
| 5 | **NotPetya Malware Case Study: From Supply Chain to Destructive Impact** | Wiper & Ransomware | Supply chain compromises, MBR wiping, PsExec lateral movement, EternalBlue | [Access Lab](https://learn.secbyte.org/ctf/notpetya-malware-case-study-from-supply-chain-to-destructive) |
| 6 | **WannaCry Malware Case Study** | Wiper & Ransomware | MS17-010 EternalBlue exploitation, doublepulsar payload, kill-switch analysis | [Access Lab](https://learn.secbyte.org/ctf/wannacry-malware-case-study) |
| 7 | **Real-World Malware Investigations** | Incident Response | Host triage, multi-stage attack reconstruction, forensic artifact collection | [Access Lab](https://learn.secbyte.org/ctf/real-world-malware-investigations) |
| 8 | **Malware Timeline Analysis: From Infection to Impact** | Forensic Analysis | Event log analysis, MFT/USN journal triage, execution timeline mapping | [Access Lab](https://learn.secbyte.org/ctf/malware-timeline-analysis-from-infection-to-impact) |
| 9 | **Threat Hunting with YARA: Hunt, Triage, & Detect Malicious Artifacts** | Detection Engineering | YARA rule drafting, string matching, condition optimization, file scanning | [Access Lab](https://learn.secbyte.org/ctf/threat-hunting-with-yara-hunt-triage-detect-malicious-artifa) |
| 10 | **Threat Hunting with Sigma: From Logs to Detections** | Detection Engineering | SIEM-agnostic rule writing, event ID mapping, log query translation | [Access Lab](https://learn.secbyte.org/ctf/threat-hunting-with-sigma-from-logs-to-detections) |
| 11 | **Threat Hunting with Sysmon: The Beacon Trace Case** | Telemetry & Monitoring | Process creation (Event ID 1), network connection (Event ID 3), C2 detection | [Access Lab](https://learn.secbyte.org/ctf/threat-hunting-with-sysmon-the-beacon-trace-case) |
| 12 | **Threat Hunting Fundamentals: Signals Before Incidents** | Threat Hunting | Hypothesis-driven hunting, baseline creation, anomalous activity detection | [Access Lab](https://learn.secbyte.org/ctf/threat-hunting-fundamentals-signals-before-incidents) |

---

## Categories

### 1. Threat Hunting & Telemetry Analysis
Learn hypothesis-driven threat hunting methods, process tracing, and Sysmon telemetry analysis to identify malicious beacons and abnormal host activity.
- [Threat Hunting Fundamentals: Signals Before Incidents](https://learn.secbyte.org/ctf/threat-hunting-fundamentals-signals-before-incidents)
- [Threat Hunting with Sysmon: The Beacon Trace Case](https://learn.secbyte.org/ctf/threat-hunting-with-sysmon-the-beacon-trace-case)
- [Malware Case Study: Cobalt Strike Beacon Hunting](https://learn.secbyte.org/ctf/malware-case-study-cobalt-strike-beacon-hunting)

### 2. Detection Engineering & Rules (YARA / Sigma)
Master drafting YARA rules to identify file artifacts in memory and converting Windows event logs into actionable Sigma detection rules.
- [Threat Hunting with YARA: Hunt, Triage, & Detect Malicious Artifacts](https://learn.secbyte.org/ctf/threat-hunting-with-yara-hunt-triage-detect-malicious-artifa)
- [Threat Hunting with Sigma: From Logs to Detections](https://learn.secbyte.org/ctf/threat-hunting-with-sigma-from-logs-to-detections)

### 3. Enterprise Botnet & Infrastructure Analysis
Deconstruct widespread enterprise botnet infrastructure, command execution channels, and module delivery vectors.
- [Malware Case Study: Emotet](https://learn.secbyte.org/ctf/malware-case-study-emotet)
- [Malware Case Study: Qakbot](https://learn.secbyte.org/ctf/malware-case-study-qakbot)
- [Malware Case Study: TrickBot Deep Dive](https://learn.secbyte.org/ctf/malware-case-study-trickbot-deep-dive)

### 4. Destructive Malware, Forensics & Timeline Investigation
Investigate global worm propagation, supply chain compromises, and execute forensic timeline analysis across impacted endpoints.
- [WannaCry Malware Case Study](https://learn.secbyte.org/ctf/wannacry-malware-case-study)
- [NotPetya Malware Case Study: From Supply Chain to Destructive Impact](https://learn.secbyte.org/ctf/notpetya-malware-case-study-from-supply-chain-to-destructive)
- [Real-World Malware Investigations](https://learn.secbyte.org/ctf/real-world-malware-investigations)
- [Malware Timeline Analysis: From Infection to Impact](https://learn.secbyte.org/ctf/malware-timeline-analysis-from-infection-to-impact)

---

## Learning Path

Follow this progression route to move from threat hunting concepts to advanced malware detection engineering:

1. **Phase 1: Hunting Foundations & Log Telemetry** — Understand basic telemetry signals and process monitoring:
   - [Threat Hunting Fundamentals: Signals Before Incidents](https://learn.secbyte.org/ctf/threat-hunting-fundamentals-signals-before-incidents)
   - [Threat Hunting with Sysmon: The Beacon Trace Case](https://learn.secbyte.org/ctf/threat-hunting-with-sysmon-the-beacon-trace-case)

2. **Phase 2: Detection Engineering** — Build detection logic with YARA and Sigma rules:
   - [Threat Hunting with YARA: Hunt, Triage, & Detect Malicious Artifacts](https://learn.secbyte.org/ctf/threat-hunting-with-yara-hunt-triage-detect-malicious-artifa)
   - [Threat Hunting with Sigma: From Logs to Detections](https://learn.secbyte.org/ctf/threat-hunting-with-sigma-from-logs-to-detections)

3. **Phase 3: Botnet & C2 Beacon Investigation** — Analyze active threat infrastructure and implants:
   - [Malware Case Study: Cobalt Strike Beacon Hunting](https://learn.secbyte.org/ctf/malware-case-study-cobalt-strike-beacon-hunting)
   - [Malware Case Study: Emotet](https://learn.secbyte.org/ctf/malware-case-study-emotet)
   - [Malware Case Study: Qakbot](https://learn.secbyte.org/ctf/malware-case-study-qakbot)
   - [Malware Case Study: TrickBot Deep Dive](https://learn.secbyte.org/ctf/malware-case-study-trickbot-deep-dive)

4. **Phase 4: Destructive Threats & Incident Forensics** — Analyze worm propagation and reconstruct attack timelines:
   - [WannaCry Malware Case Study](https://learn.secbyte.org/ctf/wannacry-malware-case-study)
   - [NotPetya Malware Case Study: From Supply Chain to Destructive Impact](https://learn.secbyte.org/ctf/notpetya-malware-case-study-from-supply-chain-to-destructive)
   - [Real-World Malware Investigations](https://learn.secbyte.org/ctf/real-world-malware-investigations)
   - [Malware Timeline Analysis: From Infection to Impact](https://learn.secbyte.org/ctf/malware-timeline-analysis-from-infection-to-impact)

---

## How to Use the Labs

1. Select a lab challenge link from the index or category sections above.
2. Review the scenario directives and telemetry samples provided on [Learn SecByte](https://learn.secbyte.org/).
3. Utilize log analysis tools (ELK Stack, Splunk, Sysmon log viewer) and rule validation frameworks (YARA CLI, Sigma tools).
4. Correlate telemetry events, validate hypotheses, extract malicious indicators, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized forensic training purposes. Performing unauthorized system monitoring, analysis, or testing on production networks is strictly prohibited.
