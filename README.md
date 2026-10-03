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

### [v1.2.0 — Operational Presets & Sentinel Trade Decision Journal (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.2.0)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.2.0-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.2.0/ZentheaQuant-v1.2.0-Windows.zip)** | `.zip` | **Full Package (Recommended):** Standalone executable, documentation, setup guide, and configuration templates |
| **[ZentheaQuant.exe](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.2.0/ZentheaQuant.exe)** | `.exe` | Standalone binary (drop-in update for existing folders) |

---

## 🌟 What's New in v1.2.0

* **1-Click Operational Preset Architecture:**
  * **Weekday Strict Setup (`WEEKDAY_STRICT`):** Institutional strict discipline with active Anti-Chop filter, 0.70 RVOL liquidity hurdle, and a tight $0.54 price collar cap.
  * **Weekend Flow Setup (`WEEKEND_FLOW`):** Adaptive weekend liquidity setup with Anti-Chop relaxed (OFF), 0.60 RVOL hurdle, $0.55 price collar cap, and $0.10 salvage floor for wide-ranging weekend swings.
  * **Dynamic Customization Tracking:** Automatically badges manual slider adjustments as `(Customized)` in real time while preserving 1-click clean reset.
* **Sentinel Trade Decision & Veto Audit Journal:**
  * Real-time auditing of every model prediction, shield veto, and trade execution directly under the Cockpit HUD.
  * Multi-device synchronization to Supabase Cloud `public.quant_decisions`.
* **Local-First & Multi-Device Cloud Sync:**
  * 100% offline isolation for coworkers without Supabase or credentials.
  * Seamless 2-way cloud state persistence for licensed operators.
* **Default Sizing Safety & Grounded Balance:**
  * Kelly sizing OFF by default, 2.0% fixed capital allocation per trade.
  * $40.00 daily drawdown safety circuit breaker.

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
