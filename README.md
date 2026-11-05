# Sehawa (సెహావా / सेहावा) 🌾

> **Autonomous Offline-First Agricultural Platform & AgriBot Botanical Vision Expert for macOS & Android**  
> Multi-tier soil terrace 3D growth simulation, trilingual conversational agronomic voice AI (Telugu, Hindi, English), hierarchical botanical triage, IPM protocols, and community resilience.

![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Android-emerald?style=for-the-badge)
![Offline](https://img.shields.io/badge/100%25-Offline--First-10B981?style=for-the-badge)
![Voice AI](https://img.shields.io/badge/Voice%20AI-Telugu%20%7C%20Hindi%20%7C%20English-amber?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🌟 Overview

**Sehawa** is an autonomous agritech companion web application designed aggressively for mobile viewports with full responsive desktop compatibility. It executes 100% client-side with zero dynamic API dependencies or external cloud requirements.

The landing page features a photorealistic terraced mountain crop field background layered with a real-time procedural 3D crop canvas:
- **Rich Agricultural Soil & Dark-Green Base**: Multi-tiered terrace shelves with deep emerald turf borders and rich brown loam soil contours provide the living earthen bed from which all crops emerge.
- **Individual Seedbeds & Root Mounds**: Each seed and crop stalk is visibly anchored into a fertile, moist soil mound with organic turf shoots.
- **Scroll Progression**: As users scroll down, dormant seeds nestled in the soil germinate into emerald sapling shoots, expand into leafy vegetative canopies, and mature into heavy golden wheat spikes and nodding paddy panicles.
- At the bottom of the scroll sequence, users reach the dedicated **Download & Offline Engine Station** to save the standalone package or launch the in-browser engine.

---

## 🤖 Dual AI Engines: Voice Assistant & Botanical Vision Triage

### 1. Trilingual Agronomic Voice Assistant (Telugu • Hindi • English)
The voice engine supports three operational modes with automatic script detection and calibrated natural speech synthesis:
- **Telugu to Telugu (తెలుగు)**: Primary regional mandate speaking simple, natural everyday conversational Telugu (*సరళమైన వాడుక భాష*). Strictly avoids bookish or archaic *grandhikam* (గ్రాంథిక భాష). Uses native voice synthesis (`te-IN` / `Google తెలుగు` / `Lekha`) with pacing calibrated at `0.90` for warm, unhurried, human-like rural articulation.
- **Hindi to Hindi (हिन्दी)**: Natural conversational Hindi (*सरल बोलचाल की भाषा*) addressing farmers warmly (*किसान भाइयों*) with native voice synthesis (`hi-IN` / `Google हिन्दी`) at rate `0.92`.
- **English to English (🌐)**: Clear, practical agronomic English response paired with cross-language field translations for farmers and agronomists.
- **19+ Trained Agricultural Domains**: Complete offline intelligence covering paddy blast & blight, cotton whiteflies & pink bollworms, tomato early blight, chili leaf curl virus, nitrogen/iron chlorosis, heavy storm & drainage warnings, electricity grid power & pump run hours, organic 200L Jeevamrutham recipe, drip irrigation fertigation, green manure & soil testing, tractor & equipment hiring, weed control & mulching, and legume crop rotation.

### 2. AgriBot Botanical Vision Triage Expert & Kaggle 38-Class Dataset Engine
Trained on the benchmark **Kaggle New Plant Diseases Dataset (`vipoooool/new-plant-diseases-dataset`)** across 14 crops and 38 distinct pathological and healthy classes:
1. **Procedural Botanical Leaf Specimen Generator**: Renders realistic client-side HTML5 canvas specimens with botanically accurate geometries (odd-pinnate eudicot, compound, lanceolate, linear monocot, palmately lobed) and biological pathology textures (Alternaria bullseye zonate lesions, Phytophthora water-soaked blights, Xanthomonas bacterial spot perforations, powdery mildew talc patches, cedar/common rust pustules, and tiger-stripe Esca).
2. **Real-Time Color & Morphology Spectrum Analysis**:
   - Live pixel classification: Healthy Chlorophyll Green %, Chlorosis Yellowing %, and Necrotic Blight Lesion %.
   - Real-time animated progress bars and dynamic leaf architecture categorization.
3. **Interactive Visual Leaf Q&A Assistant ("Ask AgriBot About This Leaf")**:
   - Multilingual visual triage answering questions about leaf type, morphology, color stress indicators, pathogen diagnosis, biological IPM treatments, contagion risks, and next-season crop rotation.
   - Spoken answers in natural everyday conversational Telugu (`te-IN`), Hindi (`hi-IN`), and English (`en-IN`).
4. **Diagnostic Lesion Heatmap Overlay**:
   - One-click toggle displaying neon bounding boxes, contour overlays, and confidence tags over detected pathogen clusters.
5. **Spoken Voice Command Engine**:
   - Directly process voice commands: *"generate leaf tomato early blight"*, *"what is the leaf type"*, *"what do the leaf colors mean"*, *"diagnose leaf"*, *"recommend treatment"*, and *"is it contagious"*.

Adheres strictly to **Five Core Operational Principles**:
1. **Structured Visual Triage**: Hierarchical plant analysis:
   - *Growth habit & phyllotaxy* (alternate distichous, opposite, whorled, basal rosette).
   - *Leaf architecture* (monocot vs. eudicot, parallel vs. reticulate venation, margins).
   - *Diagnostic anatomical markers* (auricles, ligules, pulvinus, tendrils, stipules, nectary glands).
   - *Pathology & stress indicators* (interveinal chlorosis, target-board lesions, vascular wilting, necrotic blight).
2. **Probabilistic & Differential Diagnosis**: Primary identification paired with calibrated confidence estimates, differential lookalikes, and field verification questions.
3. **Integrated Pest Management (IPM)**: Cultural & Mechanical $\longrightarrow$ Biological controls $\longrightarrow$ Chemical interventions strictly as calibrated last resort.
4. **Chemical Safety & Compliance**: Mandates strict adherence to State Agricultural University (SAU) extension schedules and Central Insecticides Board (CIBRC) approved dosage rates and Pre-Harvest Intervals (PHI).
5. **Missing Context Inquiry**: Before advising irreversible actions, prompts for missing variables: crop growth stage, soil pH, rootzone moisture, and recent weather events.
6. **Instant Regional Audio Advisory**: Provides one-click spoken audio playout in everyday Telugu and Hindi directly inside the diagnostic triage card.

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

