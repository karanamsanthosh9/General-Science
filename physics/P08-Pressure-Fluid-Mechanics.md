# P08 — Pressure & Fluid Mechanics ⭐ Priority 2

> **Exam Importance:** Pascal's Law, Archimedes' Principle, Bernoulli's Principle, and atmospheric pressure are all directly examined. Applications (hydraulic brakes, ships floating, aeroplane lift) are conceptual favourites.

**Cross-links:** [P07 Gravitation](P07-Gravitation.md) · [P03 Heat](P03-Heat-Thermodynamics.md) · [C08 States of Matter](../Chemistry/C08-States-of-Matter-Gases.md)

---

## 1. Pressure

```
Pressure P = F/A
```
- F = force (N), A = area (m²)
- Unit: **Pascal (Pa)** = N/m²
- Other units: bar, atm, mmHg (Torr)

**Conversions:**
```
1 atm = 101,325 Pa = 101.325 kPa
1 atm = 760 mmHg = 760 Torr
1 bar = 100,000 Pa = 10⁵ Pa
1 atm ≈ 1.013 bar
```

**Why knife has sharp edge?** Smaller area → larger pressure with same force.
**Why snowshoes have large area?** More area → less pressure → less sinking.

---

## 2. Hydrostatic Pressure

```
P_hydro = ρgh
```
- ρ = density of liquid (kg/m³)
- g = 9.8 m/s²
- h = depth below surface (m)

