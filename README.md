# Splunk EVTX Threat Hunting Project

Author: Tyriq McNulty

This project demonstrates advanced threat hunting techniques using EVTX logs parsed in Splunk over the course of 3 weeks. It simulates a real-world compromise involving persistence, privilege escalation, spoofing, and execution techniques observed in malware campaigns.

##  Techniques Detected (MITRE ATT&CK)

- T1046: Network Service Scanning
- T1542.001: System Firmware
- T1547.001: Registry Run Keys
- T1055: Process Injection
- T1059.003: Windows Command Shell
- T1220: XSL Script Processing
- ...and more

##  Contents

Each directory contains detailed summaries, indicators, and mitigation strategies.

- `analysis/`: Breakdown of each threat-hunting log.
- `docs/`: Full project writeup.
- `evtx-logs/`: Sample logs (if public use is allowed).

##  Notes

No screenshots were included as all log entries and behaviors are fully documented with relevant fields (Event ID, Process Path, CommandLine, Hashes, etc.).

##  Credit

EVTX samples provided by: [sbousseaden/EVTX-ATTACK-SAMPLES](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES)

