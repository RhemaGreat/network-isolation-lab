# Network Isolation Lab

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Platform](https://img.shields.io/badge/Platform-Linux-success)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

Network Isolation Lab is a Python-based cybersecurity research project demonstrating how network packets can be intercepted and blocked using Linux NetfilterQueue.

The project serves as a minimal proof-of-concept for understanding packet filtering, firewall behavior, and network isolation techniques in a controlled laboratory environment.

This repository is intended for educational purposes and defensive cybersecurity research only.

---

## Features

- Intercepts packets using NetfilterQueue
- Demonstrates packet dropping
- Simple and lightweight implementation
- Useful for learning Linux packet processing
- Foundation for advanced firewall and IDS research

---

## Technologies

- Python 3
- NetfilterQueue
- Linux
- iptables

---

## Project Structure

```
network-isolation-lab/
│
├── net_cut.py
└── README.md
```

---

## Requirements

- Python 3
- Linux
- Root privileges
- NetfilterQueue
- iptables

Install the dependency:

```bash
pip install NetfilterQueue
```

---

## Usage

Configure an iptables rule to forward packets to NetfilterQueue, then run:

```bash
sudo python3 net_cut.py
```

The script will intercept packets from Queue 0 and drop them.

---

## Learning Objectives

This project demonstrates:

- Linux packet processing
- NetfilterQueue integration
- Packet filtering
- Firewall fundamentals
- Network isolation concepts
- Defensive security research

---

## Ethical Notice

This software is intended exclusively for:

- cybersecurity education
- defensive research
- laboratory testing
- authorized security assessments

Do not deploy or use this software on networks you do not own or have explicit permission to test.

---

## Future Improvements

- Configurable filtering rules
- CLI arguments
- Packet logging
- Selective packet blocking
- Protocol-specific filtering
- Statistics dashboard
- Unit tests

---

## Author

**Rhema Great**

GitHub: https://github.com/RhemaGreat

---

## License

This project is licensed under the MIT License.
