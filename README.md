# Bitcoin Toolbox — Auto Detection & HD Scanner

A simple **client-side Bitcoin toolbox** for address balance checking and HD wallet scanning.  
Built using JavaScript, `bitcoinjs-lib`, and the [Blockstream API](https://blockstream.info/api/).

---

## 🔍 Features
- Auto-detects address type (Legacy / SegWit / Bech32 / Taproot)
- Supports BIP44 / BIP49 / BIP84 / BIP86 derivation paths
- Displays total received, spent, and unspent (UTXO)
- Fetches all connected transactions directly from the blockchain
- 100% client-side (no data ever leaves your browser)

---

## 🧠 How It Works
This tool derives Bitcoin addresses from a seed phrase or xpub key and queries the blockchain through Blockstream’s public API.  
No private keys are ever uploaded or stored.

---

## 🚀 Usage
1. Open [`index.html`](index.html) in any modern browser.
2. Enter a Bitcoin address, xpub, or seed phrase.
3. Click **“Adressen & Salden abrufen”**.
4. The tool will automatically detect and list all addresses and transactions.

---

## 🧩 Technology Stack
- **bitcoinjs-lib**
- **bip39 / bip32**
- **HTML / CSS / Vanilla JavaScript**
- **Blockstream API** for live blockchain data

---

## ⚠️ Security Notice
Never share your private keys or seed phrases.  
This tool performs all calculations locally, but **always use it offline** or with test data if you are unsure.

---

## 📜 License
Released under the [MIT License](LICENSE).  
© 2025 DGKN — Open-source Bitcoin utilities. Dogenc (DGKN)
