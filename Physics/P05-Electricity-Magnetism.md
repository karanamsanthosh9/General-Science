# P05 — Electricity & Magnetism 🔥 Priority 1

> **Exam Importance:** Electricity & Magnetism is one of the most heavily tested Physics chapters, especially for RRB JE and SSC JE. Ohm's Law, series/parallel circuits, power formulas, domestic wiring, transformer principles, and magnetic effects of current all appear regularly. Unit conversion (kWh → electricity bills) is a guaranteed question type.

**Cross-links:** [P02 Work-Energy](P02-Work-Energy-Power.md) · [C09 Electrochemistry](../Chemistry/C09-Electrochemistry.md) · [P14 Semiconductors](P14-Semiconductors-Electronics.md)

---

## 1. Chapter Importance Analysis

| Exam | Avg Questions | Focus |
|------|--------------|-------|
| RRB NTPC | 3–4 | Ohm's Law, circuits, facts |
| RRB JE | 4–6 | Full breadth — circuits, machines, domestic |
| SSC CGL | 2–3 | Conceptual, facts |
| SSC JE | 4–6 | Numerical + conceptual + applications |
| APPSC AEE | 3–4 | Circuits, power, machines |

---

## 2. PYQ Trend Analysis

| Topic | Frequency |
|-------|-----------|
| Ohm's Law (V = IR) | Very High 🔥 |
| Series vs parallel circuits | Very High 🔥 |
| Domestic wiring (fuse, earthing, wire colours) | Very High 🔥 |
| P = VI = I²R = V²/R | Very High 🔥 |
| 1 unit = 1 kWh = 3.6 × 10⁶ J | Very High 🔥 |
| AC frequency in India (50 Hz), voltage (220V) | Very High 🔥 |
| Transformer (step-up/step-down) | High ⭐ |
| Electric motor vs generator | High ⭐ |
| Faraday's laws of EM induction | High ⭐ |
| Magnetic field due to current | Moderate 📘 |

---

## 3. Electric Charge & Current

### 3.1 Electric Charge

- **Charge (Q):** Property of matter that causes electrical phenomena
- Unit: **Coulomb (C)**
- Two types: Positive (proton) and Negative (electron)
- Like charges repel; unlike charges attract
- Charge on electron = −1.6 × 10⁻¹⁹ C
- Charge is conserved (total charge of an isolated system is constant)

### 3.2 Electric Current

- **Definition:** Rate of flow of electric charge
```
I = Q/t
```
- Unit: **Ampere (A)** = Coulomb/second
- Conventional current flows from + to −; electron flow from − to +
- 1 Ampere = 1 Coulomb per second

---

## 4. Ohm's Law

> *"The current flowing through a conductor is directly proportional to the potential difference across it, provided temperature and physical conditions remain constant."*

```
V = IR
I = V/R
R = V/I
```

- V = potential difference (Volt)
- I = current (Ampere)
- R = resistance (Ohm, Ω)

### 4.1 Resistance

- **Definition:** Opposition offered by a conductor to the flow of current
- Unit: **Ohm (Ω)**

```
R = ρL/A
```
- ρ = resistivity (Ω·m) — property of material
- L = length of conductor
- A = cross-sectional area

**Effect on resistance:**

| Factor | Effect on R |
|--------|------------|
| Length increases | R increases (R ∝ L) |
| Area increases | R decreases (R ∝ 1/A) |
| Temperature increases | R increases (for metals/conductors) |
| Temperature increases | R decreases (for semiconductors) |

**Resistivity (ρ) Values:**
| Material | Resistivity | Classification |
|---------|------------|---------------|
| Silver | 1.6 × 10⁻⁸ Ω·m | Best conductor |
| Copper | 1.7 × 10⁻⁸ Ω·m | Common conductor |
| Gold | 2.4 × 10⁻⁸ Ω·m | Conductor |
| Aluminium | 2.8 × 10⁻⁸ Ω·m | Conductor |
| Nichrome | 1.0 × 10⁻⁶ Ω·m | High resistance wire |
| Silicon | ~640 Ω·m | Semiconductor |
| Glass | ~10¹² Ω·m | Insulator |

### 4.2 Ohmic vs Non-Ohmic Conductors

| Type | Behaviour | Example |
|------|-----------|---------|
| Ohmic | V-I graph is straight line (R = constant) | Resistors, metal wires at constant T |
| Non-Ohmic | V-I graph is curved (R varies) | Diode, LED, bulb filament |

---

## 5. Series and Parallel Circuits

### 5.1 Series Circuit

```
R_total = R₁ + R₂ + R₃ + ...
I is same through all components
V is distributed: V_total = V₁ + V₂ + V₃
```

| Property | Series |
|---------|--------|
| Current | Same through all resistors |
| Voltage | Divides across resistors |
| Total resistance | Sum of all (increases) |
| If one fails | All components fail (whole circuit off) |
| Use | Not used for home appliances |

