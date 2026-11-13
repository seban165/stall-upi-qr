# Stall UPI QR POS 📱🇮🇳

A fast, lightweight, offline-ready Point of Sale (POS) web app to generate custom UPI / Google Pay QR codes with pre-filled amounts for stall businesses, pop-up events, and counters.

Works seamlessly with **Google Pay**, **PhonePe**, **Paytm**, and **BHIM UPI**.

![UPI POS](https://img.shields.io/badge/UPI-Instant%20QR-brightgreen)
![No Backend](https://img.shields.io/badge/Backend-Zero%20Dependency-blue)
![Offline Ready](https://img.shields.io/badge/Offline-100%25%20Ready-orange)

---

## ✨ Features

- **⚡ Instant Pre-Filled Amount:** As you type the price on the numpad, the QR code updates in real-time. When scanned, the customer's Google Pay / PhonePe opens with the exact amount already typed in.
- **🖥️ Customer View (Fullscreen):** Large, high-contrast modal displaying your stall name, the total amount to pay, and a crisp QR code easily readable from across the counter.
- **🏷️ Quick Preset Chips:** One-tap `+₹10`, `+₹20`, `+₹50`, `+₹100` buttons for rapid cashier entry.
- **🍔 Customizable Quick Menu:** Add custom menu buttons (e.g. `Lemonade:30, Burger:80`) so you don't even have to type numbers during rush hours.
- **📊 Daily Sales Tracker:** Press **"✓ Mark Paid & Clear"** after each order to tally your day's total revenue and order count.
- **🖨️ Printable Table Standees:** Need physical QR cards on your stall counter? Switch to the **Print Standees** tab to generate a printable A4 sheet of QR codes for preset amounts (e.g., ₹20, ₹50, ₹100, Any Amount).
- **📴 100% Offline Capability:** Everything runs client-side in the browser using the bundled `qrcode.min.js`.

---

## 🌐 Live Web App

Use the live app directly in any browser (phone, tablet, laptop):  
👉 **[https://seban165.github.io/stall-upi-qr/](https://seban165.github.io/stall-upi-qr/)**

*(You can tap "Add to Home Screen" on your mobile browser to install it like a native app at your stall!)*

---

## 🛠️ Configuration

1. **Enter Your UPI ID:** At the top of the app, enter your Google Pay / PhonePe / BHIM UPI ID (e.g. `yourname@oksbi` or `yourname@okhdfcbank`).
2. **Enter Stall Name:** Enter your shop or stall name (e.g. `My Stall`).
3. Your settings are automatically saved to your browser's local storage.

---

## 🔒 Privacy & Security

- **Direct Bank Settlement:** Payments go directly from the customer's bank account to your linked bank account via standard NPCI UPI rails.
- **No Middleman / 0% Fees:** No payment gateway KYC, no transaction fees, and no external servers storing your data.

---

## 📄 License

MIT License. Free to use for personal, stall, and commercial pop-ups!
