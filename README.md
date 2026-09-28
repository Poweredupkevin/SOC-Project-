# SOC-Project-: Home SOC Lab

> 🚧 **Status: In progress.** This README describes the goals and planned design. Results, screenshots, and write-ups will be added as each phase is completed.

## Overview

Using **only open-source tools**, I'm building a home lab environment that simulates a **Security Operations Center (SOC)**, complete with **EDR** and **SIEM** tooling. The lab will also include a **web application server** that I can attack for **penetration testing practice** and then defend with **system hardening**.

## Goals

- Simulate a real SOC workflow: collect logs, detect suspicious activity, and investigate alerts
- Deploy and configure an open-source **SIEM** for log collection, analysis, and alerting
- Deploy an open-source **EDR** to monitor and respond on endpoints
- Stand up a **web app server** as a target for pentesting practice
- Apply **system hardening** and verify the improvements against the same attacks
- Document every step so others can follow along and learn from it

## Planned Lab Components

| Component | Purpose | Tool |
|-----------|---------|------|
| SIEM | Centralized log collection, searching, and alerting | Open-source (TBD) |
| EDR | Endpoint telemetry, detection, and response | Open-source (TBD) |
| Web app server | Target for pentesting practice and hardening | Open-source (TBD) |
| Attacker machine | Running the pentests against the web app server | Open-source (TBD) |

The list of tools will be filled in as the lab is built (see [`Tools you will need to follow along`](./Tools%20you%20will%20need%20to%20follow%20along)).

## Roadmap

- [ ] Plan the lab network and virtual machines
- [ ] Deploy the SIEM and onboard log sources
- [ ] Deploy the EDR agents on the endpoints
- [ ] Set up the web app server
- [ ] Pentest the web app server and capture the detections in the SIEM/EDR
- [ ] Harden the systems and retest
- [ ] Publish write-ups, diagrams, and screenshots

## Author

**Kevin Powers** · [GitHub](https://github.com/Poweredupkevin) · [LinkedIn](https://www.linkedin.com/in/kevinjpowersjr)
