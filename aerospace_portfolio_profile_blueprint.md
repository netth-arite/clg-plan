# Aerospace Engineering Portfolio & Profile Blueprint

**Target Field:** Aeronautical / Aerospace Engineering  
**Target Level:** Undergraduate Admissions & Full-Ride Scholarships (US Ivy+, Oxford Ellison, UofT Pearson, UBC ILOT, KAIST, PoliMi, Sapienza, MAI)  
**Cost Benchmark:** Free to Low-Cost (Under ₹2 Lakhs INR/year total budget constraint)

---

## 1. Specific Aerospace Project Ideas

To build a competitive admissions profile (especially for MIT's Maker Portfolio or Oxford Ellison's technical portfolio), focus on completing **1–2 well-documented engineering builds or simulations** rather than multiple unfinished projects.

### Tier A: Zero-Cost (Laptop-Only using Open-Source/Industry Tools)

*   **Complete Competition UAV / Glider Design in OpenVSP & flow5 (3–5 Weeks)**
    *   **Concept:** Design a small fixed-wing aircraft from scratch for a defined mission (e.g., carrying a 500 g payload over 15 km at minimum drag).
    *   **Tools:** NASA's **OpenVSP** (with VSPAERO) for parametric 3D geometry and **flow5** (or XFLR5) for airfoil/wing lift-drag polars and static longitudinal stability analysis.
    *   **Deliverables:** Geometry files, polars, stability margin proof, and a concise design trade-off report.

*   **Autonomous Drone Mission & Control Tuning in Simulation (3–4 Weeks)**
    *   **Concept:** Program an autonomous quadcopter or fixed-wing UAV to execute an emergency landing or obstacle avoidance route under simulated crosswinds.
    *   **Tools:** **ArduPilot SITL** (Software-in-the-Loop) coupled with Python via DroneKit/MAVProxy.
    *   **Deliverables:** Python control scripts, SITL flight logs, and telemetry error plots showing PID loop tuning performance.

*   **6-DOF Rocket Trajectory & Landing Simulator in Python (2–4 Weeks)**
    *   **Concept:** Write a 6 Degrees-of-Freedom physics simulator from scratch in Python incorporating thrust curves, atmospheric density decay, drag coefficient curves, and crosswind vectors.
    *   **Tools:** Python (NumPy, SciPy, Matplotlib), verified against **OpenRocket** data.
    *   **Deliverables:** Open-source Python repository with trajectory plots, apogee dispersion maps, and optional closed-loop airbrake/TVC algorithms.

*   **Lunar or LEO Transfer Trajectory Optimizer in NASA GMAT (3–5 Weeks)**
    *   **Concept:** Design and optimize a low-delta-v orbital transfer maneuver (e.g., Earth-to-Moon transfer or CubeSat orbit-raising/deorbit) considering orbital perturbations and launch window constraints.
    *   **Tools:** NASA’s open-source **General Mission Analysis Tool (GMAT)**.
    *   **Deliverables:** GMAT mission scripts, delta-v breakdown, and orbit propagation telemetry visualization.

### Tier B: Low-Cost Hardware (₹500 – ₹3,500)

*   **DIY Wing Flutter & Aeroelasticity Test Rig (~₹500–₹1,200)**
    *   **Concept:** Construct balsa wood or foam airfoil sections mounted on a flexible hinge in front of a controlled fan to observe dynamic stall and aeroelastic flutter onset.
    *   **Tools:** Household fan, anemometer, smartphone accelerometer (via the free **Phyphox** app), and Python for spectral analysis.
    *   **Deliverables:** Comparative plots of predicted vs. observed flutter velocities and dynamic vibration spectrum analysis.

