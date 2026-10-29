# P02 — Work, Energy & Power 🔥 Priority 1

> **Exam Importance:** Work-Energy-Power is a guaranteed chapter in every competitive exam. Formulas W=Fd·cosθ, KE=½mv², PE=mgh, Conservation of Energy, power units, and kWh conversions are directly tested. Conceptual traps (coolie carrying load, satellite work = 0) appear repeatedly.

**Cross-links:** [P01 Motion](P01-Motion-Laws-of-Motion.md) · [P03 Heat-Thermodynamics](P03-Heat-Thermodynamics.md) · [P07 Gravitation](P07-Gravitation.md)

---

## 1. Chapter Importance Analysis

| Exam | Avg Questions | Type |
|------|--------------|------|
| RRB NTPC | 2–3 | Formula-based + Conceptual |
| RRB JE | 2–3 | Numerical + Conceptual |
| SSC CGL | 2–3 | Conceptual MCQ |
| SSC JE | 3–4 | Numerical + Application |
| APPSC AEE | 2–3 | Conceptual + Numerical |

---

## 2. PYQ Trend Analysis

| Topic | Frequency | Notes |
|-------|-----------|-------|
| Work done when force ⊥ displacement = 0 | Very High 🔥 | Conceptual — coolie, satellite |
| KE = ½mv² numericals | High ⭐ | Direct formula application |
| Conservation of mechanical energy | High ⭐ | Conceptual + numerical |
| 1 HP = 746 W | Very High 🔥 | Direct fact question |
| 1 kWh in Joules | Very High 🔥 | Conversion question |
| Power = Work/time applications | High ⭐ | Rate of doing work |
| Elastic vs inelastic collision | Moderate 📘 | Conceptual |
| Efficiency formula | Moderate 📘 | Machine efficiency |

---

## 3. Work

### 3.1 Definition
Work is done when a force causes displacement of a body in the direction of the force.

```
W = F · d · cosθ
```
- F = applied force (N)
- d = displacement (m)
- θ = angle between force and displacement
- Unit: **Joule (J)** in SI; **Erg** in CGS
- 1 Joule = 1 N·m = 10⁷ erg

### 3.2 When is Work Done Zero?

| Condition | θ | cosθ | Reason |
|-----------|---|------|--------|
| Force ⊥ displacement | 90° | 0 | No component of force along motion |
| No displacement | — | — | Body doesn't move |
| Force = 0 | — | — | Nothing to do work |

**Classic PYQ Zero-Work Examples:**

| Situation | Why Work = 0 |
|-----------|-------------|
| Coolie carrying load on head walks horizontally | Force on load is vertical (upward); displacement is horizontal → θ=90° → W=0 |
| Satellite moving in circular orbit | Gravity is centripetal (toward centre); velocity is tangential (⊥ to gravity) → W=0 |
| Holding a heavy book stationary | Displacement = 0 → W = 0 |
| Earth revolving around sun (approximately) | Circular orbit → F⊥v at all points |
| Person pushing a wall that doesn't move | Displacement = 0 |

### 3.3 Positive, Negative, and Zero Work

| Type | Condition | Example |
|------|-----------|---------|
| Positive work | Force and displacement in same direction (θ < 90°) | Pushing a box forward |
| Negative work | Force and displacement in opposite direction (θ > 90°, e.g. 180°) | Friction opposing motion |
| Zero work | θ = 90° or no displacement | Coolie, satellite |

---

## 4. Energy

### 4.1 Definition
Energy is the capacity to do work.
- Unit: **Joule (J)**
- Energy is a **scalar** quantity

### 4.2 Kinetic Energy (KE)
Energy of a body due to its motion.

```
KE = ½mv²
KE = p²/(2m)       (where p = momentum)
p = √(2m·KE)
```

**Key Relations:**
- If speed is doubled → KE becomes 4 times (KE ∝ v²)
- If mass is doubled → KE becomes 2 times (KE ∝ m)
- A body at rest: KE = 0 (but may have PE)
- KE is always **non-negative** (v² is always positive)

