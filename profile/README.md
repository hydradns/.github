# HydraDNS — DNS Security & Privacy Gateway

HydraDNS is a **DNS-layer security and privacy gateway** designed to run seamlessly on both **lightweight hardware** (Raspberry Pi, NUC) and **cloud environments**. It acts as a transparent DNS forwarder/resolver with built-in security, privacy, and policy enforcement.

## Overview

* Intercepts DNS queries transparently
* Enforces security policies
* Blocks malware, phishing, trackers, and ads
* Provides administrators with clear reports and CLI-based management
# HydraDNS — DNS Security & Privacy Gateway

## Key Features

* **Multi-Deployment Ready**
  Run directly on a Raspberry Pi connected to your router, or deploy as a containerized service in the cloud.

* **Policy Enforcement Engine**
  Define granular rules to allow, deny, or log queries. Protect networks from malware, phishing, spyware, and unwanted trackers.

* **Ad & Spyware Blocking**
  Built-in ad/tracker blocking powered by curated community and commercial blocklists.

* **Blocklist Engine**
  Import and update domain blocklists automatically, with caching for high-speed lookups.

* **Shell Access & CLI Management**
  Configure and control HydraDNS using a structured CLI shell, ideal for power users and automation.

* **Central Controller & Admin Dashboard (EE)**
  In enterprise deployments, a central dashboard provides unified policy management, visibility, and analytics across multiple sites.

* **Logging & Monitoring**

  * Structured logging for observability.
  * Anonymized client IPs (in CE) for privacy compliance.
  * Extended logging in EE for enterprise auditing.

* **Resilient & Performant**

  * Connection pool with multiple upstream resolvers for failover and load balancing.
  * Real-time enforcement with **sub-millisecond lookups**.
  * End-to-end DNS integrity with less than **5ms added latency**.

* **Privacy-First by Default**
  DNS logs anonymize client IPs in the Community Edition. Support for encrypted upstream resolvers (DoH/DoT) is built in.

## Community Edition (CE)

The open-source foundation includes:

* SQLite-backed policy storage
* Blocklists
* CLI shell
* Structured logging
* Docker deployment

The CE is aimed at **adoption, transparency, and portfolio credibility** while showcasing HydraDNS's core features.

<img width="952" height="1422" alt="96133290-f9b8-4184-8a6f-ee01af5345df_changed" src="https://github.com/user-attachments/assets/2bc5d75b-b692-437e-a9ad-0f528e02e39f" />
