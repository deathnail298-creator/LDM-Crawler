# LDM — Phase One Development Path  
## Transition from Phase Zero Concept → Validated Engineering Prototype

_Last Updated: Phase Zero Release_

Phase One transforms the LDM from a credible physics concept into a **measured, test-backed, engineering-ready subsystem** suitable for eventual lunar surface demonstration.

The purpose of Phase One is not flight hardware.  
The purpose is **evidence**.

---

# 1. Phase One Objectives

Phase One focuses on four measurable goals:

1. **Validate electrostatic loft efficiency** in vacuum using lunar regolith simulant.  
2. **Quantify micro-collision erosion** caused by the passive agitation geometry.  
3. **Assess long-duration survivability** of terrace structures and dielectric layers.  
4. **Establish early thermal, electrical, and endurance models** to project multi-year behavior.

These objectives map directly to the Phase Zero uncertainties.

---

# 2. Core Tasks

Phase One executes four categories of work:

- **2.1 Experimental Validation**
- **2.2 Hardware Prototype Development**
- **2.3 Modeling & Simulation**
- **2.4 Environmental Testing**

Each category is listed below with the exact deliverables NASA/SBIR reviewers expect.

---

# 2.1 Experimental Validation

### A. Vacuum Electrostatic Loft Test
Purpose: confirm that fine-grain simulant lifts reliably under fixed-bias electrostatics.

Procedure:
- Place JSC-1A or NU-LHT simulant over a plate array.
- Evacuate chamber to **10^-5–10^-6 torr**.
- Apply fixed HV.
- Measure loft height, particle count, and repeatability.

Deliverables:
- Video/imagery of loft events  
- Loft-height vs. voltage curves  
- Energy budget per loft cycle  

---

### B. Micro-Collision Erosion Measurement
Purpose: measure angularity reduction from repeated passive agitation events.

Procedure:
- Build small terraced geometry sample.
- Drop fine simulant repeatedly using gravity-fed system.
- Collect particles after **N cycles**.
- Analyze using SEM or micro-CT.

Deliverables:
- Before/after angularity histograms  
- Micro-CT cross-sections  
- Statistical measure of edge smoothing  

---

### C. Terrace Saturation & Flow Study
Purpose: determine whether terraces clog or self-clean over time.

Procedure:
- Operate agitation surface under continuous dust deposition cycles.
- Introduce vibration (optional) to simulate lander/rover micro-motions.
- Measure dust residence time and clearing behavior.

Deliverables:
- Terrace fill rates  
- Saturation curves  
- Conditions under which terraces restore functionality  

---

### D. Thermal Cycling Endurance
Purpose: verify dielectric, coatings, adhesives, and PCB potting survive lunar thermal swings.

Procedure:
- Subject samples to ±150°C cycling for **≥100 cycles**.
- Measure dielectric breakdown voltage before/after.
- Inspect for cracking, delamination, or blistering.

Deliverables:
- Thermal endurance charts  
- Dielectric strength retention curves  
- Failure thresholds  

---

# 2.2 Hardware Prototype Development

Phase One produces **three physical prototypes**:

### Prototype 1 — Electrostatic Plate Testbed
- Bench power supply  
- HV driver  
- Replaceable dielectric skins  
- Used for loft tests and dielectric endurance checks  

### Prototype 2 — Terrace Agitation Module
- Static terraced/micro-channel surface  
- Dust-collision experiments  
- Clogging/saturation measurements  
- No electronics  

### Prototype 3 — Integrated EDU (Engineering Development Unit)
- Structural chassis mock-up  
- Real terraces  
- Real dielectric  
- Real solar panel  
- Real electronics coffin  
- Not flight-like but representative of architecture

Deliverables:
- Fabrication drawings  
- Bill of materials  
- Bench test results  

---

# 2.3 Modeling & Simulation

Phase One requires three modeling tracks:

### A. DEM Simulation (Dust Collision)
- Predict grain-shape evolution under repeated impacts  
- Validate DEM predictions against SEM/micro-CT data  
- Generate angularity reduction curves over mission timescales  

### B. Electrostatic Field Modeling
- Use COMSOL/ANSYS or open-source Poisson solvers  
- Model field uniformity, loft potential, charge distribution  
- Estimate HV thresholds and efficiency  

### C. Thermal Conduction & Radiation FEA
- Model daytime heating and nighttime cooling  
- Predict electronics coffin steady-state temperatures  
- Evaluate radiator adequacy and thermal bottlenecks  

Deliverables:
- Model inputs, assumptions, meshes  
- Result visualizations  
- Comparison of predicted vs. measured behavior  

---

# 2.4 Environmental Testing Matrix

NASA requires Phase One to include a clear test roadmap.

| Test Type                    | Required | Purpose |
|------------------------------|----------|---------|
| Vacuum Loft Test             | Yes      | Prove electrostatic lift |
| Micro-Collision Erosion Test | Yes      | Validate dust conditioning claim |
| Terrace Saturation Test      | Yes      | Ensure long-term functionality |
| Thermal Cycling              | Yes      | Validate materials & dielectric |
| Vibration Testing            | Optional | Launch survivability |
| Radiation Exposure           | Optional | Qualitative tolerance data |
| Long-Duration HV Cycling     | Yes      | Plate endurance and dielectric fatigue |

Deliverables:
- Test logs  
- Pre/post analysis  
- Pass/fail summary  

---

# 3. Phase One Success Criteria

NASA/SBIR proposals MUST define crisp thresholds.  
These are realistic and achievable:

## 3.1 Primary Success Metrics

1. **Repeatable loft of fine-grain simulant in vacuum.**  
2. **Measured ≥1% angularity reduction** in accelerated collision tests.  
3. **Terrace structures remain functional** after equivalent of months of dust cycles.  
4. **Dielectric layer survives ≥100 thermal cycles** without breakdown.  
5. **Power budget matches Phase Zero model within ±20%.**

## 3.2 Secondary Metrics

- HV failure modes are safe and predictable  
- Electronics coffin remains within allowable temperature range  
- No mechanical degradation that threatens mission assets  

---

# 4. Deliverables for NASA/SBIR Review

Phase One outputs:

### Documentation
- Experimental data package  
- Model package (DEM, electrostatics, thermal)  
- Updated ACS2 system diagram  
- Prototype design files (CAD, drawings, BOMs)  
- Final Phase One Report  

### Hardware
- Electrostatic testbed  
- Terrace agitation module  
- Integrated EDU prototype  

### Analysis
- Grain-shape evolution results  
- Thermal endurance curves  
- Dielectric fatigue data  

---

# 5. Transition Path to Flight

Phase One → Phase Two → Field Test → Lunar Demo

### Phase Two
- Build a full engineering model  
- Run extended vacuum + thermal chamber tests  
- Improve electronics coffin robustness  
- Perform HV endurance and fatigue testing  

### Field Testing
- Terrestrial analog site deployment (Arizona, Iceland, etc.)  
- Multi-month endurance run  

### Lunar Flight Demonstration
- CLPS lander secondary payload  
- Single-unit deployment near solar arrays, radiators, lander pads  
- Monitor dust conditioning footprint over 6–12 months  

---

# 6. Summary

Phase One transforms LDM from:

> **“A well-structured Phase Zero concept”**  
into  
> **“A validated, engineering-supported subsystem with measurable dust-conditioning capability.”**

It does this through:
- vacuum loft tests  
- micro-collision erosion measurement  
- terrace saturation evaluation  
- thermal endurance validation  
- modeling + prototypes + data  

Phase One is realistic, fundable, and well-aligned with NASA’s risk posture and testing culture.

