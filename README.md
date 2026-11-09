# payagent-ai-
Autonomous PayPal Commerce &amp; Escrow Agent powered by Gemini 2.5 Flash, PayPal Sandbox REST APIs, Generative UI receipt cards, Human-in-the-Loop guardrails, and a live AG Grid merchant ledger.



# ⚡ PayAgent AI — Autonomous PayPal Commerce & Escrow Agent

> Built for the **PayPal Agentic AI Hackathon**. An autonomous, mobile-first Agentic Commerce assistant featuring Generative UI PayPal cards, QR checkout, Human-in-the-Loop financial guardrails, and a real-time AG Grid merchant ledger.

## ✨ Key Features
- **🤖 Autonomous Agent Chat:** Powered by **Gemini 2.5 Flash** tool-calling and **PayPal Sandbox REST APIs** (`@paypal/agent-toolkit` compatible).
- **💳 Generative UI Receipt Cards:** Interactive in-chat PayPal Invoice, Order, and Refund cards with live status badges (`PENDING APPROVAL`, `ESCROW LOCKED`, `PAID`, `REFUNDED`) and instant scannable payment QR codes.
- **🛡️ Human-in-the-Loop (HITL) Guardrails:** Auto-executes low-risk queries and micro-refunds under $25 while requiring explicit 1-tap human approval before capturing funds or issuing high-value refunds.
- **📊 Live Merchant Ledger (AG Grid):** Real-time synchronization between chat actions and an interactive `ag-grid-community` analytics table with KPI tracking.
- **⚡ Dual-Mode Sandbox Engine:** Works out-of-the-box with an **Instant Sandbox Simulation Mode** for zero-friction judging, plus a **Live API Mode** modal to plug in `GEMINI_API_KEY`, `PAYPAL_CLIENT_ID`, and `PAYPAL_CLIENT_SECRET`.

## 🚀 Quick Start (Zero-Build Single File)
1. Clone this repository or open `index.html` directly in any modern desktop or mobile browser.
2. Tap any of the **Quick-Action Starter Chips** in the Agent Chat tab to test autonomous invoicing, checkout staging, and refunds.
3. *(Optional)* Tap the **⚙️ Gear Icon** in the top-right corner to switch from **Instant Sandbox Simulation** to **Live PayPal Sandbox API Mode**.

## 🛠️ Tech Stack
- **Frontend:** React 18, Tailwind CSS, Lucide Icons
- **AI & Payments:** Google Gemini 2.5 Flash API, PayPal Sandbox REST API (`/v1/oauth2/token`, `/v2/checkout/orders`, `/v2/invoicing/invoices`)
- **Data Grid:** AG Grid (`ag-grid-community`)
