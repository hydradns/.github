# HydraDNS

A self-hosted DNS firewall you can manage by talking to an AI agent. It blocks
ads, malware and trackers at the DNS level like Pi-hole, rebuilt in Go with an
API-first control plane and a built-in Model Context Protocol server, so Claude
or any MCP agent can run your network for you.

## Repositories

- **[hydradns](https://github.com/hydradns/hydradns)** the product: DNS engine,
  gRPC control plane, web dashboard, CLI and MCP server. GPL-3.0.
- **[hydradns-landing](https://github.com/hydradns/hydradns-landing)** the site
  at [hydradns.app](https://hydradns.app).

## What it does

- Blocks ads, malware and trackers at the DNS layer, before they reach a device
- Policy engine with allow, block and redirect rules via API, CLI or an AI agent
- Blocklists in hosts, domain and adblock formats, refreshed automatically
- A built-in MCP server (14 tools) so an AI assistant can manage the firewall
- Optional client-IP pseudonymisation for query logs

Pre-1.0 and moving fast. Runs with `docker compose up` on a Raspberry Pi, a NUC
or a cloud box.