*   **Embedded Flight Data Logger / Avionics Computer in C/C++ (~₹2,000–₹3,500)**
    *   **Concept:** Build a lightweight flight data recorder to measure real-time altitude, 9-DOF motion, and pressure drops during drops or tethered flights.
    *   **Tools:** Microcontroller (ESP32, STM32, or Arduino), BMP280 barometric pressure sensor, MPU6050 IMU, microSD module, and C/C++ firmware.
    *   **Deliverables:** Clean C/C++ codebase with a Kalman filter algorithm to smooth sensor noise, telemetry logs, and raw vs. filtered signal comparisons.

---

## 2. Specific Research Paper Topics (Zero Financial Cost)

A high-school research paper must ask a specific, testable question, rely on reproducible methods, and report error margins honestly. These papers can be submitted to the **IRIS National Fair (ISEF pathway)** or uploaded directly to college applications.

1. **Aerodynamics — Winglet Geometry Optimization:**  
   *Quantifying induced drag reduction vs. root bending moment penalties across variable winglet cant angles and taper ratios at low-to-medium Reynolds numbers in OpenVSP/flow5.*

2. **Propulsion & Maintenance — Jet Engine Remaining Useful Life (RUL):**  
   *Benchmarking physics-informed regression models against machine-learning architectures for predicting turbofan degradation cycles using NASA's public C-MAPSS dataset.*

3. **Aviation Operations — Real-World Descent Efficiency & Emissions Analysis:**  
   *Analyzing live ADS-B flight telemetry from the OpenSky Network API over local airspace (e.g., Pune Airport) to calculate fuel burn and excess CO₂ during step-down vs. continuous descent approaches.*

4. **Space Systems — CubeSat Detumbling Control Simulation:**  
   *Comparing B-dot vs. proportional-derivative magnetorquer control algorithms for detumbling a 3U CubeSat in Low Earth Orbit across varying orbital inclinations using Python.*

5. **Experimental Aerodynamics — Leading-Edge Tubercles at Low Reynolds Numbers:**  
   *Investigating stall delay and lift-drag ratio changes on bio-inspired (humpback-whale) leading-edge airfoils compared to smooth airfoils using low-cost flow visualization or open-source CFD (SU2/OpenFOAM).*

---

## 3. High-Impact Activities Beyond Projects & Papers

1. **Cold-Emailing Academic Institutions for Research Shadowing**
   * Target institutions: **IIT Bombay (Aerospace Dept)**, **COEP Technological University**, **DIAT Pune**, **IISER Pune**, and **IUCAA**.
   * Focus: Offer assistance with remote data cleaning, CAD modeling, literature synthesis, or Python scripting.
   * Key Requirement: Attach proof of a completed simulation or coding project to demonstrate readiness.

2. **Open-Source Aerospace Software Contributions**
   * Contribute bug fixes, documentation, or minor feature code to active open-source aerospace codebases: **ArduPilot**, **PX4**, **OpenRocket**, **OpenVSP**, or **Astropy**.
   * Merged GitHub pull requests serve as verifiable proof of team software engineering capability.

3. **Verifiable Community Leadership & STEM Outreach**
   * Required for top merit/leadership awards (UofT Lester B. Pearson, UBC ILOT, Oxford Ellison).
   * Initiatives: Organize free hands-on physics, math, or coding/CAD workshops for middle/high school students at local community centers or schools in Pune.

4. **Public Technical Documentation & Open Engineering Logs**
   * Maintain a public engineering blog or GitHub repository with clean READMEs, project math, design trade-offs, and failure logs.
   * Serves as direct preparation for Oxford technical interviews and Ellison video submission requirements.

5. **Free University-Level Self-Study**
   * Leverage **MIT OpenCourseWare** (*Introduction to Aerospace Engineering*, *Unified Engineering*) or **TU Delft edX** open tracks to master underlying physics and mathematical foundations without paying for unneeded credentials.

6. **Merit-Based Pre-College Research Applications**
   * Target fully funded/need-blind research programs such as **MIT RSI** (Research Science Institute) or **SSP** (Summer Science Program in Astrophysics, which provides up to 100% need-based financial aid for international students).