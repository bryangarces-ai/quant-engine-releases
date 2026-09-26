# ZENTHEA QUANT RESEARCH LAB 📈
### Production Execution Core // Quantitative Research & Risk Architecture
**Principal:** Puzzled Programmer  
**License:** Commercial Proprietary — Verified via Cloud Licensing System

---

## 🚀 Official Releases & Distribution Packages

Welcome to the official public distribution portal for **Zenthea Quant Engine**. This repository provides signed, standalone Windows binaries and official release archives for licensed users.

> [!NOTE]
> Source code is proprietary and maintained in an isolated private research environment. This repository hosts pre-compiled binaries, changelogs, and update packages only.

---

## 📥 Latest Release

### [v1.0.6 — Supabase Multi-Device Cloud Sync & Dynamic Virtual Capital (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.0.6)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.0.6-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.0.6/ZentheaQuant-v1.0.6-Windows.zip)** | `.zip` | **Full Package (Recommended):** Standalone executable, documentation, setup guide, and configuration templates |

---

## 🌟 What's New in v1.0.6

* **Multi-Device Supabase Cloud Sync:**
  * Real-time 2-way cloud synchronization for trade ledgers and compounded account balances across Desktop, Laptop, and new version releases.
  * Individual tenant isolation by `SUPABASE_USER_ID`: Each coworker runs on their own private database or local storage with zero cross-contamination.
  * Ultra-lean HTTPS REST sync protocol consuming <0.02% of Supabase Free Tier (<$0.00 forever).
* **Dynamic User-Initiated Demo Capital:**
  * Eliminates hardcoded balance constraints. You or any coworker can initiate whatever starting balance fits your test (e.g. `$50.00`, `$100.00`, `$161.00`, or `$500.00`).
  * One-click **"Set Initial Bal"** in the Web Cockpit action dock updates your running capital, local `.env`, and Supabase cloud state simultaneously.
* **Comprehensive Quantitative Research Data Logging (`public.quant_trades`):**
  * Automatically records contract sizing, underlying strike prices, trade durations, and rich JSONB metadata (TypeSafe AI / JEV confidence scores, model rationale, spot price deltas, and wallet equity curves) for continuous machine learning analysis.
* **Paper Trading Balance Reset Safeguard:**
  * Resetting or changing your starting capital **NEVER deletes past trade history**. All historical trades, win/loss stats, and time-series logs in `quant_trades` remain 100% saved.
* **JEV Predictive Smart Salvage Shield:**
  * Autonomous early stop-loss bailout at **`$0.25`** contract floor with **120-second anti-wick time gating**, recovering ~50% of risked capital on breakdowns instead of suffering $0.00 total expirations.
* **Battle-Tested Alpha Execution Core Restored:**
  * Entry collar strictly bounded to **`$0.40 - $0.60`**.
  * Full execution window from **`5s` to `265s`** from round open.
  * Dynamic Early Take-Profit at **`$0.75`** with hybrid orderbook & spot delta valuation.
* **Zero-Knowledge Privacy Architecture:**
  * The developer collects **NO data**. All operations connect directly from the user's computer to their own private Supabase instance. Complete setup instructions included in `CLOUD_SYNC_SETUP_GUIDE.md`.

---

## ⚡ Quick Start Guide (New Users)

### Step 1: Download & Extract
1. Download **`ZentheaQuant-v1.0.6-Windows.zip`** from the link above.
2. Extract the zip file into a folder of your choice (e.g. `C:\Trading\ZentheaQuant\`).

### Step 2: Activate Your License
1. Double-click **`ZentheaQuant.exe`**.
2. When prompted, enter your license key provided by **Puzzled Programmer**:
   ```text
   Format: ZENTHEA-XXXX-XXXX-XXXX-XXXX
   ```
3. The engine activates and securely registers your machine.

### Step 3: Configure Your Exchange Credentials
* Rename `.env.example` to `.env` (or use the in-app setup wizard on first launch).
* Paste your **OKX Demo API Key, Secret Key, and Passphrase** in Section 1.
* Paste your **TypeSafe AI (JEV) API key** in Section 3.
* *(Optional)* Fill in Section 6 for Supabase Cloud Sync (see `CLOUD_SYNC_SETUP_GUIDE.md`).

### Step 4: Launch Web Cockpit
Press **`1`** (or Enter) to launch the browser cockpit:
* Your default browser automatically opens to **`http://127.0.0.1:8888`**.
* Enjoy real-time 5-minute round countdowns, Alpha rankings, Cloud Sync, and autonomous Sentinel trading!

---

## 🔄 How to Update Your Application

When updating to a new version:

1. Close the running `ZentheaQuant.exe` application.
2. Download the latest **`ZentheaQuant-v1.0.6-Windows.zip`**.
3. Drag the new `ZentheaQuant.exe` into your existing folder and choose **Replace**.
4. Double-click `ZentheaQuant.exe`:
   * **Your machine license is permanently preserved.**
   * **Your exchange credentials (.env) are permanently preserved.**
   * **Your trade history and compounded balance are automatically restored!**

---

## 🏛️ Core Architectural Safeguards
1. **Live Capital Protection & Selective Execution:** Strict lockout mechanisms prevent unauthorized real-money execution.
2. **Predictive Risk Shield:** Pre-trade collars, entry timing locks, and dynamic early cash-out triggers.
3. **1.0% Institutional Risk Sizing:** Automated mathematical position sizing capped at 1% portfolio risk.
4. **ISP-Resilient Exchange Connectivity:** Built-in connection layer resilient against local ISP DNS/firewall restrictions.
5. **6-Gate Pre-Flight Strategy Certification:** Profit factor $\ge 1.50$, Max Drawdown $< 10\%$, Sharpe $\ge 0.50$, OOS profitability, Monte Carlo 95th percentile, and 0.00% Probability of Ruin.

---

## 💬 Support & Licensing
To obtain a license key, request a machine binding reset, or report an issue:
* **Contact:** Puzzled Programmer
* **Bug Reports:** Open an issue via the [GitHub Issues](https://github.com/bryangarces-ai/quant-engine-releases/issues) tab in this repository.

---

*© 2026 Puzzled Programmer — ZENTHEA Quant Research Lab. All rights reserved.*