### 4.3 Potential Energy (PE)
Energy stored in a body due to its position or configuration.

**Gravitational PE:**
```
PE = mgh
```
- m = mass (kg), g = 9.8 m/s², h = height above reference (m)
- PE increases as height increases
- PE = 0 at the reference level (usually ground)

**Elastic PE:**
```
PE = ½kx²
```
- k = spring constant (N/m)
- x = compression or extension of spring (m)

### 4.4 Other Forms of Energy

| Form | Description | Example |
|------|-------------|---------|
| Thermal energy | Energy due to random motion of particles | Hot water |
| Chemical energy | Stored in chemical bonds | Food, fuel, battery |
| Electrical energy | Energy due to flow of charges | Electricity supply |
| Nuclear energy | Energy in atomic nucleus | Nuclear reactor, sun |
| Sound energy | Energy in pressure waves | Vibrating tuning fork |
| Light energy | Energy in electromagnetic waves | Sunlight, lamp |

---

## 5. Law of Conservation of Energy

> *"Energy can neither be created nor destroyed; it can only be converted from one form to another. The total energy of an isolated system remains constant."*

### 5.1 Mechanical Energy Conservation

In absence of friction/air resistance:
```
KE + PE = Constant (Total Mechanical Energy)
```

**Verification: Ball thrown upward**

| Position | KE | PE | Total |
|---------|----|----|-------|
| Bottom (at throw) | Maximum | Zero | E |
| Middle | Half E | Half E | E |
| Top (max height) | Zero | Maximum | E |
| Bottom (on return) | Maximum | Zero | E |

### 5.2 Energy Conversions (PYQ Favourites)

| Device/Process | Energy Conversion |
|----------------|-----------------|
| Electric motor | Electrical → Mechanical |
| Electric generator | Mechanical → Electrical |
| Battery (discharging) | Chemical → Electrical |
| Battery (charging) | Electrical → Chemical |
| Solar cell | Light → Electrical |
| Bulb (incandescent) | Electrical → Light + Heat |
| Microphone | Sound → Electrical |
| Loudspeaker | Electrical → Sound |
| Steam engine | Heat → Mechanical |
| Nuclear reactor | Nuclear → Heat → Electrical |
| Sun | Nuclear (fusion) → Light + Heat |
| Hydroelectric dam | PE of water → Electrical |
| Windmill | KE of wind → Electrical |

---

## 6. Power

### 6.1 Definition
Rate of doing work or rate of energy transfer.

```
P = W/t
P = F·v         (for constant force and velocity)
P = ΔE/Δt
```
- Unit: **Watt (W)** in SI = J/s
- Larger unit: **kilowatt (kW)** = 1000 W; **Megawatt (MW)** = 10⁶ W

### 6.2 Horsepower

```
1 Horse Power (HP) = 746 W ≈ 750 W
1 Metric HP = 735.5 W
```

> **Exam note:** When a question says "HP", use 746 W. "Metric HP" uses 735.5 W.

### 6.3 Commercial Unit of Electrical Energy

```
1 Unit of electricity = 1 kWh (kilowatt-hour)
1 kWh = 1000 W × 3600 s = 3.6 × 10⁶ J = 3.6 MJ
```

**Electricity bill example:**
- A 100 W bulb running for 10 hours consumes = 100 × 10 = 1000 Wh = 1 kWh = 1 unit

---

## 7. Efficiency

```
Efficiency η = (Useful output energy / Total input energy) × 100%
             = (Output power / Input power) × 100%
```

- Efficiency is always ≤ 100%
- A perfectly efficient machine would have η = 100% (impossible due to friction, heat loss)
- Ideal machines: η = 100% (theoretical only)

---

## 8. Important Unit Conversions

| Quantity | Conversion |
|---------|-----------|
| 1 kWh | 3.6 × 10⁶ J |
| 1 calorie (cal) | 4.18 J |
| 1 kilocalorie (kcal) | 4186 J |
| 1 Horse Power | 746 W |
| 1 Metric HP | 735.5 W |
| 1 electron-volt (eV) | 1.6 × 10⁻¹⁹ J |
| 1 erg | 10⁻⁷ J |
| 1 Joule | 10⁷ erg |

