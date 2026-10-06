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

### [v1.4.0 — Dual-Alpha & Multi-Asset Concurrency Scale Release (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.4.0)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.4.0-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.4.0/ZentheaQuant-v1.4.0-Windows.zip)** | `.zip` | **Full Package (Recommended):** Standalone executable, documentation, setup guide, and configuration templates |
| **[ZentheaQuant.exe](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.4.0/ZentheaQuant.exe)** | `.exe` | Standalone binary (drop-in update for existing folders with auto-reconciling `.env`) |

---

## 🌟 What's New in v1.4.0

* **Dual-Alpha Execution Model (Mean Reversion + Trend Continuation Confluence):**
  * Scales trading opportunities from 2–3 trades/day up to 15–30 trades/day across BTC, ETH, and SOL.
  * Evaluates multi-timeframe 15m macro bias, 5m Fast EMA9 > EMA21 > EMA50 stack, momentum corridors ($50 \le RSI \le 68$ UP / $32 \le RSI \le 50$ DOWN), and $ADX_{14} \ge 20$.
  * Macro Counter-Trend Veto blocks fading strong 15m institutional trends.
* **Multi-Asset Sentinel Rotator (`ALL` Mode with Concurrency Barrier):**
  * Concurrently monitors and trades BTC, ETH, and SOL.
  * Enforces a hard **`max_concurrent_positions: 2`** barrier, capping maximum open market exposure to $\le \$6.10$ / 2.0% equity at 1.0% stake.
* **Expanded Entry Timing Window (10s – 60s):**
  * Confines entry strictly between seconds 10 and 60, eliminating API latency lockouts.
* **10-Point Pre-Flight Sentinel Arming Checklist Modal:**
  * Cyberpunk terminal checklist modal intercepting Sentinel arming from Standby.
  * Audits in-memory and `.env` guardrail alignment with 1-click **`[⚡ Auto-Upgrade Config (.env)]`** auto-repair.
* **Configuration Reconciler Engine (`EnvMigrator`):**
  * Auto-reconciles missing environment variables on boot without modifying, clobbering, or leaking existing private API credentials.
* **Conservative 1.0% Default Sizing:**
  * Fixed 1.0% default risk allocation (~$3.05 stake / 6 contracts on ~$305 equity) with 1-click UI toggles for 2.0%, 3.0%, etc.

---

## ⚡ Quick Start Guide (New Users)

### Step 1: Download & Extract
1. Download **`ZentheaQuant-v1.2.0-Windows.zip`** from the link above.
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