### 5.2 Parallel Circuit

```
1/R_total = 1/R₁ + 1/R₂ + 1/R₃ + ...
V is same across all components
I is distributed: I_total = I₁ + I₂ + I₃
```

| Property | Parallel |
|---------|----------|
| Current | Divides through branches |
| Voltage | Same across all branches |
| Total resistance | Less than smallest individual R |
| If one fails | Others continue working |
| Use | Home wiring, appliances |

### 5.3 Series vs Parallel — Master Comparison

| Feature | Series | Parallel |
|---------|--------|---------|
| Equivalent R | R₁ + R₂ (increases) | R₁R₂/(R₁+R₂) (decreases) |
| Voltage | Splits | Same across all |
| Current | Same | Splits |
| Failure effect | All fail | Others survive |
| Brightness of bulbs | Less bright | Full brightness |
| Used for | String lights (Christmas) | Home wiring ✅ |
| Battery cells — high voltage | Series | — |
| Battery cells — high current | — | Parallel |

---

## 6. Electrical Power and Energy

### 6.1 Power Formulas

```
P = VI = I²R = V²/R
```

- P = power (Watt)
- V = voltage (Volt)
- I = current (Ampere)
- R = resistance (Ohm)

### 6.2 Electrical Energy

```
E = Pt = VIt = I²Rt
```
- Unit: **Joule (J)** or **kWh (kilowatt-hour)**
- **1 kWh = 1 unit of electricity = 3.6 × 10⁶ J**

### 6.3 Commercial Calculations

**Example:** A 60 W bulb runs for 5 hours:
```
Energy = 60 W × 5 h = 300 Wh = 0.3 kWh = 0.3 units
```

### 6.4 Heating Effect of Current (Joule's Law)

```
H = I²Rt    (Joule's heating)
```
- Heat generated is proportional to I², R, and t
- **Applications:** Electric heater, electric iron, fuse, incandescent bulb, toaster
- **Fuse works on Joule's heating** — excess current melts the fuse wire

---

## 7. Domestic Electric Wiring

### 7.1 Wiring System in India

- **AC supply:** 220 V, 50 Hz
- **Three-wire system:** Live (Phase), Neutral, Earth

### 7.2 Wire Colours

| Wire | Old Colour (India) | New Colour (IS:694) |
|------|-------------------|-------------------|
| Live (Phase) | **Red** | **Brown** |
| Neutral | **Black** | **Blue** |
| Earth | **Green** | **Green/Yellow** |

> **Exam Note:** Old system (Red/Black/Green) is still asked frequently in older PYQs. New system (Brown/Blue/Green) is becoming common.

### 7.3 Safety Devices

**Fuse:**
- Connected in **series** with the circuit (live wire)
- Made of **tin-lead alloy** (low melting point ~200°C)
- Melts and breaks the circuit when current exceeds rated value
- Protects against **overcurrent and short circuit**
- Must be replaced after it melts (one-time use)
- **Fuse rating:** Current at which it melts (e.g., 5A, 15A)

**MCB (Miniature Circuit Breaker):**
- Modern replacement for fuse
- **Can be reset** by flipping the switch (reusable)
- Trips automatically when current exceeds rated value
- More reliable and convenient than fuse

**Earthing (Grounding):**
- Metal body of appliance connected to earth via green wire
- In case of leakage/fault, current flows to earth (not through human body)
- **Prevents electric shock** (not short circuit)

**ELCB/RCCB (Earth Leakage/Residual Current Circuit Breaker):**
- Detects even small earth leakage currents
- Immediately trips to prevent electric shock

| Device | Function | Position in circuit |
|--------|---------|-------------------|
| Fuse | Overcurrent protection; melts | Series with live wire |
| MCB | Overcurrent protection; resets | Series |
| ELCB/RCCB | Earth fault/leakage protection | Main switch |
| Earthing | Shock prevention | Connected to appliance body |

### 7.4 Home Wiring Details

- All appliances in home are connected in **PARALLEL**
- Parallel: each appliance gets full 220V; failure of one doesn't affect others
- Each circuit has its own fuse/MCB
- **Power factor** of AC circuit (for advanced understanding)

---

## 8. Magnetic Effects of Current

### 8.1 Oersted's Discovery

- **Hans Christian Oersted (1820):** Current-carrying conductor produces a magnetic field around it
- Compass needle deflects when current flows through nearby wire
- Established connection between electricity and magnetism

### 8.2 Magnetic Field Due to Current

**Straight wire:** Circular magnetic field lines around wire (use Right-hand thumb rule)
```
Right-hand thumb rule: 
Point thumb in direction of current → fingers curl in direction of magnetic field
```

**Solenoid:** Acts like a bar magnet when current flows through it

