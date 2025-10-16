# AI-Powered-Cyber-Threat-Monitoring-Alerting-
Automates cybersecurity log monitoring using AI. Logs from Suricata are sent to Wazuh, forwarded via Cloudflare Tunnel to n8n, enriched with Gemini, VirusTotal &amp; AbuseIPDB, and delivered as real-time, human-readable alerts via Telegram for faster threat response.
# AI-Powered Cyber Threat Monitoring & Alerting

## Project Overview
This project automates cybersecurity log monitoring and threat analysis using AI-driven workflows. Logs from a local PC are collected through **Suricata** and sent to **Wazuh** for attack-level classification. Using a **Cloudflare Tunnel**, logs are forwarded to **n8n automation**, where an **AI agent** analyzes and enriches them with threat intelligence from **Gemini API**, **VirusTotal**, and **AbuseIPDB**.  

The enriched data is parsed into a **human-readable format** and delivered as **real-time alerts via a Telegram bot**, helping security analysts quickly respond to threats without manual log inspection.

---

## Features
- Automated collection of system logs from local PC using Suricata  
- Classification of attacks using Wazuh  
- Automated workflow orchestration using n8n and Cloudflare Tunnel  
- AI-driven log analysis and threat enrichment  
- Integration with multiple threat intelligence sources (Gemini, VirusTotal, AbuseIPDB)  
- Human-readable output for easy understanding of threats  
- Real-time alerts sent via Telegram bot  

---

## Tech Stack
- **Log Collection & Security:** Suricata, Wazuh  
- **Automation & Orchestration:** n8n, Webhooks  
- **Threat Intelligence APIs:** Gemini API, VirusTotal, AbuseIPDB  
- **Connectivity:** Cloudflare Tunnel  
- **Alerting:** Telegram Bot  

---

## Project Workflow
1. **Log Collection:** Suricata collects logs from your local PC.  
2. **Classification:** Logs are sent to Wazuh, where they are categorized based on attack severity.  
3. **Forwarding Logs:** Cloudflare Tunnel forwards logs securely to n8n automation.  
4. **AI Analysis:** n8n AI agent analyzes the logs and enriches them with threat intelligence from Gemini API, VirusTotal, and AbuseIPDB.  
5. **Human-Readable Output:** Logs are converted into an easy-to-understand format using a structured output parser.  
6. **Alert Delivery:** Telegram bot receives and sends real-time notifications to users for immediate threat response.  

---