---

## 9. Work-Energy Theorem

> *"The net work done on a body equals the change in its kinetic energy."*

```
W_net = ΔKE = ½mv² − ½mu²
W_net = KE_final − KE_initial
```

**Applications:**
- A car accelerated by engine — net work = increase in KE
- Brakes applied — friction does negative work → KE decreases
- Ball thrown up — gravity does negative work → KE decreases (PE increases)

---

## 10. Solved Numericals

### Numerical 1
**Q:** A force of 100 N acts on an object and moves it 5 m in the direction of force. Find the work done.
```
W = Fd·cosθ = 100 × 5 × cos0° = 100 × 5 × 1 = 500 J
```

### Numerical 2
**Q:** A body of mass 10 kg is moving at 6 m/s. Find its kinetic energy.
```
KE = ½mv² = ½ × 10 × 36 = 180 J
```

### Numerical 3
**Q:** A 5 kg ball is raised to a height of 10 m. Find its potential energy. (g = 10 m/s²)
```
PE = mgh = 5 × 10 × 10 = 500 J
```

### Numerical 4
**Q:** A machine does 6000 J of work in 2 minutes. Find its power.
```
P = W/t = 6000 / (2 × 60) = 6000 / 120 = 50 W
```

### Numerical 5
**Q:** A 500 W motor lifts a 50 kg load. Find the velocity with which it lifts the load. (g = 10 m/s²)
```
P = F·v = mg·v
500 = 50 × 10 × v
v = 500 / 500 = 1 m/s
```

### Numerical 6
**Q:** A ball is dropped from rest from a height of 20 m. Find its KE just before hitting ground. (g = 10 m/s²)
```
PE at top = mgh = m × 10 × 20 = 200m J
By conservation of energy: KE at bottom = PE at top = 200m J
If m = 1 kg → KE = 200 J
```

### Numerical 7
**Q:** How many units (kWh) of electricity does a 1.5 kW air conditioner consume in 8 hours?
```
Energy = Power × Time = 1.5 kW × 8 h = 12 kWh = 12 units
```

---

## 11. Shortcut Tricks & Memory Techniques

> **"Work COPS OUT at 90°"** — when force is perpendicular to displacement, cosθ = cos90° = 0, so W = 0.

> **"KE = Half Mass Velocity Squared"** — ½mv² — the ½ never goes away.

> **"Conservation = INVARIANT"** — total mechanical energy stays constant when no friction.

> **"Power = Speedy Work"** — Power = W/t; faster work = more power.

> **"746 = HP"** — "7-4-6 defined by James Watt himself."

> **"1 unit = 1 kWh = 3.6 × 10⁶ J"** — the electricity meter measures kWh.

---

## 12. Frequently Confused Concepts

| Concept A | Concept B | Key Difference |
|-----------|-----------|----------------|
| Work | Energy | Work = transfer of energy; Energy = stored capacity to do work |
| Power | Energy | Power = rate of doing work; Energy = total work done |
| KE | PE | KE = energy of motion (depends on v); PE = energy of position (depends on h or x) |
| Watt | Watt-hour | Watt = unit of power (rate); Watt-hour = unit of energy (rate × time) |
| Joule | Calorie | Both energy units; 1 cal = 4.18 J |
| Elastic collision | Inelastic | Elastic: KE conserved; Inelastic: KE not fully conserved |
| Efficiency | Ideal machine | Efficiency ≤ 100%; ideal machine = 100% efficiency (theoretical) |

---

## 13. Exam Traps

> ⚠️ **TRAP 1: Coolie work** — A coolie carrying a load on his head while walking horizontally does ZERO work against gravity. The force (weight) is vertical; displacement is horizontal. W = Fd·cos90° = 0.

> ⚠️ **TRAP 2: Satellite** — A satellite in circular orbit does ZERO work as gravity (centripetal force) is always perpendicular to velocity.