**Key Points:**
- Pressure depends on **depth** and **fluid density**, NOT on shape or volume of container
- Pressure acts equally in all directions at a given depth (**Pascal's paradox**)
- A dam needs to be thicker at the bottom (higher pressure at greater depth)

---

## 3. Pascal's Law

> *"Pressure applied to an enclosed fluid is transmitted equally and undiminished in all directions throughout the fluid."*

```
P₁ = P₂    (in a connected fluid at the same level)
F₁/A₁ = F₂/A₂
```

**Applications of Pascal's Law:**

| Application | Principle | Working |
|------------|---------|---------|
| **Hydraulic lift** (car lift in garage) | Pascal's Law | Small force on small piston → large force on large piston |
| **Hydraulic brakes** | Pascal's Law | Brake pedal pressure transmitted to all wheels equally |
| **Hydraulic press** | Pascal's Law | Press paper, sugar cane |
| **Hydraulic jack** | Pascal's Law | Lift heavy loads with small effort |

**Hydraulic machines:**
```
F₁/A₁ = F₂/A₂
→ Large area (A₂) → Large force (F₂) with small input (F₁ on A₁)
Mechanical advantage = A₂/A₁
```

---

## 4. Archimedes' Principle

> *"When a body is partially or fully immersed in a fluid, it experiences an upward buoyant force equal to the weight of the fluid displaced by it."*

```
Buoyant force F_b = ρ_fluid × V_submerged × g
                  = Weight of displaced fluid
```

**Conditions for Floating:**

| Condition | Outcome |
|-----------|---------|
| Density of body < Density of fluid | Floats (partially submerged) |
| Density of body = Density of fluid | Suspended (neutral buoyancy) |
| Density of body > Density of fluid | Sinks |

**Applications of Archimedes' Principle:**

| Application | How it works |
|------------|-------------|
| Ship floats despite being steel | Ship is hollow — overall density < water density |
| Submarine dives/rises | Ballast tanks filled with water (sinks) or air (rises) |
| Hot air balloon | Hot air is less dense — buoyancy > weight |
| Hydrometer | Measures density of liquids (sinks more in less dense liquid) |
| Ice floats on water | Density of ice < density of water |
| Dead Sea float | High salt content → high density → high buoyancy |
| Plimsoll line on ships | Maximum safe loading limit marked on hull |

---

## 5. Bernoulli's Principle

> *"For an ideal fluid in steady flow, the sum of pressure energy, kinetic energy, and potential energy per unit volume is constant."*

```
P + ½ρv² + ρgh = constant
```

**Simplified (same height):**
```
P + ½ρv² = constant
→ Higher velocity = Lower pressure
→ Lower velocity = Higher pressure
```

**Applications of Bernoulli's Principle:**

| Application | How it works | PYQ |
|------------|-------------|-----|
| **Aeroplane lift** | Air moves faster over curved top wing → lower pressure above → net upward force | 🔥 |
| **Ball curving (Magnus effect)** | Cricket ball swings due to pressure difference | ⭐ |
| **Venturi meter** | Measures fluid flow rate (narrow section → low pressure) | ⭐ |
| **Carburetor** | Fast air flow → low pressure → petrol drawn in | ⭐ |
| **Atomizer/Perfume sprayer** | Fast air → low pressure draws liquid up | ⭐ |
| **Bunsen burner** | Fast gas flow draws air in | 📘 |

---

## 6. Surface Tension

- **Definition:** Property of liquid surface that tends to minimize its surface area (acts like a stretched elastic membrane)
- Unit: N/m
- Caused by cohesive forces between liquid molecules

**Phenomena due to surface tension:**
- Water drops are spherical (minimum surface area for given volume)
- Insects walk on water (surface tension supports them)
- Soap bubbles form spheres
- Meniscus in tubes (water concave; mercury convex)
- Rising of water in capillary tube (capillarity)

**Effect of temperature:** Surface tension **decreases** with increase in temperature (adding hot water to greasy plate → surface tension reduced, grease removed)

**Detergent action:** Detergents reduce surface tension → water spreads and penetrates fabrics better

---

## 7. Viscosity

- **Definition:** Property of fluids that resists flow; internal friction within fluid
- **High viscosity:** Thick fluids (honey, oil) — slow flow
- **Low viscosity:** Thin fluids (water, alcohol) — fast flow
- **Effect of temperature:** Viscosity of liquids **decreases** with temperature (honey flows easier when warm); for gases it **increases** with temperature

**Stokes' Law:**
```
F_viscous = 6πηrv
```
(Force on a sphere moving through viscous fluid)

---

## 8. Atmospheric Pressure

```
Standard atmospheric pressure:
1 atm = 101,325 Pa = 760 mmHg = 1013.25 mbar
```

- **Measured by:** Barometer (mercury barometer invented by Torricelli)
- **At sea level:** 1 atm
- **Decreases with altitude** (less air column above)
- **Weather forecasting:** High pressure = clear weather; Low pressure = rain/storm

---

## 9. Exam Traps

> ⚠️ **TRAP 1:** Pascal's Law says pressure is transmitted EQUALLY in all directions — NOT just downward.

> ⚠️ **TRAP 2:** A ship floats not because it is light, but because its AVERAGE DENSITY (hollow structure + air inside) is less than water.

> ⚠️ **TRAP 3:** Buoyant force = weight of DISPLACED fluid, NOT weight of the object.

> ⚠️ **TRAP 4:** Bernoulli's principle: FAST fluid = LOW pressure (NOT high pressure). Counter-intuitive but crucial.

> ⚠️ **TRAP 5:** Atmospheric pressure is NOT zero at sea level — it is 101,325 Pa = 1 atm. It decreases as we go up.

---

## 10. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  PRESSURE & FLUID MECHANICS — QUICK REVISION         ║
╠══════════════════════════════════════════════════════╣
║  P = F/A [Pascal] | Hydrostatic P = ρgh             ║
║  1 atm = 101325 Pa = 760 mmHg                        ║
║  Pascal's Law → hydraulic brakes/lift/press          ║
║  Archimedes: Buoyancy = weight of displaced fluid   ║
║  Float: body density < fluid density                 ║
║  Bernoulli: fast fluid = low pressure (aeroplane)    ║
║  Viscosity: liquid decreases with T; gas increases   ║
║  Surface tension: decreases with T; detergent lowers ║
║  Dead Sea: high salt density → float easily          ║
╚══════════════════════════════════════════════════════╝
```
