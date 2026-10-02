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

### [v1.1.5 — Calibrated Smart Salvage Stop-Loss & Automatic .env Migration (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.1.5)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.1.5-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.1.5/ZentheaQuant-v1.1.5-Windows.zip)** | `.zip` | **Full Package (Recommended):** Standalone executable, documentation, setup guide, and configuration templates |
| **[ZentheaQuant.exe](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.1.5/ZentheaQuant.exe)** | `.exe` | Standalone binary (drop-in update for existing folders) |

---

## 🌟 What's New in v1.1.5

* **Calibrated Smart Salvage Stop-Loss (Cutting Losses by ~50%):**
  * **Real Volatility Calibration:** Statistically grounded against 1,000 real 5m OKX candles (median body move 0.061%).
  * **Configurable Adverse Delta Threshold (`SALVAGE_ADVERSE_DELTA_PCT=0.12`):** Triggers stop-loss bailout once spot moves $\ge 0.12\%$ against entry, eliminating $0.00 zero-value expirations.
  * **Dynamic Binary Multiplier (`SALVAGE_CONTRACT_MULTIPLIER=1.80`):** Replaced the unresponsive 0.45 multiplier to accurately reflect binary contract probability decay.
  * **Observation Buffer (`SALVAGE_WINDOW_START_SEC=90`):** Gives the position 90 seconds to breathe past opening noise before strictly defending capital.
* **Automatic `.env` Migration Architecture:**
  * When running `ZentheaQuant.exe`, the engine automatically detects missing shield settings in your existing desktop `.env` and safely appends them with optimal defaults without touching or overwriting your API keys.
* **15-Minute Macro Confluence & 5s Adaptive Cache:**
  * Carries over the verified 15-minute multi-timeframe horizon and 5-second opening cache refresh for high-resolution strike accuracy.

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
