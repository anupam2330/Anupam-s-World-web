# 🌍 Anupam's World - Realtime Chat & Call App
#   https://anupam2330.github.io/Anupam-s-World-web/

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20JS%20%7C%20MQTT-orange)

**Anupam's World** is a lightweight, serverless, and responsive web application designed for real-time communication. It features text messaging, voice notes, image sharing, and peer-to-peer audio calls using WebRTC and MQTT technology. 

No backend setup is required—just open and chat!

---

## ✨ Features

* **💬 Real-time Messaging:** Instant text delivery using the lightweight MQTT protocol.
* **📞 Audio Calling:** Peer-to-peer voice calls using WebRTC (with STUN support).
* **🎙️ Voice Notes:** Record and send voice messages directly from the chat interface.
* **📷 Image Sharing:** Send images with a built-in preview and confirmation modal.
* **🟢 Presence Detection:** See who is online in the room in real-time.
* **💾 Local History:** Chat history is saved locally in your browser (LocalStorage), ensuring privacy.
* **📱 Fully Responsive:** Optimized for both Desktop and Mobile (Android/iOS) devices.
* **🔒 Secure Feel:** Features an "End-to-End Encrypted" UI badge.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Dark Theme), Vanilla JavaScript.
* **Communication Protocol:** [MQTT](https://mqtt.org/) over WebSockets.
* **Signaling & Calls:** WebRTC (RTCPeerConnection).
* **Library Used:** `mqtt.min.js` (for message handling).
* **Broker:** Public EMQX Broker (`wss://broker.emqx.io:8084/mqtt`).

---

## 🚀 How to Run

### Method 1: Local Testing (Text Only)
1.  Download the `index.html` file.
2.  Open it directly in any modern browser (Chrome, Edge, Firefox).
3.  Enter a **Room Name** and your **Display Name**.
4.  Click **"Aaie baat karte hai"** to join.

### Method 2: For Audio Calls (HTTPS Required) ⚠️
To use the **Microphone** for Calls and Voice Notes on mobile devices, the app must be served over **HTTPS**.
1.  Upload the `index.html` file to a free hosting provider like **Netlify**, **Vercel**, or **GitHub Pages**.
2.  Open the provided link (e.g., `https://anupam2330.github.io/Anupam-s-World-web/`).
3.  Share the link with a friend to test the call feature.

---

