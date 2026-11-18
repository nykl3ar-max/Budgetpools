# Budgetpools

**An offline-first monthly budget planner for Android — envelope budgeting done right.**

> No cloud. No registration. No ads. No tracking. 100% local on your device.

---

## Overview

Budgetpools is a personal finance application for Android built around the **envelope budgeting** principle. Instead of tracking spending only after the money is gone, you divide your disposable monthly income (after fixed costs) into dedicated **Budget Pools** — such as Groceries, Transport, Drugstore, Leisure, Clothing, or Savings — and track expenses against each pool in real time.

Every monetary calculation is performed with exact cent precision so there are never rounding errors or unexpected discrepancies.

---

## Key Features

| Feature | Description |
|---|---|
| **Budget Pools** | Custom spending envelopes with monthly limits, icons, and live remaining-balance indicators |
| **Traffic-Light Status** | Clear 4-state visual status (Green, Yellow, Blue, Red) for instant budget awareness |
| **Fixed Costs Tracker** | Manage recurring monthly bills (rent, electricity, internet, transit, subscriptions) with automatic deduction or manual check-off |
| **Custom Financial Month** | Choose any start day from 1 to 28 to match your actual payday cycle |
| **4-Step Setup Wizard** | Guided onboarding with live disposable-income and free-buffer calculation |
| **Envelope Transfers** | Reallocate funds seamlessly between pools and your unallocated free buffer at any time |
| **Cash Wallet** | Dedicated cash balance tracking alongside card/account payments, including ATM withdrawals |
| **Transaction History** | Searchable, filterable ledger grouped by date with full retroactive editing and deletion |
| **Local Backup & Export** | Full JSON backup/restore and UTF-8 CSV export for spreadsheet analysis |
| **Optional App Lock** | Biometric or device-credential protection on launch |

---

## Traffic-Light Rules

Each pool displays an unambiguous status based on its remaining monthly balance:

| Color | Condition | Status Label (DE / EN / PL) |
|---|---|---|
| **Green** (`#2ECC71`) | Remaining > 30% of monthly pool budget | Gut im Plan / On track / W normie |
| **Yellow** (`#F59E0B`) | Remaining > 0.00 and <= 30% of monthly pool budget | Wird knapp / Running low / Konczy sie |
| **Blue** (`#38BDF8`) | Remaining == 0.00 (exact budget reached) | Perfekt aufgegangen / Spot on / Idealnie wyliczone |
| **Red** (`#EF4444`) | Remaining < 0.00 (budget exceeded) | Uberzogen / Over budget / Przekroczono |

A pool with **0.00 remaining** means the planned budget was met to the cent — it is always highlighted in **Blue (Spot on)**, never Red.

---

## Localization

Budgetpools includes complete native translations for three languages:

- **Deutsch** (default on first launch)
- **English**
- **Polski**

You can switch the interface language at any time in **Settings** (or during Step 1 of the Setup Wizard) with immediate live updates — no app restart required. Supported currencies include `EUR`, `PLN`, `USD`, `GBP`, and `CHF`.

---

## Offline Privacy Guarantee

- **100% Local Storage:** All pools, fixed costs, transactions, and preferences stay exclusively on your Android device.
- **Zero Telemetry:** No analytics SDKs, no advertising identifiers, no crash-reporting servers, and no user accounts.
- **Explicit Update Check Only:** Network access is never used in the background. A single request to the GitHub Releases API is made only when you explicitly tap **Check for updates** in Settings.

---

## Download & Installation

Budgetpools is distributed directly via **GitHub Releases** (Android 8.0 / API 26 and newer).

1. Open the [Latest Release](https://github.com/nykl3ar-max/budgetpools/releases/latest) page.
2. Download the signed `Budgetpools-v1.0.0.apk` asset under **Assets**.
3. Open the downloaded `.apk` file on your Android device and confirm installation.
4. For future updates, open **Settings -> About -> Check for updates** inside the app or visit the [Releases](https://github.com/nykl3ar-max/budgetpools/releases) page.

---

## Copyright

Copyright (c) 2026 Budgetpools. All rights reserved. Binary release and documentation repository.
