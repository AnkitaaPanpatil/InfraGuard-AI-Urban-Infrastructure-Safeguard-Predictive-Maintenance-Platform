# 🌉 InfraGuard — AI Urban Infrastructure Safeguard & Predictive Maintenance Platform

> **Next-Generation Metropolitan Structural Health Monitoring (SHM), Real-Time Digital Twin Telemetry, Paris-Erdogan Fatigue Degradation Modeling, and AI-Driven Catastrophe Mitigation.**

**InfraGuard** is an open-source, full-stack, single-file structural intelligence and civil safety platform engineered for smart city command centers, municipal transport authorities, public works departments, and infrastructure concessionaires. By combining live geospatial digital twin overlays, high-speed piezoelectric strain waveforms, acoustic emission analysis, remaining useful life (RUL) prognostic modeling, automated non-destructive testing (NDT) dispatch, and Google Gemini AI, InfraGuard bridges the gap between reactive disaster management and proactive, life-saving infrastructure stewardship.

## 🚨 The Infrastructure Crisis & Systematic Solutions

Aging municipal assets worldwide suffer from deferred maintenance, extreme weather events, and cyclic fatigue, leading to costly emergency closures and tragic structural failures.

| Conventional Infrastructure Challenge | Real-World Urban Impact | InfraGuard Systematic Solution | 
 | ----- | ----- | ----- | 
| **Manual & Periodic Visual Inspections** | Subsurface fatigue cracks, cable fretting, and post-tension tendon corrosion remain undetected between biannual inspections. | **Continuous 100 Hz IoT Telemetry**: Multipoint Fiber Bragg Grating (FBG) strain sensors and InSAR satellite interferometry stream live data to detect micro-deflections instantly. | 
| **Catastrophic Failure Risk** | Bridge cable breaks, tunnel lining displacements, and aqueduct bursts occur with little to no advance warning. | **Automated Emergency Containment SOP**: Dynamic lane restrictions, freight diversions, and rail speed derates trigger automatically when strain exceeds safety thresholds ($> 750\ \mu\epsilon$). | 
| **Reactive Capital Expenditure (CapEx)** | Rebuilding collapsed or condemned spans costs up to 150x more than timely preventive maintenance. | **Paris-Erdogan Fatigue Prognostics**: Weibull survival models project micro-crack growth rate ($da/dN$) to schedule micro-grouting and CFRP wraps, delivering 128x CapEx ROI. | 
| **Fragmented Sensor Silos** | Inclinometers, accelerometers, piezometers, and corrosion probes operate on disconnected proprietary systems. | **Unified GIS Digital Twin**: Single-pane Leaflet.js command center synthesizing multi-modal sensor inputs with spatial asset telemetry. | 
| **Delayed Emergency Dispatch** | Slow bureaucratic escalations delay certified field engineers from deploying specialized testing rigs. | **Telematics Field Dispatch Pipeline**: Automated work orders equipped with GPS coordinates, SLA countdown clocks, and crew telemetry routed directly to NDT specialists. | 

## 🌟 Core System Pillars

### 1. 🗺️ Interactive GIS Metropolitan Digital Twin (Leaflet.js)

* **High-Contrast Digital Twin Grid**: CartoDB dark-matter geospatial mapping tracking key municipal assets:

  * 🌉 **Cable-Stayed Suspension Bridges**: Real-time cable stay tension, wind-induced sway, and deck acceleration.

  * 🚇 **Subsurface Transit Tubes & Tunnels**: Segmented lining displacement, seismic vibration, and pore water ingress pressure.

  * 💧 **High-Volume Aqueduct Viaducts**: Hydrostatic surge pressure, concrete cavitation, and joint expansion.

  * 🛣️ **Prestressed Concrete Flyovers & Overpasses**: Cyclic truck axle deflection and corrosion rate sensors.

* **Dynamic Structural Health Index (SHI)**: Live asset scoring ($0 - 100$) color-coded by severity:

  * 🟢 **Nominal** ($\text{SHI} \ge 90$): Optimal baseline dynamics.

  * 🟡 **Warning** ($70 \le \text{SHI} \le 89$): Vibration drift, thermal strain anomalies, or pore pressure shifts.

  * 🔴 **Critical Alert** ($\text{SHI} < 70$): Microstrain exceeds ASCE thresholds; triggers containment protocols.

* **Spatial Telemetry Inspector**: Instant search and filter across monitored hubs with animated fly-to navigation and real-time sensor node diagnostics.

