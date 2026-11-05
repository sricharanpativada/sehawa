# Sehawa (सेहावा) 🌾

> **Autonomous Offline-First Agricultural Platform for macOS & Android**  
> Precision soil diagnostics, edge-AI phytopathology, dual-trigger grid predictions, and hyper-local community resilience.

![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Android-emerald?style=for-the-badge)
![Offline](https://img.shields.io/badge/100%25-Offline--First-10B981?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🌟 Overview

**Sehawa** is an autonomous agritech and crop-management companion web application designed for mobile viewports with full responsive desktop compatibility. It executes 100% client-side with zero dynamic API dependencies or external network requirements.

---

## 🚜 Key Features

### 1. Offline Agricultural Core Matrix
- **5 Soil Profiles × 2 Water Tables** (10 total permutations): Alluvial, Black (Regur), Red, Sandy, and Loamy soils mapped against Low (<15m) and High (>35m) water table depths.
- Links optimal crop varieties, expected yield per acre, market demand ratings, recommended 3-step regenerative crop rotations, and boundary re-afforestation agroforestry trees.
- **Home & Rooftop Vegetable Unit**: Calibrated micro-cultivation parameters for Tomatoes, Spinach, Chilies, Coriander, and Bell Peppers with exact drip-emitter flow rates (L/hr) and potting mix ratios.
- **Companion Planting Wisdom**: Field-tested biological synergies (e.g. Marigolds repelling nematodes in Brassicas, Mustard aphid trap lines in Wheat, Basil scent camouflage with Tomatoes).

### 2. Camera-Based Native Leaf Doctor (Phytopathology)
- Mobile camera viewfinder utilizing `navigator.mediaDevices.getUserMedia` with fallback sample leaf presets.
- Client-side HTML5 `<canvas>` color-histogram pixel analysis engine.
- Instant diagnosis of **Healthy Vigorous Foliage**, **Chlorosis (N/Fe/Mg Deficiency)** with organic corrective drenches, or **Necrotic Leaf Spot / Blight** with commercial fungicide protocols.

### 3. Verified Ingredient & Pesticide Guide
- Comprehensive chemical and organic formulation profiles mapped to agricultural pests and diseases.
- Real commercial trade names (*Tatamida*, *Coragen*, *Amistar Top*, *Blitox 50*, *Dithane M-45*, *Contaf Plus*) paired with active market purchase links, application dosages, and Pre-Harvest Intervals (PHI).

### 4. Dual-Trigger Weather Shield & Predictive Grid Outage Planner
- Weather event simulator (*Torrential Monsoon*, *Severe Heatwave*, *Sudden Frost*, *Cyclonic Squall*).
- **Predictive Feeder Logic**: Adverse storm patterns automatically trigger emergency alerts warning farmers of impending rural substation tripping to run irrigation pumps immediately before power lines shut down.
- **Manual Power Cut Scheduler**: Computes crop transpiration deficit and calculates the exact pre-irrigation pump run time in minutes and total water volume needed.

### 5. Dynamic Irrigation Transpiration Timer & Market Rescue System
- Real-time countdown timer that deducts recent rainfall millimeters from baseline crop evapotranspiration needs ($ET_c$) using Web Audio API acoustic feedback.
- **Market Rescue System**: Rapid distress harvest routing directing growers to local cold storage hubs, FPO distress intake depots, and food dehydrator facilities.

### 6. Local Web Speech Regional Voice Engine
- Native HTML5 `window.speechSynthesis` supporting **Hindi** (`hi-IN`), **Telugu** (`te-IN`), **Tamil** (`ta-IN`), and **English** (`en-IN`).
- Integrated speech recognition assistant (`webkitSpeechRecognition`) for spoken agronomic inquiries.

### 7. Local Storage Community Residency Forum
- Fully functional client-side peer-to-peer bulletin board persisted in browser `localStorage`.
- Seeded with listings for **Tractor Rentals**, **Collective Labor Squads**, **Tool Exchanges**, and **Organic Manure Swaps** with full CRUD support.

---

## 🚀 Getting Started

No build step or Node.js environment is required. Simply clone the repository and open `index.html` in any browser:

```bash
# Clone the repository
git clone https://github.com/sricharanpativada/sehawa.git

# Navigate to project folder
cd sehawa

# Open in browser or run a simple local server
python3 -m http.server 8080
```

Open `http://localhost:8080` in Chrome, Safari, Firefox, or Edge.

---

## 🎨 Tech Stack

- **HTML5** & **Vanilla ES6+ JavaScript**
- **Tailwind CSS CDN** (with custom emerald/charcoal/mint/amber dark-mode palette)
- **Lucide Icons**
- **Google Fonts** (*Plus Jakarta Sans* & *Space Grotesk*)
- **HTML5 Canvas** (Procedural botanical seed, sprout & crop simulation)
- **Web APIs**: `getUserMedia`, `speechSynthesis`, `SpeechRecognition`, `AudioContext`, `localStorage`

---

## 📄 License

This project is licensed under the MIT License.
