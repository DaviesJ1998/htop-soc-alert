# htop-soc-alert
L1 SOC demo: Detect high-CPU malware with htop &amp; escalate alerts
# htop-soc-alert

![Fedora](https://img.shields.io/badge/Fedora-42-blue?logo=fedora)
![SOC](https://img.shields.io/badge/SOC-L1-green)
![License](https://img.shields.io/github/license/yourname/htop-soc-alert)

> **Simulated SOC L1 alert**: Detect high-CPU process (malware-like) using `htop`, filter, and escalate with a ticket.

---

## Live Demo  
[Read the full walkthrough here](docs/README.md) (with screenshots)

---

## What This Shows
- Linux process monitoring (`htop`, `ps aux`)
- Filtering & sorting by CPU
- Alert creation & escalation
- Cross-verification with `ps`
- Ties to **Cyber Kill Chain (Exploitation)**

---

## Quick Run
```bash
./scripts/monitor_cpu.sh Brave
./scripts/generate_alert.sh 22017 60.2