### 8.3 Force on Current-Carrying Conductor in Magnetic Field

```
F = BIL sinθ    (force on straight wire)
F = qvB sinθ    (force on moving charge)
```

**Fleming's Left-Hand Rule (Motor Rule):**
- Forefinger = direction of magnetic field (B)
- Middle finger = direction of current (I)
- Thumb = direction of force (F) on conductor
- **Used for:** Electric motor (current+field → force)

**Fleming's Right-Hand Rule (Generator Rule):**
- Forefinger = magnetic field
- Middle finger = induced current direction
- Thumb = direction of motion of conductor
- **Used for:** Electric generator (motion+field → current)

---

## 9. Electromagnetic Induction (Faraday's Laws)

### 9.1 Faraday's Laws

**First Law:** An EMF is induced in a conductor whenever the magnetic flux through it changes.

**Second Law:** The magnitude of induced EMF is proportional to the rate of change of magnetic flux.

```
EMF = −dΦ/dt    (Faraday-Lenz law; negative sign = Lenz's law)
```

**Lenz's Law:** The induced current opposes the change that causes it (conservation of energy).

### 9.2 Electric Motor

- Converts **electrical energy → mechanical energy**
- Works on principle: **current-carrying conductor in a magnetic field experiences force**
- Uses Fleming's Left-Hand Rule
- **Components:** Armature coil, permanent magnet, commutator, brushes
- **Uses:** Fans, mixers, washing machines, electric vehicles, escalators

### 9.3 Electric Generator (Dynamo)

- Converts **mechanical energy → electrical energy**
- Works on principle: **Faraday's electromagnetic induction**
- Uses Fleming's Right-Hand Rule
- **AC generator (Alternator):** Produces alternating current
- **DC generator (Dynamo):** Produces direct current
- **Uses:** Power stations, bicycles (cycle dynamo), emergency power supply

### 9.4 Transformer

- **Function:** Changes AC voltage level (step-up or step-down)
- **Principle:** Mutual electromagnetic induction
- **Works ONLY on AC** (NOT DC — needs changing flux)

```
Vs/Vp = Ns/Np = Ip/Is

Efficiency = (Vs × Is)/(Vp × Ip) × 100%
```

- Vs = secondary voltage, Vp = primary voltage
- Ns = secondary turns, Np = primary turns

| Type | Ns/Np | Vs vs Vp | Current | Use |
|------|-------|---------|---------|-----|
| Step-up transformer | Ns > Np | Vs > Vp | Is < Ip | Power transmission (increase voltage, decrease current for less line loss) |
| Step-down transformer | Ns < Np | Vs < Vp | Is > Ip | Distribution to homes (reduce to 220V) |

> **Why high voltage for transmission?** P = I²R (power loss). High voltage → low current → less power loss in transmission lines.

---

## 10. Important Electrical Devices — PYQ Facts

| Device | Working Principle | Energy Conversion |
|--------|------------------|------------------|
| Electric motor | Current in magnetic field → force | Electrical → Mechanical |
| Generator | Motion in magnetic field → EMF | Mechanical → Electrical |
| Transformer | Mutual EM induction | AC voltage change |
| Electromagnet | Current → magnetic field | Electrical → Magnetic |
| Thermocouple | Temperature difference → EMF | Thermal → Electrical |
| LED | Semiconductor + electrical energy | Electrical → Light |
| Electric heater | Joule heating (I²R) | Electrical → Heat |
| Photoelectric cell | Light ejects electrons | Light → Electrical |

---

## 11. Solved Numericals

### Numerical 1
**Q:** A resistor of 10 Ω has a potential difference of 50 V across it. Find current and power.
```
I = V/R = 50/10 = 5 A
P = VI = 50 × 5 = 250 W
OR P = I²R = 25 × 10 = 250 W
```

### Numerical 2
**Q:** Two resistors 6 Ω and 3 Ω are connected in (a) series (b) parallel. Find equivalent resistance.
```
(a) Series: R = 6 + 3 = 9 Ω
(b) Parallel: 1/R = 1/6 + 1/3 = 1/6 + 2/6 = 3/6 = 1/2
    R = 2 Ω
```

### Numerical 3
**Q:** A 1000 W heater runs for 2 hours every day for 30 days. Find cost at Rs 5 per unit.
```
Energy = 1000 W × 2 h × 30 days = 60,000 Wh = 60 kWh = 60 units
Cost = 60 × 5 = Rs 300
```

### Numerical 4
**Q:** A step-up transformer has 200 primary turns and 1000 secondary turns. Primary voltage = 220V. Find secondary voltage.
```
Vs/Vp = Ns/Np
Vs/220 = 1000/200 = 5
Vs = 220 × 5 = 1100 V
```

