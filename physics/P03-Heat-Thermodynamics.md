# P03 — Heat & Thermodynamics 🔥 Priority 1

> **Exam Importance:** Heat is one of the highest-yield Physics chapters. Temperature scales, specific heat, latent heat, modes of heat transfer, anomalous expansion of water, Laws of Thermodynamics, and boiling point variations appear in virtually every paper.

**Cross-links:** [P02 Work-Energy](P02-Work-Energy-Power.md) · [C08 States of Matter](../Chemistry/C08-States-of-Matter-Gases.md) · [C12 Thermochemistry](../Chemistry/C12-Thermochemistry.md)

---

## 1. Chapter Importance Analysis

| Exam | Avg Questions | Focus Areas |
|------|--------------|-------------|
| RRB NTPC | 3–4 | Temperature scales, specific heat, expansion |
| RRB JE | 2–3 | Laws of thermodynamics, heat transfer |
| SSC CGL | 2–3 | Temperature conversions, facts |
| SSC JE | 3–4 | Numericals + concepts |
| APPSC AEE | 2–3 | Concepts + fact-based |

---

## 2. PYQ Trend Analysis

| Topic | Frequency |
|-------|-----------|
| Temperature scale conversion | Very High 🔥 |
| Anomalous expansion of water (max density at 4°C) | Very High 🔥 |
| Specific heat of water (4200 J/kg·K) | Very High 🔥 |
| Modes of heat transfer (conduction/convection/radiation) | Very High 🔥 |
| Boiling point changes with pressure | High ⭐ |
| Latent heat concept | High ⭐ |
| Laws of Thermodynamics | High ⭐ |
| Thermal expansion | High ⭐ |

---

## 3. Temperature

### 3.1 Temperature Scales

| Scale | Symbol | Freezing Point | Boiling Point | Absolute Zero |
|-------|--------|---------------|--------------|---------------|
| Celsius | °C | 0 | 100 | −273.15 |
| Fahrenheit | °F | 32 | 212 | −459.67 |
| Kelvin | K | 273.15 | 373.15 | 0 (absolute zero) |
| Rankine | °R | 491.67 | 671.67 | 0 |

### 3.2 Conversion Formulas

```
K = °C + 273.15    (use 273 for approximations)
°C = (°F − 32) × 5/9
°F = (9/5 × °C) + 32
°C = (K − 273)

Special point: −40°C = −40°F  (same numerical value!)
Body temp: 37°C = 98.6°F = 310 K
```

### 3.3 Instruments to Measure Temperature

| Instrument | Type | Range | Use |
|-----------|------|-------|-----|
| Clinical thermometer | Mercury-in-glass | 35–42°C | Human body temperature |
| Laboratory thermometer | Mercury-in-glass | −10 to 110°C | Lab use |
| Pyrometer (optical) | Non-contact | Very high temps | Furnaces, molten metals |
| Thermistor | Electrical | Wide range | Electronic circuits |
| Thermocouple | Electrical (EMF) | −270 to 1700°C | Industrial |
| Gas thermometer | Gas expansion | Very wide | Standard reference |

> **Absolute zero (0 K = −273.15°C):** Theoretically the lowest possible temperature where all molecular motion stops. Unattainable in practice (Third Law of Thermodynamics).

---

## 4. Heat vs Temperature

| Property | Heat | Temperature |
|---------|------|-------------|
| Definition | Form of energy transferred due to temperature difference | Measure of degree of hotness/coldness |
| Nature | Energy (quantity) | Scalar property (intensity) |
| Unit | Joule (J) or calorie (cal) | Celsius (°C), Kelvin (K), Fahrenheit (°F) |
| Direction of flow | Flows from higher T to lower T | Indicates direction of heat flow |
| Depends on | Mass, specific heat, temperature change | Average KE of molecules |

---

## 5. Specific Heat Capacity

### 5.1 Definition and Formula

> Specific heat capacity = amount of heat required to raise the temperature of **1 kg** of substance by **1°C (or 1 K)**

```
Q = mcΔT
```
- Q = heat absorbed/released (J)
- m = mass (kg)
- c = specific heat capacity (J/kg·K)
- ΔT = change in temperature (K or °C)

### 5.2 Specific Heat Values — PYQ Master Table

