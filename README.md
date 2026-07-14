# Production AI & Automation Portfolio

A collection of enterprise-ready AI agents and workflows built with n8n and OpenAI.

## 🏗️ Core Engines

### 1. Revenue Operations Engine
* **Location:** `/engine-01-revenue-ops`
* Automates inbound webhooks, sanitizes lead data, and uses an OpenAI Chat Model for automated lead intent scoring.

### 2. Conversational Booking State Machine
* **Location:** `/engine-02-state-booking`
* Manages live calendar slots, updates, and cancellations while utilizing a dedicated Global Error Handler subnet for reliability.

### 3. Support & SLA Escalation Engine
* **Location:** `/engine-03-support-sla`
* Uses AI spam filters to save token costs and dynamically routes tickets to 6 paths (FAQ, Bug, Refund, etc.) with automatic SLA breach watchdogs.
