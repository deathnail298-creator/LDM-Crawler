
---

# 5. Subsystem Breakdown

## 5.1 Chassis & Structural Frame
- One-piece or near-monolithic shell  
- Dust-resistant slopes  
- Internal ribs for stiffness & thermal conduction  
- Built to survive micrometeorites and thermal cycling  
- Compatible with simple manufacturing (CNC, machining, casting)

## 5.2 Electrostatic Lift System
- Fixed-voltage plates beneath dielectric coating  
- Upward-directed field geometry  
- Short duty cycle (minutes per day)  
- Solid-state simplicity  
- Primary dust-lifting engine

## 5.3 Passive Agitation & Deposition Geometry
- Terraces and micro-channels  
- Designed for repeated low-energy collisions  
- No clog-sensitive mechanics  
- Creates statistical grain-shape modification over time

## 5.4 Power System
- Fixed solar panel (non-deployable)  
- Small battery with deep-sleep architecture  
- Minimal switching circuitry  
- Designed to survive 14-day lunar nights

## 5.5 Thermal Control System
- Passive conduction to chassis  
- Radiative surfaces shaped away from dust-settling areas  
- Insulated electronics coffin  
- Optional PCM buffer (Phase Zero-permitted)

## 5.6 Electronics Coffin
- Fully sealed and potted  
- Minimal MCU or even discrete timer  
- No sensors or environment feedback  
- EMI-shielded enclosure  

## 5.7 Delivery & Deployment Architecture
- Derived from Crawler delivery system  
- No deployment actions  
- “Place it on the ground and ignore it”  
- Compatible with CLPS-class landers and rovers

## 5.8 Local Environment Interaction
- Fine grains lofted  
- Passively conditioned  
- Gradually expand footprint  
- Works quietly and independently for years

---

# 6. Operating Principle

The LDM runs a **five-step physics cycle**:

### 6.1 Charge & Loft
Electrostatic plates activate briefly.  
Fine grains become charged and loft upward.

### 6.2 Ballistic Return
Dust falls back with no turbulence (no lunar atmosphere).

### 6.3 Passive Agitation
Terraces and micro-channels force rolling, sliding, and collisions.  
Repeated impacts soften grain edges.

### 6.4 Outward Redistribution
Conditioned grains drift outward due to migration and surface activity.

### 6.5 Long-Duration Compounding
Millions of cycles → measurable drop in abrasiveness.

NASA prefers slow, cumulative effects to fragile one-time mechanisms.

---

# 7. Mission Architecture (Phase Zero)

## 7.1 Deployment
- Rover placement  
- Lander-bolted deployment  
- Drop-and-set emplacement  
No unfolding or articulation.

## 7.2 Daily Operating Cycle
- Wake  
- Energize plates for 1–5 minutes  
- Deactivate  
- Let passive geometry work  
- Return to deep sleep

99% of mission time = sleeping.

## 7.3 Footprint
- ~3–15 m operational radius  
- Expands over years  
- Ideal for solar farms, radiators, habitats, rover bays

## 7.4 Timeline
- **Year 0–1**: initial conditioning  
- **Year 1–3**: stable churn zone  
- **Year 3–10+**: expanding conditioned footprint  

## 7.5 End-of-Life Behavior
- Device fails silent  
- May become partially buried  
- Leaves behind slightly conditioned regolith  
- No unsafe modes

---

# 8. Technical Margins & Uncertainties

Phase Zero intentionally leaves certain questions open:

- Regolith electrostatic variability  
- Per-cycle angularity reduction  
- Long-term terrace saturation  
- Solar panel darkening & dust accumulation  
- Dielectric breakdown under cycling  
- Electronics coffin thermal survivability  
- Charge accumulation under solar wind conditions  

Each uncertainty maps cleanly into a Phase One experiment.

---

# 9. Failure Modes & Graceful Degradation

All LDM failures are **benign**:

### 9.1 Functional Failures
- Electrostatic lift fails → device becomes inert  
- Timer fails → device runs irregularly or not at all

### 9.2 Structural Failures
- Micrometeorite impact → reduced efficiency  
- Thermal cracking → lower performance  

### 9.3 Electrical Failures
- Battery fade → permanent sleep  
- Solar panel degradation → reduced duty cycle  
- Dielectric arc → plates burn open & stop functioning  

### 9.4 Graceful End-States
- Quiet inert node  
- Partial functionality  
- Burial by regolith  
No debris, no hazardous emissions, no runaway conditions.

---

# 10. Phase One Path

Phase One validates physics and materials:

## 10.1 Core Objectives
- Confirm electrostatic loft in vacuum  
- Measure grain-shape evolution under agitation  
- Characterize terrace longevity  
- Validate thermal & dielectric durability  

## 10.2 Experiments
- Vacuum loft tests  
- Micro-collision erosion tests  
- Terrace saturation trials  
- Thermal cycling (±150°C)  

## 10.3 Prototype Hardware
- Electrostatic testbed  
- Terraced geometry mock-up  
- Integrated EDU (Engineering Development Unit)

## 10.4 Modeling Work
- DEM collision modeling  
- COMSOL electrostatic field mapping  
- Thermal conduction/radiation FEA  

## 10.5 Success Criteria
- Repeatable loft  
- ≥1% angularity reduction in accelerated tests  
- 100+ thermal cycles with no dielectric failure  
- Power consumption within 20% of model  

## 10.6 Transition Path
- Phase One → Engineering Model  
- Engineering Model → Lunar analog field testing  
- Field testing → CLPS secondary payload demonstration  

---

# Appendix A — Heritage & Lineage

LDM inherits the **Crawler** family design principles:

- rugged monolithic construction  
- passive-first philosophy  
- dust-tolerant geometry  
- failure modes that default to harmless inactivity  

This continuity reduces risk and accelerates contractor adoption.

---

# Appendix B — License

See the project's `LICENSE` file for full terms.

