# HydraDNS — DNS Security & Privacy Gateway

HydraDNS is a **DNS-layer security and privacy gateway** designed to run seamlessly on both **lightweight hardware** (Raspberry Pi, NUC) and **cloud environments**. It acts as a transparent DNS forwarder/resolver with built-in security, privacy, and policy enforcement.

The main project lives at [hydradns/hydradns](https://github.com/hydradns/hydradns) — a single monorepo containing the core DNS engine, dashboard, CLI, and scanner.

## Overview

* Intercepts DNS queries transparently
* Enforces security policies
* Blocks malware, phishing, trackers, and ads
* Provides administrators with clear reports and CLI-based management

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

* **Logging & Monitoring**
  Structured logging for observability, with anonymized client IPs for privacy compliance.

* **Resilient & Performant**
  Connection pool with multiple upstream resolvers for failover and load balancing.

* **Bypass-Resistant**
  Detects and blocks client-side attempts to route around policy using DNS-over-HTTPS or DNS-over-TLS to third-party resolvers, so devices on the network can't silently escape enforcement.

## Open Source

HydraDNS is licensed under GPL-3.0 and is complete and usable on its own — see the [monorepo](https://github.com/hydradns/hydradns) for setup, docs, and contribution guidelines.
