# A. Praneeth Sai — Personal Portfolio Website 🛡️

A sleek, modern, non-linear developer portfolio and hackathon studio engineered for **A. Praneeth Sai** (BTech CSE – Cyber Security @ Jaypee University of Information Technology, Solan).

## 🌟 Major Architectural Upgrades

### 1. Non-Linear User Experience (Workspace vs. Continuous Mode)
- **Eliminated Scroll Fatigue:** Instead of forcing visitors into a single 5,000px vertical scroll where every point is stacked linearly, the site features a **Dynamic Workspace Hub**:
  - `🌟 Overview` — Hero, Identity badge, Mission, and Quick Stats.
  - `🎬 SIH & RIDEHACK Studio` — Direct video controller, interactive slide deck, and team roster.
  - `💻 Engineering & Repos` — 100% original project repositories.
  - `🛡️ Security Arsenal` — Technical skills, Linux internals, penetration testing stack, and 3 honors cards.
  - `⌨️ Cyber Terminal` — Interactive command-line environment (`sih`, `ridehack`, `projects`, `skills`, `team`).
  - `📬 Contact` — Secure communication dispatch.
- **Dual UX View Modes:**
  - **Workspace Mode (Default):** Smooth tab-based switching that presents one focused workspace at a time with smooth entry transitions.
  - **Continuous Mode:** One-click toggle in the header for visitors who prefer classic continuous page scrolling.
- **Floating HUD Dock:** Fixed glassmorphic mini-dock at the bottom center to hop between sections instantly at any scroll point.

### 2. SIH 2026 & RIDEHACK'26 Presentation & Demonstration Studio
- **Official SIH PPT Integration & Downloads:**
  - Direct download for the official presentation: **`SIH_2026_Satyameva_Idea_Template.pptx` (2.9 MB)**.
  - Direct download/viewing for the official submission document: **`SIH_2026_Satyameva_Idea_Template.pdf` (1.2 MB)**.
  - Direct download for the RIDEHACK Finals presentation: **`RIDEHACK_2026_Satyameva_Aegis.pptx` & `.pdf`**.
- **Dual Visual Slide Deck Viewer (SIH 2026 & RIDEHACK'26):**
  - Renders the **ACTUAL high-resolution presentation slides** (extracted directly from your official submission at 3000x1688 resolution).
  - Deck toggle button to switch seamlessly between **SIH 2026 Submission (6 Slides)** and **RIDEHACK'26 Grand Finals (8 Slides)**.
  - Clickable visual thumbnail ribbon at the bottom of the viewer for instant slide hopping.
  - Fullscreen Zoom Modal (`openSlideModal()`) with keyboard arrow controls (&larr; / &rarr;) to inspect slide diagrams in full detail.
- **Embedded SIH PDF Reader:**
  - Dedicated studio tab with an interactive inline PDF reader for `SIH_2026_Satyameva_Idea_Template.pdf` allowing evaluators and recruiters to read the submission directly in-browser.
- **Direct YouTube Video Integration (`https://youtu.be/Uu-bOJTZrFY`):**
  - Embedded responsive 16:9 player with chapter scrubbing buttons (`▶ PPT Pitch Walkthrough`, `▶ Live System Demonstration`).
- **Team CYPHER-X Official Rosters (RIDEHACK'26 & SIH 2026):**
  - **🏆 RIDEHACK'26 Founding Team (Grand Finals @ JIIT Noida • Team ID: 10):**
    - **A. Praneeth Sai** — Founder & Sole Backend / Protocol Architect (B.Tech CSE-CS @ JUIT Solan): 100% Backend services, custom PoW blockchain ledger (zero gas fees), Python/Flask microservices, PBKDF2 (100k rounds), OpenCV 128D Face-Lock, and PIL document tamper heatmaps.
    - **Anushka Bansal** — Co-Founder & Data Integrity / Computational Research Lead (B.Tech Bioinformatics @ JUIT Solan): Data integrity heuristics, mathematical data structures, tamper-detection benchmarks, and research dataset validation.
    - **Shashank Ray** — Co-Founder & AI Model Lead (B.Tech CSE-AI&ML @ JUIT Solan): Google Gemini 2.0 Flash prompt pipelines for automated OCR extraction, multi-campus node scalability, and B2B university SaaS model (₹1.5L/campus annual SaaS + ₹25 API calls).
    - **Sameeksha Chandel** — Co-Founder & Product / Operations Lead (B.Tech CSE-AI&ML @ JUIT Solan): Product lifecycle, campus operational rollout workflows, student self-sovereign wallet experience, NEP 2020 regulatory compliance, and incubation pitch structuring.
    - Status: TRL 6 Prototype tested across Jaypee nodes; targeting ₹1 Cr incubation fund.
  - **🎖️ Smart India Hackathon 2026 Squad (PS: SIH26125 • Team CYPHER-X):**
    - **A. Praneeth Sai** — Team Leader & Sole Backend / Core Architect (B.Tech CSE-CS @ JUIT Solan): 100% Backend architecture & database schemas, custom PoW blockchain engine, Node.js + Web3.js asynchronous pipelines, SQLite/SQLAlchemy ORM, PBKDF2 salting, Polygon smart contracts (~₹0.08 minting), and multi-sig (2-of-3) key compromise safeguards.
    - **Jai Chauhan** — Systems & Network Deployment Lead (B.Tech CSE-CS @ JUIT Solan): Campus server infrastructure, local intranet node deployment, IPFS distributed pin routing for AES-256 encrypted payloads, and real-time socket listeners.
    - **Jyoti Rana** — Regulatory Compliance & Research Lead (B.Tech CSE @ JUIT Solan): UGC Fake Degree regulatory epidemiology reports, NIST FIPS 180-4 and RFC 2104 benchmarks, and institutional registrar audit trail workflows.
    - **Gauri** — Frontend & UX Architecture Lead (B.Tech Biotechnology @ JUIT Solan): Student Digital Wallet interface, dynamic 60s QR code rendering, and responsive mobile verification UX.
    - **Sparsh** — Verification Protocols & Data Specs Lead (B.Tech CSE @ JUIT Solan): Verification data structures, marksheet attribute mapping, JSON-LD / Blockcerts schema compatibility, and certificate signing format requirements.
    - **Akshit Thakur** — QA & Presentation Workflow Lead (B.Tech CSE-AI&DS @ JUIT Solan): 10,000+ record stress testing, sub-3 second latency validation, edge-case invalidations, and pitch demonstration workflow.

### 3. 100% Genuine Project Showcase
- **Satyameva Aegis (Flagship):** Spanning hero project card with direct link to launch the presentation studio or inspect code on GitHub, featuring real metrics: 92% speedup, Face-Lock AI, Tamper Heatmap, PBKDF2 100K iterations.
- **SecurePassGuard:** Real-time client-side password entropy calculator with zero server logging.
- **SchoolSportsHub:** Inter-school athletic match scheduling & roster tracking platform.

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

## 🌐 How to Deploy Live for Free (GitHub Pages)

Host this live at **`https://praneethsai050-cmd.github.io`** in 3 steps:

1. Create a public repository on GitHub named **`praneethsai050-cmd.github.io`**.
2. Push your portfolio files:
   ```bash
   cd C:\Users\hp\.gemini\antigravity\scratch\portfolio
   git init
   git add .
   git commit -m "feat: non-linear portfolio with SIH PPT and demo studio"
   git branch -M main
   git remote add origin https://github.com/praneethsai050-cmd/praneethsai050-cmd.github.io.git
   git push -u origin main
   ```
3. Within 1 minute, your portfolio will be live at `https://praneethsai050-cmd.github.io`!