### 2. ⚡ Piezoelectric Dynamic Strain & Micro-Vibration Oscilloscope (HTML5 Canvas)

* **Live 100 Hz Waveform Stream**: Real-time oscilloscope rendering raw dynamic microstrain ($\mu\epsilon$), baseline tolerance limits, and harmonic modal drift.

* **Harmonic Spectrum & Modal Analysis**:

  * Continuous measurement of fundamental natural frequencies ($f_0 \approx 3.42\text{ Hz}$).

  * Fast Fourier Transform (FFT) damping ratio computation to detect mechanical friction loss or joint loosening.

* **Transient Load Injection Simulator**: Allows structural engineers to simulate transient spikes induced by heavy freight trains or minor seismic tremors to test real-time system damping and recovery.

* **Multi-Modal Physical Telemetry Transducers**:

  * Dual-axis MEMS inclinometer drift ($\pm 0.014^\circ$).

  * Fiber Bragg Grating (FBG) thermal expansion tracking ($31.4^\circ\text{C}$, $+1.2\text{ mm}$).

  * Acoustic emission (AE) transducer hit rates detecting micro-crack propagation signatures.

### 3. ⏳ Paris-Erdogan Fatigue Degradation & RUL Horizon Modeling

* **Fracture Mechanics Degradation Curves**: Computes subcritical crack propagation rate governed by the Paris-Erdogan relation:
  

  $$
  \frac{da}{dN} = C(\Delta K)^m
  $$

  
  where $\Delta K$ is the stress intensity factor range, calibrated via cumulative cyclic commuter traffic loading.

* **Remaining Useful Life (RUL) Horizon**: Neural Weibull survival estimation computing asset lifespan in years and recommending proactive retrofit windows.

* **CapEx Cost-Benefit ROI Calculator**:

  * Direct comparison of proactive intervention (e.g., $\$64,000$ micro-grouting or CFRP wrap) versus catastrophic rebuilding ($\$8,200,000$).

  * Embodied carbon budget tracking displaying metric tons of $\text{CO}_2\text{e}$ preserved by avoiding emergency Portland cement replacements.

### 4. 🛠️ Structural Engineering Field Work Order Dispatch

* **Automated Ticket Pipeline**: High-priority work orders generated with unique tracking IDs (`WO-2026-881`), SLA resolution windows (24-Hour emergency to 72-Hour preventive), and GPS coordinates.

* **Specialized Response Teams**: Standby crew monitoring including Alpha Team (Acoustic & Ultrasonic NDT), Bravo Team (Geotechnical Ingress & Tunnel Grouting), and Charlie Team (Grid & Sensor Telematics).

* **Rapid Containment Standard Operating Procedure (SOP)**: Modal-triggered traffic safeguards interfacing with smart traffic signals:

  * Commercial truck restriction ($> 15\text{ tons}$).

  * Metro speed derate ($-40\%$).

  * Variable Message Sign (VMS) digital bypass broadcast.

### 5. 🧠 InfraGuard Copilot — Lead Civil & Structural Diagnostics AI

* **Powered by Gemini 3 Flash**: Dedicated engineering diagnostics assistant trained on ASCE, Eurocode, and FEMA infrastructure safety codes.

* **One-Touch Diagnostic Prompts**:

  * 🌉 *Bridge Cable Microstrain Audit*

  * 🚇 *Tunnel Deflection & Water Ingress Tolerances*

  * 🛡️ *Concrete Spalling & Post-Tension Corrosion Containment*

* **Offline Heuristic Resiliency**: Built-in statutory structural engineering logic ensures critical safety recommendations are generated even during severed internet connectivity.

## 🛠️ Technical Architecture

InfraGuard is engineered strictly under the **Single-File Mandate** (`infraguard_app.html`), ensuring instantaneous zero-build execution in any modern web browser without dependencies, package managers, or backend runtimes.

| Architecture Layer | Technology Stack | Purpose & Integration | 
 | ----- | ----- | ----- | 