> ⚠️ **TRAP 3: KE negative** — KE is ALWAYS non-negative (v² ≥ 0). It cannot be negative.

> ⚠️ **TRAP 4: Energy created** — Energy is NEVER created or destroyed. It only converts. A perpetual motion machine is IMPOSSIBLE.

> ⚠️ **TRAP 5: Horsepower** — 1 HP = 746 W, NOT 1000 W. 1 kW = 1000 W.

> ⚠️ **TRAP 6: Double the speed** — If speed doubles, KE becomes 4 times (KE ∝ v²), not 2 times.

> ⚠️ **TRAP 7: 1 kWh** — 1 kWh = 3.6 × 10⁶ J. The "unit" on your electricity bill is kWh, not kW.

---

## 14. Must-Remember Points

- W = Fd·cosθ — Zero when F ⊥ d (θ = 90°)
- KE = ½mv²; doubles if mass doubles; quadruples if speed doubles
- PE = mgh (gravitational); PE = ½kx² (elastic/spring)
- Conservation: KE + PE = constant (no friction)
- Work-energy theorem: W_net = ΔKE
- Power = W/t = F·v [Watt]
- 1 HP = 746 W
- 1 kWh = 3.6 × 10⁶ J
- 1 cal = 4.18 J
- Efficiency = (Output/Input) × 100% ≤ 100%

---

## 15. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  WORK, ENERGY & POWER — QUICK REVISION               ║
╠══════════════════════════════════════════════════════╣
║  W = Fd·cosθ → zero when F⊥d (coolie, satellite)    ║
║  KE = ½mv² | PE = mgh | Elastic PE = ½kx²           ║
║  KE+PE = constant (no friction: conservation)        ║
║  Work-Energy Theorem: W_net = ΔKE                    ║
║  Power P = W/t = F·v [Watt]                          ║
║  1 HP = 746 W | 1 kWh = 3.6×10⁶ J                   ║
║  1 calorie = 4.18 J | 1 kcal = 4186 J               ║
║  Efficiency = (Output/Input) × 100%                  ║
║  Speed doubles → KE becomes 4× (not 2×)              ║
║  Energy conversions: motor=elec→mech; gen=mech→elec  ║
╚══════════════════════════════════════════════════════╝
```

---

## 16. Last-Minute Revision Sheet

```
✅ W = Fd·cosθ | Zero: coolie (vertical F, horizontal d), satellite
✅ KE = ½mv² | PE = mgh | Total ME = KE + PE = constant
✅ Speed doubles → KE × 4 | Mass doubles → KE × 2
✅ 1 HP = 746 W | 1 kWh = 3.6 × 10⁶ J | 1 cal = 4.18 J
✅ Power = W/t = F·v [Watt]
✅ Efficiency = (useful output/input) × 100% ≤ 100%
✅ W-E Theorem: Net work done = change in KE
✅ Energy forms: KE, PE, thermal, chemical, nuclear, electrical
✅ Energy converts; never created/destroyed
✅ Elastic collision: both momentum AND KE conserved
✅ Inelastic: only momentum conserved
```

---

## 17. Concept Map

```
ENERGY
├── Kinetic Energy: KE = ½mv²
├── Potential Energy: PE = mgh (gravity), ½kx² (spring)
├── Other: thermal, chemical, nuclear, electrical, sound, light
└── Conservation: KE+PE=const (no friction)
    └── With friction: ME decreases (converts to heat)

WORK
├── W = Fd·cosθ
├── Zero: θ=90° (F⊥d), no displacement, no force
├── Positive: F same direction as d
└── Negative: F opposite to d (friction)

POWER
├── P = W/t = F·v [Watt]
├── 1 HP = 746 W
└── Commercial energy: kWh (1 kWh = 3.6×10⁶ J)

ENERGY CONVERSIONS
├── Motor: Electrical → Mechanical
├── Generator: Mechanical → Electrical
├── Battery: Chemical ↔ Electrical
├── Solar cell: Light → Electrical
└── Nuclear reactor: Nuclear → Heat → Electrical
```
