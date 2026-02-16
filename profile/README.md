# LeakRadar.io

**Search 280 billion+ plain-text credentials** collected from malware logs, combolists, database breaches and dark-web dumps. Get alerted before attackers act.

[![Website](https://img.shields.io/badge/Website-leakradar.io-blue)](https://leakradar.io)
[![API Docs](https://img.shields.io/badge/API%20Docs-docs.leakradar.io-green)](https://docs.leakradar.io)
[![Status](https://img.shields.io/badge/Status-status.leakradar.io-brightgreen)](https://status.leakradar.io)
[![Python Wrapper](https://img.shields.io/badge/pip-leakradar-yellow)](https://pypi.org/project/leakradar/)
[![Twitter](https://img.shields.io/badge/Twitter-@LeakRadario-1DA1F2)](https://x.com/LeakRadario)

---

### What is LeakRadar?

LeakRadar.io is a threat-intelligence platform built for security teams, pentesters and incident responders. It indexes credentials exclusively from public forums and Telegram channels, stores them as plain text (no hashes, no redaction), and lets you query them in milliseconds.

Searches are free and unlimited. Unlocking credentials (revealing usernames and passwords in clear text) costs one credit per record, drawn from a daily quota tied to your subscription plan.

---

### Search Modes

- **Email Search**
  Query a single address and instantly see every leak containing it.

- **Domain Search**
  Map a domain's full exposure. Results are automatically categorized into employees, third-party accounts and customers.

- **Advanced Search**
  Combine multiple criteria with boolean operators, wildcards and field filters across: `url`, `url_host`, `url_domain`, `url_tld`, `url_scheme`, `url_port`, `username`, `password`, `email_host`, `email_domain`, `email_tld`.

- **Dark Web Search**
  Search through posts from dark web forums to find mentions of your assets, credentials or organization.

- **Raw Search**
  Query the full raw leak archive (including stealer logs and large breach dumps), by text or by container ID, and export results when you need to work with them offline.

---

### Monitoring & Alerts

Set up monitoring for emails and domains. When a new leak is detected, receive an alert through the channel of your choice:

- Email
- Slack
- Telegram
- Webhook

---

### Teams

Share access with your security team so analysts and engineers can investigate leaks from a single account.

---

### API & Python Wrapper

Full REST API documentation: [docs.leakradar.io](https://docs.leakradar.io)

**Python wrapper:**

```bash
pip install leakradar
```

Source: [github.com/LeakRadar/leakradar-wrapper](https://github.com/LeakRadar/leakradar-wrapper)

**Rate limits:** 30 req/s for all plans, except Mass Check endpoints (1 req/s) and Advanced Search endpoints (5 req/s).

---

### Why Use LeakRadar?

- **Early Threat Detection** — Identify compromised accounts and credentials before attackers exploit them.
- **Operational Security** — Give your SOC, incident response or security team a single place to investigate exposure across stealer logs and public breaches.
- **Compliance & Trust** — Support customers, partners and auditors that you actively monitor for leaked credentials.

---

### Get Started

1. Go to [leakradar.io](https://leakradar.io) and create an account — no credit card required.
2. Add the domains and emails you want to monitor.
3. Configure alerts (Email, Slack, Telegram or Webhook).
4. Use the dashboard or API to search leaks, investigate incidents and export data when needed.

For pricing and plan details, see the [website](https://leakradar.io).

---

### Legal Notice

You are responsible for ensuring that all searches and monitoring are performed with proper authorization and in compliance with all applicable laws and regulations.
LeakRadar.io is intended only for defensive security, monitoring and incident response use cases.

© 2026 LeakRadar.io · All rights reserved.
