# Tabs 🌌 (или Kvit)

A minimalist, serverless, zero-backend Progressive Web App (PWA) designed for splitting daily lunch bills, taxi rides, and evening hangouts with friends or colleagues. 

It requires **no databases, no servers, and no user registration**, making it 100% private, free, and secure.

### ✨ Features
*   **Zero-Backend Architecture:** Everything runs strictly in your browser (`localStorage`). No data ever touches a third-party server.
*   **P2P Encrypted Sync:** Share and merge expenses with friends using encrypted, compressed URL payloads or QR codes (protected via a shared group passcode).
*   **Smart Merge Engine:** Avoids overwriting data; intelligently merges concurrent transaction logs based on unique IDs and timestamps.
*   **Offline-First (PWA):** Install it on your mobile screen. Works flawlessly in dead zones, basements, or without an internet connection.
*   **Premium Dark UI:** Clean, ultra-responsive, mobile-first design built with Tailwind CSS and Alpine.js.

### 🛠️ Tech Stack
*   **Frontend:** Single-file architecture (`index.html`)
*   **Reactivity:** Alpine.js (via CDN)
*   **Styling:** Tailwind CSS (via CDN)
*   **Security:** Web Crypto API (Client-side AES-GCM encryption)