| **Presentation Tier** | HTML5 / Semantic DOM | Zero-latency 5-tab structural operations dashboard | 
| **Styling Framework** | Tailwind CSS CDN | Modern design tokens: `infra` cyan, `hazardRed`, `sensorAmber`, `healthGreen`, and `steelDark` glassmorphism | 
| **Typography** | Google Fonts | `Plus Jakarta Sans` for clean UI legibility, `JetBrains Mono` for stress tensors & coordinates | 
| **Geospatial Engine** | Leaflet.js (v1.9.4) & CartoDB Dark Matter | Interactive hardware-accelerated mapping, custom HTML div-markers, dynamic tooltips | 
| **Oscilloscope Engine** | HTML5 2D Canvas API | Real-time animated sinusoidal strain waveforms, tolerance limit lines, and transient harmonic modeling | 
| **Acoustic Synthesizer** | Web Audio API | Synthesized sine, sawtooth, and triangle frequencies for nominal pings, sensor alarms, and containment alerts | 
| **Generative Intelligence** | Google Gemini API (`gemini-3-flash-preview`) | Structural stress evaluation, ASCE/Eurocode compliance audits, and mitigation protocols | 
| **State Machine** | Vanilla JavaScript (ES6+) | In-memory reactive state managing asset SHI scores, sensor nodes, work orders, and live telemetry | 

## 🚀 Quick Start & Installation

InfraGuard requires **no package installations, no compilation steps, and no database configurations**.

### Method 1: Direct Browser Launch

1. Download or clone `infraguard_app.html`.

2. Double-click the file to open it directly in Google Chrome, Brave, Mozilla Firefox, Microsoft Edge, or Safari.

### Method 2: Lightweight Local HTTP Server (Recommended)

Running via a local HTTP server provides optimal asset caching and smoother geolocation handling:

```
# Using Python 3
python -m http.server 8080

# Or using Node.js (npx)
npx serve .

```

Open your browser and navigate to:

```
http://localhost:8080/infraguard_app.html

```

## 🔑 Connecting the Gemini AI API Key

The application contains built-in structural engineering fallback heuristics that answer cable strain, tunnel ingress, and spalling queries immediately. To enable live generative AI diagnostics through Google Gemini:

1. Open `infraguard_app.html` in any code or text editor.

2. Locate the `submitAiStructuralQuery` function (around line 520):

   ```
   const apiKey = "YOUR_GEMINI_API_KEY_HERE";
   
   ```

3. Generate a free API key from [Google AI Studio](https://aistudio.google.com/?utm_source=gemini).

4. Insert your key into the empty string, save the file, and refresh your browser.

## 🔄 Structural Anomaly & Incident Lifecycle

```
  [Continuous IoT Telemetry] ──> [Dynamic Microstrain Spike (>740 με)] ──> [SHI Drops to Critical]
              │                                                                     │
              ▼                                                                     ▼
  [Oscilloscope Waveform Surge] ──> [Audio Alert Chime] ────────────────> [Containment SOP Prompt]
              │                                                                     │
              ▼                                                                     ▼
  [Traffic Diverted / Derated] ───> [Work Order Dispatched] ─────────────> [NDT Field Crew Deployed]
              │                                                                     │
              ▼                                                                     ▼
  [Consult InfraGuard Copilot] ───> [CFRP Wrap / Micro-Grout Protocol] ──> [SHI Restored to Nominal]

```

1. **Detection**: IoT strain gauges detect transient microstrain exceeding calibrated design limits ($> 740\ \mu\epsilon$).

2. **Escalation**: Asset Structural Health Index drops from nominal ($94.6$) to critical ($62$), triggering auditory alarms and pulsing red digital twin beacons.

3. **Containment**: Chief Inspector activates **Rapid Containment SOP**, locking freight lanes and derating transit metro speed by $40\%$.

4. **Investigation**: Oscilloscope inspects harmonic natural frequencies, damping drift, and acoustic emission hits.

5. **Mitigation**: Copilot evaluates fracture mechanics and issues an emergency NDT inspection ticket to deploy ultrasonic flaw detection rigs.

## 📊 Calibrated Engineering Standards

InfraGuard measures all structural telemetry against recognized civil engineering benchmarks:

* **ASCE 7-22 (Minimum Design Loads and Associated Criteria)**:

  * Peak allowable dynamic microstrain on suspension stays: $\epsilon_{\text{allowable}} < 750\ \mu\epsilon$.

* **Eurocode 3 (Design of Steel Structures — Fatigue)**:

  * Allowable stress fluctuation: $\Delta\sigma \le 42\text{ MPa}$ per $2 \times 10^6$ cycles for Category 125 details.

* **FEMA Tunnel Water Ingress & Ground Subsidence Standards**:

  * Maximum allowable pore differential pressure: $\Delta P < 1.4\text{ Bar}$.

## 📄 License

This software is released under the [MIT License](LICENSE) — free to use, modify, and adapt for municipal departments of transportation, civil engineering research laboratories, smart city infrastructure hackathons, and structural health monitoring deployments.
