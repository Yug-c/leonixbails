<p align="center">
  <img src="https://a.top4top.io/p_37287xrhs1.jpg" width="250"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Arial&weight=800&size=34&pause=1000&color=00BFFF&center=true&vCenter=true&width=650&lines=Modified+WhatsApp+Baileys" />
</p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029Vb7eLDIGzzKXAALjIO1v">
    <img src="https://img.shields.io/badge/WhatsApp_Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Channel">
  </a>
  <a href="https://t.me/vinzxcommnty">
    <img src="https://img.shields.io/badge/Telegram_Channel-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel">
  </a>
  <a href="https://t.me/yat1mlau">
    <img src="https://img.shields.io/badge/Contact_Developer-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Contact Developer">
  </a>
</p>

---

## 🌟 Overview

WhatsApp Baileys is an open-source library designed to help developers build automation solutions and integrations with WhatsApp efficiently and directly. Using websocket technology without the need for a browser, this library supports a wide range of features such as message management, chat handling, group administration, as well as interactive messages and action buttons for a more dynamic user experience.

Actively developed and maintained, baileys continuously receives updates to enhance stability and performance. One of the main focuses is to improve the pairing and authentication processes to be more stable and secure. Pairing features can be customized with your own codes, making the process more reliable and less prone to interruptions.

This library is highly suitable for building business bots, chat automation systems, customer service solutions, and various other communication automation applications that require high stability and comprehensive features. With a lightweight and modular design, baileys is easy to integrate into different systems and platforms.

---

## 📦 Installation

Add the following dependency to your `package.json`:

```json
"dependencies": {
  "@whiskeysockets/baileys": "github:vinzephyrine/sixbails"
}
```

Then run:

```bash
npm install
```

---

## 🔌 Import

```javascript
const {
  default: makeWASocket,
  // Other Options 
} = require('@whiskeysockets/baileys');
```

---

## 📱 How To Connect To WhatsApp

📷 With QR Code

```javascript
const {
  default: makeWASocket
} = require('@whiskeysockets/baileys');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: true
})
```

🔢 Connect With Phone Pairing Code

```javascript
const {
  default: makeWASocket,
  fetchLatestWAWebVersion
} = require('@whiskeysockets/baileys');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: false,
  version: fetchLatestWAWebVersion()
});

const number = "628XXXXX";
const code = await client.requestPairingCode(number.trim()); // Use: (number, "YYYYYYYY") for custom-pairing

console.log("Your pairing code: " + code);
```

---

## ‼️Why Choose WhatsApp Baileys?

Because this library offers high stability, full features, and an actively improved pairing process. It is ideal for developers aiming to create professional and secure WhatsApp automation solutions. Support for the latest WhatsApp features ensures compatibility with platform updates.

---

### 📌 Technical Notes

- Supports custom pairing codes that are stable and secure
- Fixes previous issues related to pairing and authentication
- Features interactive messages and action buttons for dynamic menu creation
- Automatic and efficient session management for long-term stability
- Compatible with the latest multi-device features from WhatsApp
- Easy to integrate and customize based on your needs
- Perfect for developing bots, customer service automation, and other communication applications
- Has 1 newsletter follow, only the developer's WhatsApp channel: [WhatsApp Channel](https://whatsapp.com/channel/0029Vb7eLDIGzzKXAALjIO1v)

---

For complete documentation, installation guides, and implementation examples, please visit the official repository and community forums. We continually update and improve this library to meet the needs of developers and users of modern WhatsApp automation solutions.

**Thank you for choosing WhatsApp Baileys as your WhatsApp automation solution!**


---

### 📞 Contact Developer

For questions, support, or collaboration, feel free to contact the developer:

- **Telegram**: [Telegram Contact](https://t.me/yat1mlau)
- **Channel**: [Channel Telegram](https://t.me/vinzxcommnty) 

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&color=00BFFF&center=true&vCenter=true&width=500&lines=Thanks+For+Using!+🚀" />
</p>
