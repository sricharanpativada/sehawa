# ｓｅｈａｗａ (సెహావా / सेहावा) 🌾

> **Autonomous Offline-First Agricultural Platform & AgriBot Botanical Vision Expert for macOS & Android**  
> Terrace 3D growth simulation, hierarchical visual botanical triage, IPM protocols, and hyper-local community resilience.

![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Android-emerald?style=for-the-badge)
![Offline](https://img.shields.io/badge/100%25-Offline--First-10B981?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🌟 Overview

**ｓｅｈａｗａ** is an autonomous agritech companion web application designed aggressively for mobile viewports with full responsive desktop compatibility. It executes 100% client-side with zero dynamic API dependencies or external cloud requirements.

The landing page features a photorealistic terraced mountain crop field background overlaid with a real-time procedural 3D crop animation: as users scroll down, seeds germinate into saplings, vegetative canopies expand, and mature golden wheat and waving paddy panicles emerge from the soil. At the bottom of the scroll sequence, users reach the dedicated **Download & Offline Engine Station** to save the standalone package or launch the in-browser engine.

---

## 🤖 AgriBot Multimodal Diagnostic Assistant

AgriBot operates as an expert agronomic diagnostic assistant and botanical vision expert adhering strictly to **Five Core Operational Principles**:

1. **Structured Visual Triage**: Hierarchical plant analysis:
   - *Growth habit & phyllotaxy* (alternate distichous, opposite, whorled, basal rosette).
   - *Leaf architecture* (monocot vs. eudicot, parallel vs. reticulate venation, margins).
   - *Diagnostic anatomical markers* (auricles, ligules, pulvinus, tendrils, stipules, nectary glands).
   - *Pathology & stress indicators* (interveinal chlorosis, target-board lesions, vascular wilting, necrotic blight).
2. **Probabilistic & Differential Diagnosis**: Primary identification paired with calibrated confidence estimates, differential lookalikes, and field verification questions.
3. **Integrated Pest Management (IPM)**: Strict sequential hierarchy:
   - Cultural & Mechanical controls first $\longrightarrow$ Biological controls second $\longrightarrow$ Chemical interventions strictly as a calibrated last resort.
4. **Chemical Safety & Compliance**: Mandates strict adherence to State Agricultural University (SAU) extension schedules and Central Insecticides Board (CIBRC) approved dosage rates and Pre-Harvest Intervals (PHI).
5. **Missing Context Inquiry**: Before advising irreversible actions, prompts for missing variables: crop growth stage, soil pH, rootzone moisture, and recent weather events.
6. **Empathetic Everyday Telugu Operational Mandate (సరళమైన వాడుక భాష)**:
   - Primary operational mandate: converses exclusively in warm, natural everyday conversational Telugu whenever the user speaks or inputs prompts in Telugu.
   - Strictly avoids archaic, bookish, or formal *grandhikam* (గ్రాంథిక భాష).
   - Explains technical agronomic concepts (chlorosis, drip irrigation, IPM, transpiration) using simple everyday farming analogies.
   - Fluid Telugu vocal pacing calibrated at `0.92` (strictly in the ideal 0.90 to 0.95 range).
   - **Zero English Output Rule**: Never outputs text or audio in English if the input prompt was in Telugu.
7. **Single-Like Constraint on Community Listings**:
   - Each user can give only one like per post listing in the village residency forum (`localStorage` tracking via `sehawa_liked_posts`), preventing duplicate upvotes.

---

## 🚜 Key Architectural Components

### 1. Terrace Background & 3D Scroll-Driven Growth Physics
- **Mountain Terrace Backdrop**: Integrated with photorealistic terraced paddy hills.
- **Scroll Progression**:
  $$\text{🌰 Soil Seed } (0\% \to 25\%) \longrightarrow \text{🌱 Emerging Sapling } (25\% \to 50\%) \longrightarrow \text{🌿 Vegetative Canopy } (50\% \to 75\%) \longrightarrow \text{🌾 Golden Harvest } (75\% \to 100\%)$$
- **Mature Grain Physics**: Nodding rice panicles and wheat spikes with bristling golden awns and dynamic wind oscillation.

### 2. Dedicated Download & Offline Engine Station
- **One-Click Download**: Saves `sehawa-offline-engine.html` locally for 100% offline usage on Android, macOS, Windows, and Linux.
- **In-Browser Execution**: Launches the full standalone suite (`app.html`) inside an interactive glassmorphism modal with full window controls.
- Clean landing page layout without companion suite clutter.

### 3. Offline Agricultural Core Matrix (in `app.html`)
- 5 Soil Profiles $\times$ 2 Water Tables (10 permutations) mapping optimal crop varieties, yield per acre, 3-step crop rotations, and boundary re-afforestation agroforestry trees.
- Home & Rooftop Vegetable Unit with calibrated drip-emitter flow rates (L/hr) and potting mix ratios.
- Companion Planting biological synergies (Marigolds, Mustard trap crops, Basil camouflage).

### 4. Dual-Trigger Weather Shield & Predictive Grid Outage Planner
- Weather event simulation (*Torrential Monsoon*, *Severe Heatwave*, *Sudden Frost*).
- **Predictive Grid Warning**: Approaching storms trigger automatic warnings to run water irrigation pumps before rural electricity lines shut down.
- **Evapotranspiration Irrigation Countdown**: Real-time acoustic countdown deducting rainfall from crop water demands ($ET_c$).

### 5. Verified Pesticide Guide & Community Resilience Forum
- Chemical and organic formulation profiles paired with real commercial trade names (*Tatamida*, *Coragen*, *Amistar Top*, *Blitox 50*).
- Local storage peer-to-peer bulletin board with full CRUD persistence for tractor rentals, tool sharing, and labor squads.

---

## 🚀 Getting Started

No build step or Node.js environment is required. Simply clone the repository and open either `index.html` (the landing page with interactive app popup modal) or `app.html` (the direct standalone companion app) in any browser:

```bash
# Clone the repository
git clone https://github.com/sricharanpativada/sehawa.git

# Navigate to project folder
cd sehawa

# Open in browser or run a simple local server
python3 -m http.server 8080
```

- **Landing Page**: `http://localhost:8080/index.html` (features the seed-sprout 3D canvas and pops the companion app into a window upon clicking **Launch App**, **Open Companion App**, or **Explore Offline Engine**).
- **Standalone Companion App**: `http://localhost:8080/app.html` (direct access to the offline agritech suite).

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

