# Privacy Policy for CraftLedger

**Effective Date:** November 25, 2026  
**Publisher:** HoneaDevWrx (Thompson's Station, TN, USA)  
**Support Contact:** `honeadevwrx@outlook.com`  
**Android Package:** `com.honeadevwrx.craftledger`  
**Microsoft Store Identity:** `34743JMHonea.CraftLedger` (Publisher Display Name: `JMHonea`)

CraftLedger ("the App") is developed by **HoneaDevWrx** as a 100% offline, local-first business management application for Android and Windows.

## 1. Zero Data Collection & Local SQLite Storage
CraftLedger **does not collect, transmit, rent, or sell any personal, financial, or usage data**.
- Business profiles, client contacts, quotes, invoices, payment logs, client digital signatures, time entries, expenses, and mileage records reside exclusively in your local device SQLite database (`craftledger_v1.db3`).
- CraftLedger uses **no backend cloud servers**, **no third-party analytics SDKs**, **no crash telemetry**, and **no advertising trackers**.

## 2. Encrypted Vault Backups (`.clvault`)
When you export a `.clvault` backup, the App encrypts your ledger locally using a passphrase you provide (**PBKDF2-SHA256 100,000 iterations + AES-256-GCM**) before handing the file to your device share sheet or file picker. HoneaDevWrx never receives your passphrase or backup data.

## 3. Permissions & Store Purchases
- **Local File Access / Share Sheet:** Used solely when you tap Export PDF, Export CSV, or Backup / Restore `.clvault`.
- **In-App Purchase (`craftledger_pro_lifetime`):** Handled directly by Google Play Billing or Microsoft Store without external servers, cached locally via an HMAC-SHA256 integrity tag for offline use.

## 4. Data Deletion
Delete all records at any time via **Vault & Tax -> Erase All Local Data**, or by uninstalling the App.

## 5. Children's Privacy & Contact
Intended for adults (18+) and business operators. Questions: `honeadevwrx@outlook.com`.