### Numerical 5
**Q:** An electric iron of 1000 W is used for 2 hours. Find heat generated.
```
H = P × t = 1000 × (2 × 3600) = 7,200,000 J = 7.2 MJ
OR: Energy = 1000 W × 2 h = 2 kWh = 7.2 × 10⁶ J
```

---

## 12. Shortcut Tricks & Memory Techniques

> **"VIR man"** → V = IR (Ohm's Law). The VIR triangle: cover the one you want to find.

> **"Power PIZZA"** → P = VI = I²R = V²/R — three faces of the power formula.

> **"Series = Suffering"** → Like old Christmas lights — one bulb fails, all go dark.

> **"Parallel = PARTY"** → Each bulb/device gets full voltage and works independently. Home wiring = party mode.

> **"Fuse = Fusible link in SERIES on Live wire"** — fuse is ALWAYS on the live (phase) wire, ALWAYS in series.

> **"Motor = Mi-LEFT-Hand"** → Motor uses Left-Hand rule (M for Motor, M for your Middle finger = current).

> **"Generator = Right-Hand"** → Generator uses Right-Hand rule.

> **"Transformer = Turns ratio = Voltage ratio"** → Vs/Vp = Ns/Np.

---

## 13. Frequently Confused Concepts

| Concept A | Concept B | Distinction |
|-----------|-----------|------------|
| Current | Voltage | Current = flow of charge; Voltage = potential difference (driving force) |
| Resistance | Resistivity | Resistance = property of a component; Resistivity = property of material |
| Series | Parallel | Series: same current, voltage divides; Parallel: same voltage, current divides |
| Fuse | MCB | Fuse: one-time, melts; MCB: reusable, trips and resets |
| Motor | Generator | Motor: electrical→mechanical; Generator: mechanical→electrical |
| Transformer | Generator | Transformer: changes voltage (AC); Generator: produces electrical energy |
| EMF | Potential Difference | EMF = open circuit voltage (source); PD = voltage with current flowing |
| AC | DC | AC: alternating direction; DC: constant direction |

---

## 14. Exam Traps

> ⚠️ **TRAP 1:** Home wiring is in PARALLEL, not series. That's why one appliance failure doesn't affect others.

> ⚠️ **TRAP 2:** Fuse is connected in SERIES (not parallel) on the LIVE wire.

> ⚠️ **TRAP 3:** Transformer works ONLY on AC, NOT DC. No changing flux with DC → no induction.

> ⚠️ **TRAP 4:** MCB can be RESET (unlike fuse which must be replaced).

> ⚠️ **TRAP 5:** Earthing prevents electric SHOCK, not short circuit.

> ⚠️ **TRAP 6:** In parallel circuit, equivalent resistance is LESS than the SMALLEST individual resistance.

> ⚠️ **TRAP 7:** When speed doubles, if P = F·v → power doubles. But P = I²R doesn't depend on speed.

> ⚠️ **TRAP 8:** High voltage for power transmission REDUCES current → reduces line losses (P_loss = I²R).

> ⚠️ **TRAP 9:** Resistance of metals INCREASES with temperature; semiconductors DECREASE with temperature.

---

## 15. Must-Remember Points

- V = IR (Ohm's Law); P = VI = I²R = V²/R
- Series: R adds; same current; voltage divides
- Parallel: R reduces; same voltage; current divides
- Home wiring = PARALLEL (each appliance gets 220V)
- Fuse: series, live wire, tin-lead alloy, one-time use
- MCB: series, resettable, more reliable
- Earthing: prevents shock (green wire)
- AC India: 220V, 50 Hz
- Motor: electrical → mechanical (Left-Hand rule)
- Generator: mechanical → electrical (Right-Hand rule)
- Transformer: AC only; Ns/Np = Vs/Vp
- Step-up: increase voltage (for transmission); Step-down: decrease voltage (for homes)
- 1 unit = 1 kWh = 3.6 × 10⁶ J

---

## 16. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  ELECTRICITY & MAGNETISM — QUICK REVISION            ║
╠══════════════════════════════════════════════════════╣
║  V = IR | P = VI = I²R = V²/R                        ║
║  Series: R adds, same I, V divides                   ║
║  Parallel: R reduces, same V, I divides              ║
║  Home wiring = PARALLEL (220V to all)                ║
║  Fuse: series, live wire, tin-lead alloy             ║
║  MCB: resettable; Earthing: green wire = shock prev  ║
║  India: AC 220V, 50 Hz                               ║
║  Motor: electrical→mechanical (Left-Hand rule)       ║
║  Generator: mechanical→electrical (Right-Hand rule)  ║
║  Transformer: AC only | Ns/Np = Vs/Vp               ║
║  1 kWh = 1 unit = 3.6 × 10⁶ J                       ║
║  Best conductor: Silver > Copper > Gold > Al         ║
╚══════════════════════════════════════════════════════╝
```
