<div align="center">

<!-- HERO SVG BANNER -->
<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="heroBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0f1e"/>
      <stop offset="100%" style="stop-color:#0d1b2e"/>
    </linearGradient>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0ea5e9"/>
      <stop offset="50%" style="stop-color:#06b6d4"/>
      <stop offset="100%" style="stop-color:#22c55e"/>
    </linearGradient>
    <linearGradient id="shieldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0ea5e9"/>
      <stop offset="100%" style="stop-color:#06b6d4"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <!-- Background -->
  <rect width="860" height="200" fill="url(#heroBg)" rx="12"/>
  <!-- Grid lines -->
  <g stroke="#ffffff" stroke-opacity="0.03" stroke-width="1">
    <line x1="0" y1="40" x2="860" y2="40"/>
    <line x1="0" y1="80" x2="860" y2="80"/>
    <line x1="0" y1="120" x2="860" y2="120"/>
    <line x1="0" y1="160" x2="860" y2="160"/>
    <line x1="86" y1="0" x2="86" y2="200"/>
    <line x1="172" y1="0" x2="172" y2="200"/>
    <line x1="258" y1="0" x2="258" y2="200"/>
    <line x1="344" y1="0" x2="344" y2="200"/>
    <line x1="430" y1="0" x2="430" y2="200"/>
    <line x1="516" y1="0" x2="516" y2="200"/>
    <line x1="602" y1="0" x2="602" y2="200"/>
    <line x1="688" y1="0" x2="688" y2="200"/>
    <line x1="774" y1="0" x2="774" y2="200"/>
  </g>
  <!-- Glow orbs -->
  <circle cx="120" cy="100" r="70" fill="#0ea5e9" opacity="0.06"/>
  <circle cx="740" cy="100" r="70" fill="#22c55e" opacity="0.05"/>
  <!-- Shield icon -->
  <g transform="translate(60,60)" filter="url(#glow)">
    <path d="M20 4 L36 10 L36 22 C36 30 28 37 20 40 C12 37 4 30 4 22 L4 10 Z" fill="url(#shieldGrad)" opacity="0.9"/>
    <path d="M13 20 L18 25 L27 16" stroke="white" stroke-width="2.5" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
  </g>
  <!-- Title -->
  <text x="118" y="88" font-family="'Segoe UI',system-ui,sans-serif" font-size="36" font-weight="800" letter-spacing="-1" fill="white">Firewall<tspan fill="url(#accentGrad)">Bridge</tspan></text>
  <!-- Subtitle -->
  <text x="120" y="118" font-family="'Segoe UI',system-ui,sans-serif" font-size="14" fill="#94a3b8" letter-spacing="0.3">Universal Firewall Migration Platform · Any Vendor → Any Vendor</text>
  <!-- Accent line -->
  <rect x="120" y="130" width="200" height="2" rx="1" fill="url(#accentGrad)"/>
  <!-- Badges row -->
  <g transform="translate(120,148)">
    <rect width="80" height="20" rx="10" fill="#0ea5e922" stroke="#0ea5e944" stroke-width="1"/>
    <text x="40" y="14" font-family="monospace" font-size="9" fill="#0ea5e9" text-anchor="middle" font-weight="600">AI POWERED</text>
    <rect x="88" width="76" height="20" rx="10" fill="#22c55e22" stroke="#22c55e44" stroke-width="1"/>
    <text x="126" y="14" font-family="monospace" font-size="9" fill="#22c55e" text-anchor="middle" font-weight="600">OPEN SOURCE</text>
    <rect x="172" width="72" height="20" rx="10" fill="#a78bfa22" stroke="#a78bfa44" stroke-width="1"/>
    <text x="208" y="14" font-family="monospace" font-size="9" fill="#a78bfa" text-anchor="middle" font-weight="600">WEB BASED</text>
    <rect x="252" width="80" height="20" rx="10" fill="#f59e0b22" stroke="#f59e0b44" stroke-width="1"/>
    <text x="292" y="14" font-family="monospace" font-size="9" fill="#f59e0b" text-anchor="middle" font-weight="600">8 VENDORS</text>
  </g>
  <!-- Right side - animated dots -->
  <g transform="translate(680,70)">
    <circle cx="0" cy="0" r="4" fill="#0ea5e9" opacity="0.8"/>
    <circle cx="20" cy="10" r="3" fill="#06b6d4" opacity="0.6"/>
    <circle cx="40" cy="0" r="4" fill="#22c55e" opacity="0.8"/>
    <circle cx="60" cy="10" r="3" fill="#0ea5e9" opacity="0.6"/>
    <circle cx="80" cy="0" r="4" fill="#06b6d4" opacity="0.8"/>
    <line x1="4" y1="0" x2="17" y2="9" stroke="#0ea5e9" stroke-width="1" opacity="0.3"/>
    <line x1="23" y1="9" x2="37" y2="1" stroke="#06b6d4" stroke-width="1" opacity="0.3"/>
    <line x1="44" y1="0" x2="57" y2="9" stroke="#22c55e" stroke-width="1" opacity="0.3"/>
    <line x1="63" y1="9" x2="76" y2="1" stroke="#0ea5e9" stroke-width="1" opacity="0.3"/>
  </g>