| Substance | Specific Heat c (J/kg·K) | Notes |
|---------|------------------------|-------|
| **Water** | **4200** | Highest among common liquids — crucial fact |
| Ice | 2100 | Half of water |
| Steam | 2010 | |
| Alcohol (ethanol) | 2400 | |
| Mercury | 140 | Lowest among common liquids |
| Aluminium | 900 | |
| Iron / Steel | 460–500 | |
| Copper | 385 | |
| Gold | 128 | |
| Lead | 128 | |
| Glass | 840 | |
| Sand | 800 | |
| Air | 1005 | |
| Hydrogen | 14300 | Highest of all elements |

### 5.3 Significance of Water's High Specific Heat

- Water can absorb/release large amounts of heat with small temperature change
- **Coastal climate** is moderate (sea absorbs heat in summer, releases in winter)
- **Used as coolant** in car radiators, power stations
- Body temperature regulation — blood is mostly water
- Oceans act as global heat reservoirs (regulates Earth's climate)

---

## 6. Latent Heat

### 6.1 Definition
Heat absorbed or released during a **change of phase** (state change) WITHOUT any change in temperature.

```
Q = mL
```
- L = specific latent heat (J/kg)
- No temperature change during phase change!

### 6.2 Types of Latent Heat

| Type | Process | Example |
|------|---------|---------|
| Latent heat of fusion | Solid → Liquid (or reverse) | Ice melting at 0°C |
| Latent heat of vaporisation | Liquid → Gas (or reverse) | Water boiling at 100°C |

### 6.3 Latent Heat Values for Water

| Process | Latent Heat |
|---------|------------|
| Fusion of ice | 334,000 J/kg = 334 kJ/kg |
| Vaporisation of water | 2,260,000 J/kg = 2260 kJ/kg |

> **Exam Note:** Latent heat of vaporisation >> latent heat of fusion. This is why steam burns are more severe than boiling water burns at the same temperature — steam releases extra 2260 kJ/kg upon condensation.

### 6.4 Phase Diagram Concept (Temperature vs Heat Graph)

```
Temperature
    |
100°C ─────────────── B ─── C (boiling, T constant)
    |                  |         \
    |                  |          \
  0°C ─── A (melting, T constant) \
    |      |                       \
    |      |                        \
    └──────────────────────────────────→ Heat added
         Solid | Melting | Liquid | Vaporising | Gas
```
- At A (0°C): solid melts — temperature stays constant while latent heat of fusion is absorbed
- At B-C (100°C): liquid boils — temperature stays constant while latent heat of vaporisation is absorbed

---

## 7. Thermal Expansion

### 7.1 Types

```
Linear expansion:   ΔL = L₀αΔT        → α = linear expansion coefficient
Area expansion:     ΔA = A₀(2α)ΔT     → β = 2α
Volume expansion:   ΔV = V₀(3α)ΔT     → γ = 3α
Relation: α : β : γ = 1 : 2 : 3
```

### 7.2 Applications of Thermal Expansion

| Application | Principle |
|------------|-----------|
| Gaps left in railway tracks | Rail expands in summer; gaps prevent buckling |
| Gaps in bridges (expansion joints) | Thermal expansion accommodation |
| Thermometers | Mercury/alcohol expands with temperature |
| Bimetallic strip (thermostat) | Two metals with different α bend on heating |
| Riveting | Hot rivet inserted, on cooling contracts and tightens |
| Ball and ring experiment | Metal ball passes through ring when cold, doesn't when hot |
| Overhead telephone wires | Kept slack for summer expansion |

### 7.3 Anomalous Expansion of Water (CRITICAL PYQ TOPIC)

> **Water contracts on cooling from 4°C to 0°C (anomalous behaviour). It is MOST DENSE at 4°C.**

| Temperature | Behaviour |
|-------------|-----------|
| Above 4°C | Expands on heating (normal) |
| 4°C → 0°C | Contracts on heating (anomalous — reverse!) |
| At 0°C | Water freezes to ice |
| Ice | LESS DENSE than water → floats |

**Why ice floats:**
- Ice forms at 0°C and has a more open crystal structure (hexagonal)
- Density of ice (~917 kg/m³) < Density of water (~1000 kg/m³)
- Hence ice floats on water

**Significance:**
- Lakes freeze from surface downward (ice on top insulates water below)
- Aquatic life survives in frozen lakes (water at 4°C at bottom)
- Pipes burst in winter (water expands on freezing)
- This is why pipes in cold climates need insulation

---

## 8. Modes of Heat Transfer

### 8.1 Conduction

- **Definition:** Heat transfer through a material WITHOUT movement of the material itself
- Requires a **physical medium** (solid is best)
- Mechanism: Molecular vibration and free electron transfer
- **Best conductors:** Silver, Copper, Aluminium (metals)
- **Poor conductors (insulators):** Wood, rubber, wool, glass, air

| Property | Detail |
|---------|--------|
| Medium required | Yes (solid preferred) |
| Molecular movement | No (molecules vibrate in place) |
| Rate | Slow |
| Example | Iron rod heated at one end; heat conducting pot |

**Thermal Conductivity (k):** Higher k → better conductor

| Material | Relative Conductivity |
|---------|-----------------------|
| Silver | Best metal conductor |
| Copper | Second best |
| Gold | Third |
| Aluminium | Fourth |
| Air | Very poor (good insulator) |

### 8.2 Convection

- **Definition:** Heat transfer through movement of the heated fluid (liquid or gas) itself
- Requires a **fluid medium** (liquid or gas)
- Mechanism: Heated fluid expands, becomes less dense, rises; cool fluid sinks → creates convection current

| Property | Detail |
|---------|--------|
| Medium required | Yes (liquid or gas) |
| Molecular movement | Yes (bulk movement of fluid) |
| Rate | Medium |
| Example | Boiling water, sea breeze, trade winds, hot air balloon |

**Types of Convection:**

| Type | Mechanism | Example |
|------|-----------|---------|
| Natural convection | Density difference due to temperature | Sea breeze, trade winds |
| Forced convection | Fan/pump forces fluid movement | Air conditioner, cooling fan |

**PYQ Examples:**
- Sea breeze (day): land heats faster → air over land rises → sea air flows in
- Land breeze (night): sea stays warmer → air over sea rises → land air flows out
- Trade winds, monsoons → large-scale atmospheric convection
- Heating in a room — hot air rises, cool air sinks

### 8.3 Radiation

- **Definition:** Heat transfer as electromagnetic waves (infrared radiation) without any material medium
- Does **NOT** require a medium — can travel through vacuum
- Fastest mode of heat transfer

| Property | Detail |
|---------|--------|
| Medium required | NO (works in vacuum) |
| Nature | Electromagnetic waves (infrared) |
| Speed | Speed of light (3 × 10⁸ m/s) |
| Example | Heat from sun, heat from fire felt at distance |

**Black body:**
- A perfect absorber and emitter of radiation
- Dark/black surfaces absorb and emit more; shiny surfaces reflect more

**Stefan-Boltzmann Law:**
```
P = σAT⁴    (power radiated proportional to T⁴)
```

**Greenhouse Effect:**
- Glass/CO₂ allows short-wavelength sunlight to pass but traps long-wavelength infrared radiation
- Leads to global warming (see [B09 Ecology](../Biology/B09-Ecology-Environment.md))

### 8.4 Comparison Table

| Feature | Conduction | Convection | Radiation |
|---------|-----------|-----------|----------|
| Medium needed | Yes (solid) | Yes (fluid) | NO |
| Mechanism | Molecular vibration | Bulk fluid flow | EM waves |
| Speed | Slowest | Medium | Fastest (speed of light) |
| Vacuum possible | No | No | Yes |
| Example | Metal rod | Boiling water | Sun's heat reaching Earth |

---

## 9. Laws of Thermodynamics

### 9.1 Zeroth Law

> *"If body A is in thermal equilibrium with body B, and body B is in thermal equilibrium with body C, then A is in thermal equilibrium with C."*

- **Basis of thermometers** — a thermometer reaches thermal equilibrium with the body whose temperature it measures
- Defines the concept of temperature

### 9.2 First Law (Law of Energy Conservation)

> *"The heat added to a system equals the increase in internal energy plus the work done by the system."*

```
ΔQ = ΔU + W
or: ΔU = ΔQ − W
```
- ΔQ = heat absorbed
- ΔU = change in internal energy
- W = work done by system

**Implications:**
- Energy cannot be created or destroyed
- A perpetual motion machine of the first kind (creates energy from nothing) is impossible

### 9.3 Second Law

> *"Heat spontaneously flows only from a hotter body to a cooler body. The entropy of an isolated system always increases."*

**Kelvin's statement:** It is impossible to construct a device that extracts heat from a reservoir and converts it entirely into work (no 100% efficient heat engine).

**Clausius's statement:** Heat cannot spontaneously flow from a cold body to a hot body.

- **Entropy (S):** Measure of disorder of a system; always increases in a spontaneous process
- A perfect refrigerator (that cools without using energy) is impossible
- Carnot engine = most efficient theoretical heat engine

**Carnot Efficiency:**
```
η = 1 − T_cold/T_hot    (temperatures in Kelvin)
```
- Always < 100% since T_cold ≠ 0 K (absolute zero unattainable)

### 9.4 Third Law

> *"The entropy of a perfect crystalline substance at absolute zero temperature is zero. Absolute zero (0 K) is unattainable."*

---

## 10. Special Topics — PYQ Favourites

### 10.1 Effect of Pressure on Boiling/Melting Points

| Effect | Boiling Point | Melting Point |
|--------|-------------|--------------|
| Increase pressure | Increases ↑ | Increases (for most) |
| Decrease pressure | Decreases ↓ | Decreases (for most) |

**Applications:**

| Situation | Explanation |
|-----------|-------------|
| Pressure cooker cooks faster | High pressure → higher boiling point of water (>100°C) → food cooks faster |
| Water boils below 100°C at high altitude | Low atmospheric pressure → lower boiling point |
| Mount Everest: water boils at ~70°C | Very low pressure at high altitude |
| Ice melts under skate blade | High pressure reduces melting point of ice slightly (regelation) |

### 10.2 Newton's Law of Cooling

```
dT/dt ∝ (T − T_surroundings)
```
- Rate of cooling is proportional to excess temperature above surroundings
- A hot body cools faster when temperature difference is large; slower as it approaches room temperature

### 10.3 Thermal Equilibrium

- Two bodies in contact exchange heat until they reach the **same temperature** (thermal equilibrium)
- The hotter body loses heat = heat gained by the colder body (no heat lost to surroundings):
```
m₁c₁(T₁ − T_mix) = m₂c₂(T_mix − T₂)
```

---

## 11. Solved Numericals

### Numerical 1
**Q:** Convert 100°C to Kelvin and Fahrenheit.
```
K = 100 + 273 = 373 K
°F = (9/5 × 100) + 32 = 180 + 32 = 212°F
```

### Numerical 2
**Q:** How much heat is needed to raise the temperature of 2 kg of water from 20°C to 80°C?
```
Q = mcΔT = 2 × 4200 × (80 − 20) = 2 × 4200 × 60 = 504,000 J = 504 kJ
```

### Numerical 3
**Q:** How much heat is released when 500 g of ice melts at 0°C? (L_fusion = 334 kJ/kg)
```
Q = mL = 0.5 × 334,000 = 167,000 J = 167 kJ
```

### Numerical 4
**Q:** 200 g of water at 80°C is mixed with 300 g of water at 20°C. Find the final temperature.
```
Using heat balance: m₁c(T₁−T) = m₂c(T−T₂)
0.2(80−T) = 0.3(T−20)
16 − 0.2T = 0.3T − 6
22 = 0.5T
T = 44°C
```

### Numerical 5
**Q:** What is the efficiency of a Carnot engine working between 500 K and 300 K?
```
η = 1 − T_cold/T_hot = 1 − 300/500 = 1 − 0.6 = 0.4 = 40%
```

---

## 12. Shortcut Tricks & Memory Techniques

> **"CCR for heat transfer"**: Conduction, Convection, Radiation — like the rock band. **C**onduction needs contact, **C**onvection needs current (fluid), **R**adiation needs nothing.

> **"Kelvin = Celsius + 273"** — Kelvin always 273 more. No negative in Kelvin (unlike Celsius).

> **"Water is the SUPERSTAR of specific heat"** — 4200 J/kg·K. Nothing common beats it. That's why the sea regulates coastal climate.

> **"−40 is the magic number"** — −40°C = −40°F (the only point where both scales are equal).

> **"ADEK laws"**: Actually **ZEROTH, FIRST, SECOND, THIRD** — use 0-1-2-3 for laws of thermodynamics.

> **"Pressure Cooker = Higher BP"** — More pressure → higher boiling point → food cooks faster.

> **"Mountain = Lower BP"** — Less pressure at altitude → water boils below 100°C → food takes longer to cook.

---

## 13. Frequently Confused Concepts

| Concept A | Concept B | Key Difference |
|-----------|-----------|----------------|
| Heat | Temperature | Heat = energy; Temperature = measure of hotness |
| Specific heat | Heat capacity | Specific heat = per kg; Heat capacity = for whole body (mc) |
| Conduction | Convection | Conduction: no bulk movement; Convection: fluid moves |
| Latent heat of fusion | Latent heat of vaporisation | Fusion: 334 kJ/kg; Vaporisation: 2260 kJ/kg (much higher) |
| Sublimation | Evaporation | Sublimation: solid→gas directly; Evaporation: liquid→gas |
| Boiling | Evaporation | Boiling: throughout liquid at specific T; Evaporation: surface only, any T |
| Entropy | Energy | Entropy = disorder; Energy = capacity to do work |

---

## 14. Exam Traps

> ⚠️ **TRAP 1:** Water is MOST DENSE at **4°C**, not at 0°C or 100°C. Below 4°C, water expands as it cools (anomalous).

> ⚠️ **TRAP 2:** Ice floats because it is LESS dense than water. Density of ice < Density of water.

> ⚠️ **TRAP 3:** During melting/boiling, temperature does NOT change even though heat is being added (latent heat absorbed without temperature change).

> ⚠️ **TRAP 4:** Steam burns are MORE severe than hot water burns at the same 100°C because steam releases an EXTRA 2260 kJ/kg latent heat upon condensing.

> ⚠️ **TRAP 5:** Radiation does NOT require a medium — it is the ONLY mode that works in vacuum (explains how we get heat from the sun).

> ⚠️ **TRAP 6:** At high altitudes, water boils at BELOW 100°C (not above) due to lower pressure.

> ⚠️ **TRAP 7:** Absolute zero = 0 K = −273.15°C — it is NEVER attainable (Third Law).

> ⚠️ **TRAP 8:** Mercury thermometers are NOT used for very low temperatures because mercury freezes at −38.8°C. Alcohol thermometers are used for low temperatures.

---

## 15. Must-Remember Points

- Temperature scales: 0°C = 273 K = 32°F; 100°C = 373 K = 212°F
- Absolute zero = 0 K = −273.15°C (unattainable)
- −40°C = −40°F (only point scales coincide)
- Specific heat of water = 4200 J/kg·K (highest among common substances)
- Mercury has LOWEST specific heat among liquids = 140 J/kg·K
- Anomalous expansion: water MOST DENSE at 4°C; ice floats
- Latent heat of vaporisation >> latent heat of fusion for water
- Modes: Conduction (solid), Convection (fluid), Radiation (no medium)
- Radiation = fastest; travels at speed of light; only mode in vacuum
- Laws: 0th = thermometer basis; 1st = energy conservation; 2nd = entropy; 3rd = absolute zero
- Pressure cooker: higher P → higher BP → faster cooking
- High altitude: lower P → lower BP → slower cooking

---

## 16. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  HEAT & THERMODYNAMICS — QUICK REVISION              ║
╠══════════════════════════════════════════════════════╣
║  K = °C + 273 | 0°C=273K | 100°C=373K               ║
║  −40°C = −40°F (only common point)                   ║
║  Absolute zero = 0K = −273.15°C                      ║
║  Q = mcΔT | Q = mL (latent: no temp change)         ║
║  Water: c = 4200 J/kg·K (highest)                    ║
║  Mercury: c = 140 J/kg·K (lowest liquid)             ║
║  Water max density at 4°C (ice floats)               ║
║  Modes: Conduction→solid | Convection→fluid           ║
║         Radiation→no medium (fastest, vacuum OK)     ║
║  Pressure cooker: ↑P → ↑BP → faster cooking         ║
║  High altitude: ↓P → ↓BP → slower cooking           ║
║  0th Law=thermometer | 1st=energy | 2nd=entropy      ║
╚══════════════════════════════════════════════════════╝
```

---

## 17. Last-Minute Revision Sheet

```
✅ 0°C = 273K = 32°F | 100°C = 373K = 212°F
✅ Body temp: 37°C = 310 K = 98.6°F
✅ Absolute zero = 0 K = -273.15°C
✅ −40°C = −40°F (only equal point in C and F scales)
✅ Q = mcΔT | c_water = 4200 | c_mercury = 140
✅ Q = mL (during phase change, T constant)
✅ L_vaporisation (2260 kJ/kg) >> L_fusion (334 kJ/kg)
✅ Water most dense at 4°C; ice floats (less dense)
✅ Conduction: solids; Convection: fluids; Radiation: no medium
✅ Radiation = only mode in vacuum; fastest (speed of light)
✅ Pressure cooker: ↑P → ↑BP | Mountain: ↓P → ↓BP
✅ Steam burn > hot water burn (releases latent heat)
✅ Carnot efficiency = 1 − T_cold/T_hot (always < 100%)
```
