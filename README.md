# WHAT YOUR BROWSER SAYS ABOUT YOU // Flip the Script

> **A 100% client-side privacy scanner and live OpenRTB 2.6 auction inspector.**  
> *Expose the hidden hardware signals your browser reveals in under 0.2 seconds—and see how ad networks value your attention.*

---

## ⚡ Overview

Every time you load a webpage, your browser silently broadcasts diagnostic clues about your device: screen dimensions, graphics card fingerprints, home timezone offsets, battery levels, and hardware cores. Data brokers and ad networks aggregate these signals into master identity graphs behind closed doors.

**Flip the Script** turns the ad industry's financial engine into the exhibit itself. It runs an immediate, zero-network-request forensic audit of your local browser, letting you inspect the exact OpenRTB 2.6 code packets ad buyers use to bid on your screen.

---

## 🚀 Key Features

* **Dual-Mode Auction Engine:**
  * **100% Local Simulation (Default):** Runs entirely offline inside your browser with `0 Outside Connections`. Zero server logs, zero third-party tracking, zero cookies.
  * **Opt-In Live Network Auction:** Pings live ad-exchange endpoints in real time so you can watch ad buyers bid on your screen (**Free for You // Paid by Them**).
* **OpenRTB 2.6 Packet Inspector:**
  * View raw bid requests and responses generated dynamically from your device hardware.
  * Instant **Plain English Decoder** toggle translating complex JSON fields (`canvas_hash`, `hardwareConcurrency`, `gpc`) into simple explanations.
* **Data Broker Orientation & Severity Matrix:**
  * Plain-language breakdowns of commercial broker tracking practices (Mobilewalla, Gravy Analytics, Kochava, Babel Street).
  * Color-coded severity ratings derived from FTC orders, Senate Committee investigations, and DHS Inspector General audits (`DHS OIG-23-61`).
* **`.GOV` & `.US` Legal Proof Room:**
  * Direct citations to official government dockets and congressional reports with one-click copyable case IDs.
* **Interactive Action Kit & Automated Letter Builder:**
  * One-click generation of pre-formatted legal demand letters for state representatives and data privacy requests under CCPA/CPRA.
* **`800×1050` Redacted PNG Receipt Generator:**
  * Exports a client-side graphic summary of your device clues with custom redaction stamps to share on social media or send to elected officials.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** Plain HTML5, CSS3 (Tailwind CSS CDN), Vanilla JavaScript ES6+.
* **Dependencies:** None. Fully self-contained single-file architecture (`index.html`).
* **Canvas Processing:** HTML5 Canvas API for real-time graphics fingerprinting and client-side PNG receipt rendering.
* **Deployment:** Designed for 100% free hosting on GitHub Pages, Cloudflare Pages, or Vercel.

---

## 📦 Quick Start (Local Development)

Because the project is built as a zero-dependency static application, no Node.js or build tools are required:

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/browser-clues.git](https://github.com/YOUR-USERNAME/browser-clues.git)
