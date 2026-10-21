# SafeVaani 🛡️
> **Your always-on, hands-free personal safety companion for women in India.**

SafeVaani is a modern, responsive web application and ecosystem designed to protect women and families through on-device voice detection, ambient SOS triggers, live circle location tracking, and audio escort.

---

## ✨ Key Features

- **Hands-Free Voice SOS**: Voice recognition runs locally on your device. Say emergency trigger words (*"help"*, *"bachao"*, *"madad"*) even with the app closed or screen locked.
- **Safety Circle & Live Tracking**: Share real-time location telemetry with trusted contacts with zero latency.
- **Audio Escort**: Let your circle hear your surroundings in real-time when walking alone at night.
- **On-Device & Private**: Voice telemetry stays strictly on the phone and is never sold or uploaded to cloud storage.
- **Comprehensive Route Matrix**: Over 103 pages, deep-dive guides, safety comparisons (e.g. SafeVaani vs 112 India, bSafe, Himmat), and blog resources.

---

## 🚀 Running Locally

SafeVaani is built with high-performance static architecture and vector graphics. You can run it immediately without complex build chains:

```bash
# Clone the repository
git clone https://github.com/sharsh07-dev/SafeVaani.git
cd SafeVaani

# Start any local static web server (e.g., Python 3)
python3 -m http.server 8088
```

Open [http://localhost:8088](http://localhost:8088) in your browser.

---

## 📁 Project Structure

```
├── index.html                 # Hero, interactive voice demo, pricing, and FAQ
├── _astro/                    # Production JS bundle & stylesheets
├── art/                       # Official SVG vector artwork & illustrations
├── brand/                     # Brand logos and iconography
├── compare/                   # Competitor comparison pages (112 India, bSafe, etc.)
├── features/                  # Detailed feature documentation
├── voice-sos/                 # Voice SOS architecture & mechanics
├── blog/                      # 70+ safety articles, guides & release updates
├── about/                     # About SafeVaani Safety
├── security/                  # Privacy & on-device security guarantees
└── privacy-policy/            # Legal & privacy pledge
```

---

## 📄 License
© SafeVaani Safety. All rights reserved.
