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

### [v1.0.2 — Predictive Event Market Shield & Execution Controls (Windows x64)](https://github.com/bryangarces-ai/quant-engine-releases/releases/tag/v1.0.2)

| Package | Format | Description |
| :--- | :--- | :--- |
| **[ZentheaQuant-v1.0.2-Windows.zip](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.0.2/ZentheaQuant-v1.0.2-Windows.zip)** | .zip | **Full Package:** Standalone executable, documentation, and configuration templates |
| **[ZentheaQuant.exe](https://github.com/bryangarces-ai/quant-engine-releases/releases/download/v1.0.2/ZentheaQuant.exe)** | .exe | **Standalone Binary:** Quick drop-in executable for existing users |

---

## 🌟 What's New in v1.0.2

* **Predictive Risk Guardrails:** Realigned entry price collar to $0.35 - .52 to guarantee a favorable risk-to-reward ratio.
* **Strict Entry Window:** Enforces 15s - 90s trade entry cutoff from round open to eliminate late-round volatility chop.
* **Early Take-Profit Cash-Out:** Raised target to $0.85 and integrated live OKX orderbook bid queries for instant exit before expiration.
* **Dynamic Zero-Rebuild Configuration:** Adjust risk parameters directly via the Web Cockpit or .env without recompiling.
* **Parameter Change Audit Trail:** Live persistent audit logging tracking parameter revisions and operator rationale.
* **Non-Destructive .env Auto-Migration:** Automatically discovers and appends missing risk controls without overwriting personal API keys.

---

## ⚡ Quick Start Guide (New Users)

### Step 1: Download & Extract
1. Download **ZentheaQuant-v1.0.2-Windows.zip** from the link above.
2. Extract the zip file into a folder of your choice (e.g. C:\Trading\ZentheaQuant\).

### Step 2: Activate Your License
1. Double-click **ZentheaQuant.exe**.
2. When prompted, enter your license key provided by **Puzzled Programmer**:
   `	ext
   Format: ZENTHEA-XXXX-XXXX-XXXX-XXXX
   `
3. The engine activates and securely registers your machine.

### Step 3: Configure Your Exchange Credentials
On first run, the built-in wizard prompts you to configure your API keys:
* **Option A (Guided Wizard):** Press Y and paste your OKX API Key, Secret, Passphrase, and JEV API key.
* **Option B (Manual):** Rename .env.example to .env and fill in your keys.

### Step 4: Launch Web Cockpit
Press **1** (or Enter) to launch the browser cockpit:
* Your default browser automatically opens to **http://127.0.0.1:8888**.
* Enjoy live charts, risk monitoring, strategy execution, and backtesting!

---

## 🔄 How to Update Your Application

When an update is released, an in-app notice appears automatically on launch:

1. Close the running ZentheaQuant application.
2. Download the latest ZentheaQuant-v1.0.2-Windows.zip or ZentheaQuant.exe.
3. Drag the new ZentheaQuant.exe into your existing folder and choose **Replace**.
4. Double-click ZentheaQuant.exe — **all your API keys (.env) and machine license are 100% preserved!**

---

## 🏛️ Core Architectural Safeguards
1. ** Live Capital Protection & Selective Execution:** Strict lockout mechanisms prevent unauthorized real-money execution.
2. **Predictive Risk Shield:** Pre-trade collars, entry timing locks, and dynamic early cash-out triggers.
3. **1.0% Institutional Risk Sizing:** Automated mathematical position sizing capped at 1% portfolio risk.
4. **ISP-Resilient Exchange Connectivity:** Built-in connection layer resilient against local ISP DNS/firewall restrictions.
5. **6-Gate Pre-Flight Strategy Certification:** Profit factor $\\ge 1.50$, Max Drawdown $< 10\%$, Sharpe $\\ge 0.50$, OOS profitability, Monte Carlo 95th percentile, and 0.00% Probability of Ruin.

---

## 💬 Support & Licensing
To obtain a license key, request a machine binding reset, or report an issue:
* **Contact:** Puzzled Programmer
* **Bug Reports:** Open an issue via the [GitHub Issues](https://github.com/bryangarces-ai/quant-engine-releases/issues) tab in this repository.

---

*© 2026 Puzzled Programmer — ZENTHEA Quant Research Lab. All rights reserved.*
