# A. Praneeth Sai — Personal Portfolio Website 🛡️

A sleek, modern, non-linear developer portfolio and interactive cyber operations studio engineered for **A. Praneeth Sai** (BTech CSE – Cyber Security @ Jaypee University of Information Technology, Solan).

Live Website: **[https://praneethsai050-cmd.github.io](https://praneethsai050-cmd.github.io)**

---

## 🌟 Major Architectural Upgrades

### 1. Non-Linear User Experience (Workspace vs. Continuous Mode)
- **Eliminated Scroll Fatigue:** Instead of forcing visitors into a linear vertical scroll, the site features a **Dynamic Workspace Hub**:
  - `🌟 Overview` — Hero, Verified Identity Card, GitHub Sponsor pill, Mission highlights, and Quick Stats.
  - `🎬 SIH & RIDEHACK Studio` — Direct video controller, dual high-res PPT slide decks, embedded PDF reader, and team roster.
  - `💻 Engineering & Repos` — 100% original project repositories including **Satyameva Aegis**, **GhostChat (E2EE)**, **SecurePassGuard**, and **SchoolSportsHub**.
  - `🛡️ Security Arsenal` — Skills matrix, competitive honors, and the newly added **Interactive Security Lab Workbench**.
  - `⌨️ Cyber Terminal & CTF` — Interactive command-line workspace and **Operation Aegis Shield** 3-tier CTF engine.
  - `📬 Contact & Transmission` — Multi-channel direct dispatch (WhatsApp direct template, LinkedIn, JUIT institutional email).
- **Dual UX View Modes:**
  - **Workspace Mode (Default):** Tab-based focused workspace with custom glowing active tab indicators (`.workspace-tab.tab-active`).
  - **Continuous Mode:** Single-click toggle in the header for traditional continuous vertical scrolling.
- **Floating HUD Dock:** Fixed glassmorphic mini-dock at the bottom center to hop between sections instantly at any scroll point.

---

### 2. 🛡️ Security Arsenal — Interactive Security Lab Workbench
Client-side cryptographic engineering tools running directly in the browser via the native **Web Crypto API**:
- **Live Cryptographic Hash Lab (`#lab-panel-hash`)**:
  - Computes real-time digests using `window.crypto.subtle.digest`.
  - Supports **SHA-256** (NIST FIPS 180-4), **SHA-512**, and **HMAC-SHA256** with customizable secret salt keys.
  - Features real-time benchmark execution timer (sub-millisecond latency), bit-length indicator, and one-click clipboard copy with visual confirmation.
- **Real-Time Password Entropy & Vulnerability Gauge (`#lab-panel-entropy`)**:
  - Computes **Shannon Entropy in bits**: $E = L \times \log_2(R)$ where $R$ dynamically evaluates lowercase, uppercase, numbers, and special symbol character spaces.
  - Offline brute-force resistance time calculated against a simulated $10^{11}$ hashes/sec high-performance GPU cluster.
  - Animated segmented strength meter (Vulnerable &rarr; Moderate &rarr; Very Strong &rarr; Military Grade).
  - Four-part compliance indicator (12+ Chars, Uppercase, Lowercase, Symbols/Digits) and a cryptographically secure random passphrase generator.
- **Cryptographic Standards & Architecture Radar (`#lab-panel-radar`)**:
  - **Satyameva PoW Blockchain Core:** Custom SHA-256 difficulty mining, 0 gas fee ledger, tamper-evident block headers.
  - **OpenCV 128D Face-Lock AI:** Biometric facial coordinate hashing for degree photo tamper detection (Cosine Sim > 0.94).
  - **PBKDF2 100k Iteration Vault:** NIST SP 800-132 key derivation with dynamic salt against rainbow tables.
  - **WebRTC E2EE Direct Mesh (GhostChat):** P2P encrypted signaling without intermediary server logs (DTLS-SRTP 256-bit AES-GCM).

---

### 3. ⌨️ Interactive Cyber Terminal & Mini-CTF Shell ("Operation Aegis Shield")
An authentic Unix-style terminal emulator built with custom shell parsing, sound synthesis, and challenge gamification:
- **CTF Mission Control Bar**:
  - Real-time scoreboard (`0 / 300 PTS`), active stage badges, tactical hint dispatch, and audio synthesizer toggle.
- **3-Tier Progressive CTF Challenges**:
  - **Stage 1 (Crypto Intercept)**: Decrypt adversarial Base64 packet payload (`U0FUX0ZMQUd7Q1lCRVJfQUVHSVNfMjAyNn0=`) using `decode <base64>` and submit flag (`SAT_FLAG{CYBER_AEGIS_2026}`) for +100 PTS.
  - **Stage 2 (Hash Preimage Attack)**: Crack target SHA-256 signature (`ac4139d6...`) using clues and `hash satyameva` / `submit satyameva` for +100 PTS.
  - **Stage 3 (Proof-of-Work Blockchain Mining)**: Execute live browser block mining (`mine 3`) to find the consensus nonce for block `aegis-block-1:<nonce>` with prefix `000` for +100 PTS (300/300 Total).
- **Celebration & Reward**:
  - Multi-tone **Web Audio API** victory fanfare chime.
  - Multi-directional **Canvas Confetti** celebration shower.
  - Unlocks the **"CTF Master Unlocked"** glowing badge on the Cyber ID Card!
- **Interactive Terminal Utilities**:
  - `hash <text>`: Live SHA-256 digest computation.
  - `entropy <pwd>`: Password bits of entropy and crack-time calculus.
  - `decode <b64>` / `encode <text>`: Base64 payload transformation.
  - `mine [diff]`: In-browser asynchronous PoW block miner with live nonces/sec telemetry.
  - `scan`: Simulated vulnerability scan and security header audit for `satyameva-aegis.juit`.
  - `theme [matrix|cyber|amber|synth]`: Dynamic multi-palette terminal color themes.
  - `sound [on|off]`: Synthesizer audio effects switch.
  - `history`: Command navigation with **Arrow Up** and **Arrow Down**.
  - `Tab`: Autocomplete for all available command names.
  - **Quick Action Command Chips**: One-click pills directly above the terminal to execute commands instantly.

---

### 4. 🎬 SIH 2026 & RIDEHACK'26 Presentation Studio
- **Official SIH PPT Integration & Downloads:**
  - Direct download for the official presentation: **`SIH_2026_Satyameva_Idea_Template.pptx` (2.9 MB)**.
  - Direct download/viewing for the official submission document: **`SIH_2026_Satyameva_Idea_Template.pdf` (1.2 MB)**.
  - Direct download for the RIDEHACK Finals presentation: **`RIDEHACK_2026_Satyameva_Aegis.pptx` & `.pdf`**.
- **Dual Visual Slide Deck Viewer (SIH 2026 & RIDEHACK'26):**
  - High-resolution presentation slides rendered directly in-browser.
  - Seamless toggle between **SIH 2026 Submission (6 Slides)** and **RIDEHACK'26 Grand Finals (8 Slides)**.
  - Clickable visual thumbnail ribbon and fullscreen zoom modal with keyboard arrow controls (&larr; / &rarr;).
- **Embedded SIH PDF Reader:** Dedicated studio tab with an interactive inline PDF reader for `SIH_2026_Satyameva_Idea_Template.pdf`.
- **Direct YouTube Video Integration (`https://youtu.be/Uu-bOJTZrFY`):** Embedded responsive 16:9 player with chapter scrubbing buttons (`▶ PPT Pitch Walkthrough`, `▶ Live System Demonstration`).
- **Team CYPHER-X Official Rosters (RIDEHACK'26 & SIH 2026):**
  - **🏆 RIDEHACK'26 Founding Team (Grand Finals @ JIIT Noida • Team ID: 10):**
    - **A. Praneeth Sai** — Founder & Lead Architecture Engineer (B.Tech CSE-CS @ JUIT Solan): 100% Backend services, custom PoW blockchain ledger, Python/Flask microservices, PBKDF2 (100k rounds), OpenCV 128D Face-Lock, and PIL document tamper heatmaps.
    - **Anushka Bansal** — Co-Founder & Data Integrity / Computational Research Lead (B.Tech Bioinformatics @ JUIT Solan).
    - **Shashank Ray** — Co-Founder & AI Model Lead (B.Tech CSE-AI&ML @ JUIT Solan).
    - **Sameeksha Chandel** — Co-Founder & Product / Operations Lead (B.Tech CSE-AI&ML @ JUIT Solan).
  - **🎖️ Smart India Hackathon 2026 Squad (PS: SIH26125 • Team CYPHER-X):**
    - **A. Praneeth Sai** (Team Leader & Core Architect), **Jai Chauhan** (Systems & Network Deployment), **Jyoti Rana** (Regulatory Compliance), **Gauri** (Frontend & UX), **Sparsh** (Verification Protocols), **Akshit Thakur** (QA & Workflow).

---

### 5. 💻 100% Genuine Project Showcase
- **Satyameva Aegis (Flagship):** Decentralized academic credential issuance platform featuring PoW blockchain ledger, Gemini AI OCR, Face-Lock AI, and instant QR verification.
- **GhostChat (Live on Render):** Ephemeral peer-to-peer encrypted chat utilizing WebRTC data channels with DTLS-SRTP 256-bit AES-GCM encryption and zero server-side message logging.
- **SecurePassGuard:** Real-time client-side password entropy & vulnerability analyzer with zero tracking.
- **SchoolSportsHub:** Inter-school athletic tournament scheduling, roster coordination, and results platform.

---

## 🚀 How to Run & Preview Locally

### Option 1: Direct Browser Launch
Simply double-click `index.html` or run in PowerShell:
```powershell
Start-Process "C:\Users\hp\.gemini\antigravity\scratch\portfolio\index.html"
```

### Option 2: Local HTTP Server (Python)
```powershell
cd C:\Users\hp\.gemini\antigravity\scratch\portfolio
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

---

## 🌐 Live Deployment
The portfolio is deployed directly to **GitHub Pages**:
- **Repository:** `https://github.com/praneethsai050-cmd/praneethsai050-cmd.github.io`
- **Live URL:** [https://praneethsai050-cmd.github.io](https://praneethsai050-cmd.github.io)
