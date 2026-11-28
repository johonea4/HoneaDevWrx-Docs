# Privacy Policy for LedgerStudio

**Effective Date:** November 27, 2026  
**Publisher:** HoneaDevWrx (Thompson's Station, TN, USA)  
**Support Contact:** `honeadevwrx@outlook.com`  
**Android Package:** `com.honeadevwrx.ledgerstudio`  
**Microsoft Store Identity:** `34743JMHonea.LedgerStudio` (Publisher Display Name: `JMHonea`, Store ID: `9N5J73G62VMV`)

LedgerStudio ("the App") is developed by **HoneaDevWrx** as a 100% offline, local-first business management application for Android and Windows.

## 1. Zero Data Collection & Local SQLite Storage
LedgerStudio **does not collect, transmit, rent, or sell any personal, financial, or usage data**.
- Business profiles, client contacts, quotes, invoices, payment logs, client digital signatures, time entries, expenses, and mileage records reside exclusively in your local device SQLite database (`ledgerstudio_v1.db3`).
- LedgerStudio uses **no backend cloud servers**, **no third-party analytics SDKs**, **no crash telemetry**, and **no advertising trackers**.

## 2. Encrypted Vault Backups (`.lsvault`)
When you export a `.lsvault` backup, the App encrypts your ledger locally using a passphrase you provide (**PBKDF2-SHA256 100,000 iterations + AES-256-GCM**) before handing the file to your device share sheet or file picker. HoneaDevWrx never receives your passphrase or backup data.

## 3. Permissions & Store Purchases
- **Local File Access / Share Sheet:** Used solely when you tap Export PDF, Export CSV, or Backup / Restore `.lsvault`.
- **In-App Purchase (`ledgerstudio_pro_lifetime`):** Handled directly by Google Play Billing or Microsoft Store without external servers, cached locally via an HMAC-SHA256 integrity tag for offline use.

## 4. Data Deletion
Delete all records at any time via **Vault & Tax -> Erase All Local Data**, or by uninstalling the App.

## 5. Children's Privacy & Contact
Intended for adults (18+) and business operators. Questions: `honeadevwrx@outlook.com`.