</svg>

<br/>

[![Python](https://img.shields.io/badge/Python-3.9%20|%203.10%20|%203.11%20|%203.12%20|%203.13-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-Web%20Framework-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![Docker](https://img.shields.io/badge/Docker-Container%20Ready-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/yourname/FirewallBridge?style=flat-square&color=f59e0b)](https://github.com/yourname/FirewallBridge/stargazers)

</div>

---

## What is FirewallBridge?

**FirewallBridge** is a free, open source, web-based firewall configuration migration platform. It helps network engineers migrate firewall policies, objects, NAT rules and routes from one vendor to another — using a simple upload-and-convert workflow. No cloud required, no vendor lock-in, no cost.

---

## Features

<!-- FEATURES SVG -->
<svg width="860" height="120" viewBox="0 0 860 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0f172a"/>
      <stop offset="100%" style="stop-color:#0a0f1e"/>
    </linearGradient>
  </defs>
  <!-- Card 1 -->
  <rect x="0" y="0" width="160" height="110" rx="10" fill="#0f172a" stroke="#0ea5e922" stroke-width="1"/>
  <text x="80" y="35" font-family="sans-serif" font-size="22" text-anchor="middle">🔀</text>
  <text x="80" y="58" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white" text-anchor="middle">Multi-Vendor</text>
  <text x="80" y="74" font-family="'Segoe UI',sans-serif" font-size="9" fill="#64748b" text-anchor="middle">Any → Any support</text>
  <rect x="55" y="88" width="50" height="3" rx="1.5" fill="#0ea5e9" opacity="0.6"/>
  <!-- Card 2 -->
  <rect x="170" y="0" width="160" height="110" rx="10" fill="#0f172a" stroke="#22c55e22" stroke-width="1"/>
  <text x="250" y="35" font-family="sans-serif" font-size="22" text-anchor="middle">🌐</text>
  <text x="250" y="58" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white" text-anchor="middle">Web Interface</text>
  <text x="250" y="74" font-family="'Segoe UI',sans-serif" font-size="9" fill="#64748b" text-anchor="middle">Flask + JavaScript UI</text>
  <rect x="225" y="88" width="50" height="3" rx="1.5" fill="#22c55e" opacity="0.6"/>
  <!-- Card 3 -->
  <rect x="340" y="0" width="160" height="110" rx="10" fill="#0f172a" stroke="#a78bfa22" stroke-width="1"/>
  <text x="420" y="35" font-family="sans-serif" font-size="22" text-anchor="middle">📦</text>
  <text x="420" y="58" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white" text-anchor="middle">Container Ready</text>
  <text x="420" y="74" font-family="'Segoe UI',sans-serif" font-size="9" fill="#64748b" text-anchor="middle">Docker &amp; Podman</text>
  <rect x="395" y="88" width="50" height="3" rx="1.5" fill="#a78bfa" opacity="0.6"/>
  <!-- Card 4 -->
  <rect x="510" y="0" width="160" height="110" rx="10" fill="#0f172a" stroke="#f59e0b22" stroke-width="1"/>
  <text x="590" y="35" font-family="sans-serif" font-size="22" text-anchor="middle">✈️</text>
  <text x="590" y="58" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white" text-anchor="middle">Offline First</text>
  <text x="590" y="74" font-family="'Segoe UI',sans-serif" font-size="9" fill="#64748b" text-anchor="middle">No internet needed</text>
  <rect x="565" y="88" width="50" height="3" rx="1.5" fill="#f59e0b" opacity="0.6"/>
  <!-- Card 5 -->
  <rect x="680" y="0" width="160" height="110" rx="10" fill="#0f172a" stroke="#f43f5e22" stroke-width="1"/>
  <text x="760" y="35" font-family="sans-serif" font-size="22" text-anchor="middle">📋</text>
  <text x="760" y="58" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white" text-anchor="middle">Built-in Logging</text>
  <text x="760" y="74" font-family="'Segoe UI',sans-serif" font-size="9" fill="#64748b" text-anchor="middle">Full audit trail</text>
  <rect x="735" y="88" width="50" height="3" rx="1.5" fill="#f43f5e" opacity="0.6"/>
</svg>

- **Multi-Vendor Support** — Compatible with all major enterprise firewall vendors
- **Web-Based Interface** — Built with Flask and JavaScript for an intuitive browser UI
- **Offline Operation** — Runs fully self-contained, no internet connection required after setup
- **Container-Ready** — Includes Dockerfile and Podman support for fast deployment
- **Built-in Logging** — Comprehensive logging for easy troubleshooting and auditing
- **Python Compatibility** — Fully tested on Python 3.9, 3.10, 3.11, 3.12 and 3.13

---

## Supported Migration Matrix

<!-- MATRIX SVG -->
<svg width="860" height="260" viewBox="0 0 860 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="matBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0f1e"/>
      <stop offset="100%" style="stop-color:#0d1b2e"/>
    </linearGradient>
  </defs>
  <rect width="860" height="260" rx="12" fill="url(#matBg)" stroke="#1e293b" stroke-width="1"/>
  <!-- Title -->
  <text x="30" y="32" font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="white">Migration Support Matrix</text>
  <text x="30" y="50" font-family="monospace" font-size="9" fill="#475569">SOURCE → DESTINATION</text>

  <!-- Column headers -->
  <g font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="#94a3b8" text-anchor="middle">
    <text x="280" y="75">Juniper SRX</text>
    <text x="390" y="75">FortiGate</text>
    <text x="500" y="75">Cisco ASA</text>
    <text x="610" y="75">Check Point</text>
    <text x="720" y="75">Palo Alto</text>
  </g>

  <!-- Row labels -->
  <g font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="#e2e8f0">
    <text x="30" y="113">Juniper SRX</text>
    <text x="30" y="153">FortiGate</text>
    <text x="30" y="193">Cisco ASA</text>
    <text x="30" y="233">Check Point</text>
  </g>
  <!-- Row 5 needs more space -->
  <text x="30" y="248" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="#e2e8f0" dy="-5">Palo Alto</text>

  <!-- Vendor color bars on left -->
  <rect x="0" y="90" width="4" height="30" rx="2" fill="#22c55e"/>
  <rect x="0" y="130" width="4" height="30" rx="2" fill="#ef4444"/>
  <rect x="0" y="170" width="4" height="30" rx="2" fill="#3b82f6"/>
  <rect x="0" y="210" width="4" height="30" rx="2" fill="#e11d48"/>
  <rect x="0" y="232" width="4" height="30" rx="2" fill="#f97316"/>

  <!-- YES cells -->
  <g fill="#22c55e">
    <!-- Juniper row: FG=Yes, ASA=Yes, CP=Yes, PA=Yes -->
    <rect x="355" y="93" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="390" y="108" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="465" y="93" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="500" y="108" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="575" y="93" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="610" y="108" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="685" y="93" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="720" y="108" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <!-- FortiGate row: JN=Yes, ASA=Yes, PA=Yes -->
    <rect x="245" y="133" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="280" y="148" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="465" y="133" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="500" y="148" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="685" y="133" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="720" y="148" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <!-- CheckPoint row: JN=Yes, FG=Yes, ASA=Yes, PA=Yes -->
    <rect x="245" y="213" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="280" y="228" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="355" y="213" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="390" y="228" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="465" y="213" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="500" y="228" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="685" y="213" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="720" y="228" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <!-- PaloAlto row: JN=Yes, FG=Yes, ASA=Yes, CP=Yes -->
    <rect x="245" y="233" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="280" y="248" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="355" y="233" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="390" y="248" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="465" y="233" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="500" y="248" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
    <rect x="575" y="233" width="70" height="22" rx="6" fill="#22c55e18" stroke="#22c55e44" stroke-width="1"/>
    <text x="610" y="248" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#22c55e">✓ Yes</text>
  </g>

  <!-- N/A cells -->
  <g>
    <rect x="245" y="93" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="280" y="108" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
    <rect x="355" y="133" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="390" y="148" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
    <rect x="245" y="173" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="280" y="188" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
    <rect x="575" y="133" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="610" y="148" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
    <rect x="575" y="213" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="610" y="228" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
    <rect x="685" y="233" width="70" height="22" rx="6" fill="#1e293b" stroke="#334155" stroke-width="1"/>
    <text x="720" y="248" font-family="monospace" font-size="10" text-anchor="middle" fill="#475569">— N/A</text>
  </g>

  <!-- NO cells -->
  <g fill="#ef4444">
    <rect x="355" y="173" width="70" height="22" rx="6" fill="#ef444418" stroke="#ef444440" stroke-width="1"/>
    <text x="390" y="188" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#ef4444">✗ No</text>
    <rect x="465" y="173" width="70" height="22" rx="6" fill="#ef444418" stroke="#ef444440" stroke-width="1"/>
    <text x="500" y="188" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#ef4444">✗ No</text>
    <rect x="575" y="173" width="70" height="22" rx="6" fill="#ef444418" stroke="#ef444440" stroke-width="1"/>
    <text x="610" y="188" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#ef4444">✗ No</text>
    <rect x="685" y="173" width="70" height="22" rx="6" fill="#ef444418" stroke="#ef444440" stroke-width="1"/>
    <text x="720" y="188" font-family="monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#ef4444">✗ No</text>
  </g>
</svg>

---

## Quick Start

<!-- SETUP SVG -->
<svg width="860" height="72" viewBox="0 0 860 72" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="72" rx="10" fill="#0a0f1e" stroke="#1e293b" stroke-width="1"/>
  <!-- Step 1 -->
  <circle cx="40" cy="36" r="18" fill="#0ea5e922" stroke="#0ea5e944" stroke-width="1.5"/>
  <text x="40" y="41" font-family="'Segoe UI',sans-serif" font-size="13" font-weight="800" fill="#0ea5e9" text-anchor="middle">1</text>
  <text x="68" y="32" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white">Clone Repo</text>
  <text x="68" y="48" font-family="monospace" font-size="9" fill="#475569">git clone …</text>
  <!-- Arrow -->
  <path d="M180 36 L210 36" stroke="#334155" stroke-width="1.5" stroke-dasharray="3,2"/>
  <polygon points="210,32 218,36 210,40" fill="#334155"/>
  <!-- Step 2 -->
  <circle cx="240" cy="36" r="18" fill="#22c55e22" stroke="#22c55e44" stroke-width="1.5"/>
  <text x="240" y="41" font-family="'Segoe UI',sans-serif" font-size="13" font-weight="800" fill="#22c55e" text-anchor="middle">2</text>
  <text x="268" y="32" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white">Install Deps</text>
  <text x="268" y="48" font-family="monospace" font-size="9" fill="#475569">pip install -r requirements.txt</text>
  <!-- Arrow -->
  <path d="M420 36 L450 36" stroke="#334155" stroke-width="1.5" stroke-dasharray="3,2"/>
  <polygon points="450,32 458,36 450,40" fill="#334155"/>
  <!-- Step 3 -->
  <circle cx="480" cy="36" r="18" fill="#a78bfa22" stroke="#a78bfa44" stroke-width="1.5"/>
  <text x="480" y="41" font-family="'Segoe UI',sans-serif" font-size="13" font-weight="800" fill="#a78bfa" text-anchor="middle">3</text>
  <text x="508" y="32" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white">Run App</text>
  <text x="508" y="48" font-family="monospace" font-size="9" fill="#475569">python app.py</text>
  <!-- Arrow -->
  <path d="M620 36 L650 36" stroke="#334155" stroke-width="1.5" stroke-dasharray="3,2"/>
  <polygon points="650,32 658,36 650,40" fill="#334155"/>
  <!-- Step 4 -->
  <circle cx="680" cy="36" r="18" fill="#f59e0b22" stroke="#f59e0b44" stroke-width="1.5"/>
  <text x="680" y="41" font-family="'Segoe UI',sans-serif" font-size="13" font-weight="800" fill="#f59e0b" text-anchor="middle">4</text>
  <text x="708" y="32" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="white">Open Browser</text>
  <text x="708" y="48" font-family="monospace" font-size="9" fill="#475569">localhost:5000</text>
</svg>

### 🐍 Local (Python)

```sh
# Clone the repository
git clone https://github.com/yourname/FirewallBridge.git
cd FirewallBridge

# Create virtual environment and install dependencies
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# Start the app
python app.py
# Open http://localhost:5000
```

### 🐳 Docker

```sh
docker build -t firewallbridge .
docker run -p 8080:5000 --name=firewallbridge -d \
  -v $(pwd)/logs:/code/logs/ \
  firewallbridge:latest
# Open http://localhost:8080
```

### 🦭 Podman

```sh
podman build -t firewallbridge .
podman run -p 8080:5000 --name=firewallbridge -d \
  -v $(pwd)/logs:/code/logs/ \
  firewallbridge:latest
```

---

## How It Works

<!-- HOW IT WORKS SVG -->
<svg width="860" height="130" viewBox="0 0 860 130" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="flowBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0a0f1e"/>
      <stop offset="100%" style="stop-color:#0d1b2e"/>
    </linearGradient>
    <linearGradient id="arrowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0ea5e9"/>
      <stop offset="100%" style="stop-color:#22c55e"/>
    </linearGradient>
  </defs>
  <rect width="860" height="130" rx="12" fill="url(#flowBg)" stroke="#1e293b" stroke-width="1"/>

  <!-- Step boxes -->
  <!-- Box 1: Upload -->
  <rect x="20" y="30" width="130" height="70" rx="10" fill="#0f172a" stroke="#0ea5e933" stroke-width="1.5"/>
  <text x="85" y="58" font-family="sans-serif" font-size="20" text-anchor="middle">📤</text>
  <text x="85" y="76" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="white" text-anchor="middle">Upload Config</text>
  <text x="85" y="90" font-family="monospace" font-size="8" fill="#475569" text-anchor="middle">.conf / .xml / .txt</text>

  <!-- Arrow 1→2 -->
  <path d="M155 65 L185 65" stroke="url(#arrowGrad)" stroke-width="2"/>
  <polygon points="183,61 191,65 183,69" fill="#0ea5e9"/>

  <!-- Box 2: Parse -->
  <rect x="192" y="30" width="130" height="70" rx="10" fill="#0f172a" stroke="#22c55e33" stroke-width="1.5"/>
  <text x="257" y="58" font-family="sans-serif" font-size="20" text-anchor="middle">🔍</text>
  <text x="257" y="76" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="white" text-anchor="middle">Parse &amp; Extract</text>
  <text x="257" y="90" font-family="monospace" font-size="8" fill="#475569" text-anchor="middle">Objects · Policies · NAT</text>

  <!-- Arrow 2→3 -->
  <path d="M325 65 L355 65" stroke="url(#arrowGrad)" stroke-width="2"/>
  <polygon points="353,61 361,65 353,69" fill="#06b6d4"/>

  <!-- Box 3: Analyze -->
  <rect x="363" y="30" width="130" height="70" rx="10" fill="#0f172a" stroke="#a78bfa33" stroke-width="1.5"/>
  <text x="428" y="58" font-family="sans-serif" font-size="20" text-anchor="middle">🤖</text>
  <text x="428" y="76" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="white" text-anchor="middle">AI Analysis</text>
  <text x="428" y="90" font-family="monospace" font-size="8" fill="#475569" text-anchor="middle">Risk · Warnings · Tips</text>

  <!-- Arrow 3→4 -->
  <path d="M496 65 L526 65" stroke="url(#arrowGrad)" stroke-width="2"/>
  <polygon points="524,61 532,65 524,69" fill="#14b8a6"/>

  <!-- Box 4: Convert -->
  <rect x="534" y="30" width="130" height="70" rx="10" fill="#0f172a" stroke="#f59e0b33" stroke-width="1.5"/>
  <text x="599" y="58" font-family="sans-serif" font-size="20" text-anchor="middle">⚡</text>
  <text x="599" y="76" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="white" text-anchor="middle">Convert</text>
  <text x="599" y="90" font-family="monospace" font-size="8" fill="#475569" text-anchor="middle">Target vendor format</text>

  <!-- Arrow 4→5 -->
  <path d="M667 65 L697 65" stroke="url(#arrowGrad)" stroke-width="2"/>
  <polygon points="695,61 703,65 695,69" fill="#22c55e"/>

  <!-- Box 5: Export -->
  <rect x="705" y="30" width="130" height="70" rx="10" fill="#0f172a" stroke="#22c55e33" stroke-width="1.5"/>
  <text x="770" y="58" font-family="sans-serif" font-size="20" text-anchor="middle">💾</text>
  <text x="770" y="76" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="white" text-anchor="middle">Export &amp; Deploy</text>
  <text x="770" y="90" font-family="monospace" font-size="8" fill="#475569" text-anchor="middle">Download ready config</text>
</svg>

1. **Upload** your source firewall config file (.conf, .xml, .txt, .cfg)
2. **Parse** — FirewallBridge extracts all objects, policies, NAT rules, routes and VPN
3. **Analyze** — AI-powered risk assessment and compatibility report
4. **Convert** — Transforms config into the target vendor's exact syntax
5. **Export** — Download the production-ready config file

---

## Supported Vendors

<!-- VENDORS SVG -->
<svg width="860" height="80" viewBox="0 0 860 80" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="80" rx="10" fill="#0a0f1e" stroke="#1e293b" stroke-width="1"/>
  <!-- FortiGate -->
  <rect x="15" y="15" width="95" height="50" rx="8" fill="#ef444412" stroke="#ef444430" stroke-width="1"/>
  <text x="62" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#ef4444" text-anchor="middle">FG</text>
  <text x="62" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">FortiGate</text>
  <!-- Cisco FTD -->
  <rect x="120" y="15" width="95" height="50" rx="8" fill="#0ea5e912" stroke="#0ea5e930" stroke-width="1"/>
  <text x="167" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#0ea5e9" text-anchor="middle">FT</text>
  <text x="167" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">Cisco FTD</text>
  <!-- Cisco ASA -->
  <rect x="225" y="15" width="95" height="50" rx="8" fill="#3b82f612" stroke="#3b82f630" stroke-width="1"/>
  <text x="272" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#3b82f6" text-anchor="middle">AS</text>
  <text x="272" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">Cisco ASA</text>
  <!-- Palo Alto -->
  <rect x="330" y="15" width="95" height="50" rx="8" fill="#f9731612" stroke="#f9731630" stroke-width="1"/>
  <text x="377" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#f97316" text-anchor="middle">PA</text>
  <text x="377" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">PAN-OS</text>
  <!-- Check Point -->
  <rect x="435" y="15" width="95" height="50" rx="8" fill="#e11d4812" stroke="#e11d4830" stroke-width="1"/>
  <text x="482" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#e11d48" text-anchor="middle">CP</text>
  <text x="482" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">Check Point</text>
  <!-- Juniper -->
  <rect x="540" y="15" width="95" height="50" rx="8" fill="#22c55e12" stroke="#22c55e30" stroke-width="1"/>
  <text x="587" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#22c55e" text-anchor="middle">JN</text>
  <text x="587" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">Juniper SRX</text>
  <!-- Sophos -->
  <rect x="645" y="15" width="95" height="50" rx="8" fill="#2563eb12" stroke="#2563eb30" stroke-width="1"/>
  <text x="692" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#2563eb" text-anchor="middle">SX</text>
  <text x="692" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">Sophos XG</text>
  <!-- pfSense -->
  <rect x="750" y="15" width="95" height="50" rx="8" fill="#94a3b812" stroke="#94a3b830" stroke-width="1"/>
  <text x="797" y="38" font-family="monospace" font-size="11" font-weight="800" fill="#94a3b8" text-anchor="middle">PF</text>
  <text x="797" y="54" font-family="'Segoe UI',sans-serif" font-size="9" fill="#94a3b8" text-anchor="middle">pfSense</text>
</svg>

| Vendor | Product | Config Format | As Source | As Target |
|---|---|---|:---:|:---:|
| Fortinet | FortiGate | `.conf` | ✅ | ✅ |
| Cisco | FTD / FMC | `.txt` | ✅ | ✅ |
| Cisco | ASA | `.cfg` | ✅ | ✅ |
| Palo Alto | PAN-OS | `.xml` | ✅ | ✅ |
| Check Point | R80 / R81 | `.txt` | ✅ | ✅ |
| Juniper | SRX / Junos | `.set` | ✅ | ✅ |
| Sophos | XG | `.xml` | ✅ | ✅ |
| Netgate | pfSense | `.xml` | ✅ | ✅ |

---

## Documentation

Full documentation is available at **[firewallbridge.readthedocs.io](https://firewallbridge.readthedocs.io)**

Topics covered:
- Installation guide (local, Docker, Podman)
- Supported configuration elements per vendor
- Interface and zone mapping guide
- Troubleshooting and log analysis
- Contributing guide

---

## Contributing

Contributions are welcome! Here's how to get started:

```sh
# Fork the repo, then:
git clone https://github.com/YOUR_USERNAME/FirewallBridge.git
cd FirewallBridge
git checkout -b feature/your-feature-name

# Make your changes, then:
git commit -m "feat: add your feature"
git push origin feature/your-feature-name
# Open a Pull Request
```

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

---

## Credits

This project is inspired by and builds upon ideas from:

- [VahidTa/firewall_migration_tool](https://github.com/VahidTa/firewall_migration_tool) — original open source migration tool
- [CheckPointSW/SmartMove](https://github.com/CheckPointSW/SmartMove) — Check Point's open source migration reference

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

<!-- FOOTER SVG -->
<svg width="600" height="50" viewBox="0 0 600 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0ea5e9"/>
      <stop offset="50%" style="stop-color:#06b6d4"/>
      <stop offset="100%" style="stop-color:#22c55e"/>
    </linearGradient>
  </defs>
  <rect x="0" y="22" width="600" height="1" fill="url(#footerGrad)" opacity="0.4"/>
  <text x="300" y="16" font-family="'Segoe UI',sans-serif" font-size="11" fill="#475569" text-anchor="middle">Built with ❤️ for the network security community</text>
  <text x="300" y="40" font-family="monospace" font-size="9" fill="#334155" text-anchor="middle">🛡 FirewallBridge · Any Vendor → Any Vendor · Free &amp; Open Source</text>
</svg>

**⭐ Star this repo if it helped you!**

[Report Bug](https://github.com/yourname/FirewallBridge/issues) · [Request Feature](https://github.com/yourname/FirewallBridge/issues) · [Follow on X](https://x.com/yourhandle)

</div>
