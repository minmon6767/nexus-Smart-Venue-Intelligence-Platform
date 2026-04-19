# NEXUS — Smart Venue Intelligence Platform

> **PromptWars Virtual Edition Challenge Submission**
> _Design a solution that improves the physical event experience for attendees at large-scale sporting venues._

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Google%20Cloud-blue?style=for-the-badge&logo=vercel)](https://nexus-smart-venue-intelligence-plat.vercel.app/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge)]()

---

## 🏟 Problem Statement

Large-scale sporting venues (50,000–100,000 capacity) face critical operational challenges:

- **Crowd crushing** due to uneven flow and poor visibility into congestion zones
- **Excessive wait times** at entry gates, concessions, and facilities
- **Slow incident response** caused by lack of real-time situational awareness
- **Poor fan experience** — attendees have no live guidance on queues or navigation

---

## 💡 Solution: NEXUS

NEXUS is a **dual-interface real-time venue intelligence system** with:

| Interface | Users | Purpose |
|---|---|---|
| **Operations Dashboard** | Venue staff, supervisors | Full situational awareness, alerts, staff coordination |
| **Fan Mobile App** | Attendees | Navigation, live queue times, personalized alerts |

---

## ✨ Key Features

### 🗺 Operations Center Dashboard
- **Live Crowd Density Heatmap** — Canvas-rendered stadium map with real-time zone density coloring (green/amber/red)
- **Gate Queue Management** — Per-gate wait times with surge detection and auto-alerts
- **Bottleneck AI Analysis** — Automated detection of crowd crush risk zones with mitigation recommendations
- **Incident Coordination** — Dispatch log, staff deployment map, emergency protocol status
- **ML Wait Prediction** — 30-minute forward forecast for all queues including halftime surge prediction
- **Radio/Comms Channels** — Live staff communication log across 5 operational channels

### 📱 Fan-Facing Mobile Experience
- **Smart Indoor Navigation** — Turn-by-turn directions to seat, restrooms, concessions
- **Live Queue Intelligence** — Real-time wait times across all facilities
- **Proactive Crowd Alerts** — Auto-warns fans of congested routes with alternatives
- **Seat Delivery Ordering** — Food/drink delivered to seat number
- **Post-Match Exit Routing** — Smart exit guidance to minimize congestion

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML5, CSS3, Canvas API |
| Fonts | Space Grotesk + JetBrains Mono |
| Deployment | Google Cloud Run (Docker/nginx) |
| Data | Simulated real-time sensor data with live jitter |
| Maps | HTML5 Canvas stadium heatmap renderer |

---

## 🚀 Deployment on Vercel

### Quick Deploy

```bash

```

### One-Command Deploy (using Cloud Build)
```bash
```

---

## 📁 Project Structure

```
```

---

## 🎯 How It Addresses the Challenge

| Challenge | NEXUS Solution |
|---|---|
| Crowd movement | Real-time heatmap + AI bottleneck detection + crowd velocity tracking |
| Waiting times | Live queue sensors across all gates/concessions + ML prediction engine |
| Real-time coordination | Dispatch log, radio channels, automated alert routing to supervisors |
| Seamless fan experience | Mobile app with navigation, proactive alerts, seat ordering |
| Emergency situations | Protocol status board + crush-risk threshold triggers + medical dispatch |

---

## 📸 Screenshots

> Dashboard · Crowd Flow · Queue Times · Staff Coordination · Fan App

---

## 🏆 Built For

**PromptWars Virtual Edition** — Challenge: Smart Sporting Venue Experience  
Built with ❤️ using AI-assisted development

---

## 📄 License

MIT License — free to use, modify, and deploy.
