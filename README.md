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

### [v1.5.0 — Asymmetric Value Collar & Pure Option A Hold Overhaul Release (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.5.0)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.5.0-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.5.0/ZentheaQuant-v1.5.0-Windows.zip)** | `.zip` | **Full Package (Recommended):** Standalone executable, documentation, setup guide, and configuration templates |
| **[ZentheaQuant.exe](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.5.0/ZentheaQuant.exe)** | `.exe` | Standalone binary (drop-in update for existing folders with auto-reconciling `.env`) |

---

## 🌟 What's New in v1.5.0

* **Asymmetric Value Collar ($0.35–$0.45) (`core/exchange.py`, `core/prediction_engine.py`):**
  * Strictly gates binary event contract acquisitions between **$0.35 and $0.45**.
  * Rejects expensive contracts ($> \$0.45$) that created negative risk-reward traps in historical trading.
  * Mathematically guarantees positive Risk-to-Reward Ratio ($\ge 1.22:1$ to $1.85:1$), dropping breakeven win rate to $\le 45\%$.
* **Pure Option A Hold to Expiration (Zero Panic Selling):**
  * Completely bypassed and disabled `Smart Salvage` ($0.25 bailouts) and `Wick Defense` ($0.001 dumpings).
  * In-flight positions are held to full 300-second expiration, allowing winning strikes to settle for the full $1.00 (+100%) payout without being shaken out by mid-candle wick noise.
  * Early Take-Profit disabled to capture maximum expiration edge.
* **Pre-Flight JEV AI Conviction & 60%–80% Token Reduction:**
  * Retained JEV System One neural model for pre-flight evaluation and conviction scoring ($\ge 65\%$).
  * Powers the 3D Holographic WebGL Neural Orb and live Thought Trace stream on the Web Cockpit (`http://localhost:8888`).
  * Completely purged in-flight polling calls (`evaluate_early_cashout` and `evaluate_salvage_bailout`), cutting API token consumption by **60%–80%**.
* **Automated 1-Click .env Configuration Migration on Arming:**
  * Clicking **"ARM"** or opening the Pre-Flight Checklist automatically reconciles and upgrades legacy configuration parameters to `v1.5.0` optimal values (`PRICE_COLLAR_MIN=0.35`, `PRICE_COLLAR_MAX=0.45`, `ENTRY_WINDOW_START_SEC=15`, `ENTRY_WINDOW_END_SEC=45`, `DAILY_DRAWDOWN_LIMIT=25.0`).
  * Strictly preserves all private user credentials (`OKX_API_KEY`, `TYPESAFE_API_KEY`, `TELEGRAM_BOT_TOKEN`, `SUPABASE_KEY`) with automatic `.bak` backups.
* **Risk Hardening:**
  * Fixed lot sizing of 6 contracts (~$2.10–$2.70 risk per trade; ~0.7%–0.9% of capital).
  * Daily drawdown circuit breaker calibrated to `$25.00 USDT`.
  * Execution capture sweet-spot: **15s–45s**.

---

## ⚡ Quick Start Guide (New Users)

### Step 1: Download & Extract
1. Download **`ZentheaQuant-v1.5.0-Windows.zip`** from the link above.
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
2. Download the latest **`ZentheaQuant-v1.5.0-Windows.zip`**.
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
* Contact **Puzzled Programmer** via official private support channels.
