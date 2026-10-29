# P07 — Gravitation ⭐ Priority 2

> **Exam Importance:** Gravitation provides direct questions on universal law, variation of g, escape velocity, orbital velocity, and weightlessness. G vs g distinction is a classic exam trap.

**Cross-links:** [P01 Motion](P01-Motion-Laws-of-Motion.md) · [P02 Work-Energy](P02-Work-Energy-Power.md) · [P08 Pressure](P08-Pressure-Fluid-Mechanics.md)

---

## 1. PYQ Trend Analysis

| Topic | Frequency |
|-------|-----------|
| G vs g distinction | Very High 🔥 |
| Variation of g with location | Very High 🔥 |
| Escape velocity (11.2 km/s) | High ⭐ |
| g on moon = g_earth/6 | High ⭐ |
| Weightlessness concept | High ⭐ |
| Kepler's Laws | Moderate 📘 |

---

## 2. Universal Law of Gravitation

> *"Every particle of matter attracts every other particle with a force that is directly proportional to the product of their masses and inversely proportional to the square of the distance between them."*

```
F = G × m₁ × m₂ / r²
```
- F = gravitational force (N)
- G = Universal Gravitational Constant = **6.67 × 10⁻¹¹ N·m²/kg²**
- m₁, m₂ = masses of the two bodies (kg)
- r = distance between their centres (m)

**Key Properties of G:**
- Universal constant — same everywhere in universe
- Very small value — gravitational force is very weak
- Determined by Henry Cavendish (1798)

---

## 3. Acceleration Due to Gravity (g)

```
g = GM/R²

At Earth's surface: g = 9.8 m/s² ≈ 10 m/s²
```
- M = mass of Earth = 6 × 10²⁴ kg
- R = radius of Earth = 6.4 × 10⁶ m

### 3.1 G vs g — Key Comparison

| Property | G (Universal constant) | g (Local acceleration) |
|---------|----------------------|----------------------|
| Full name | Universal Gravitational Constant | Acceleration due to gravity |
| Value | 6.67 × 10⁻¹¹ N·m²/kg² | 9.8 m/s² (at Earth's surface) |
| Varies? | NO — same everywhere | YES — varies with location |
| Units | N·m²/kg² | m/s² |

---

## 4. Variation of g

### 4.1 Variation with Altitude (Height above Earth's surface)

```
g_h = g × R²/(R+h)²
g_h = g(1 − 2h/R)   for h << R
```
- **g decreases as height increases**
- At infinite distance from Earth: g = 0

### 4.2 Variation with Depth below Earth's surface

```
g_d = g(1 − d/R)
```
- **g decreases as depth increases**
- At the **centre of Earth: g = 0** (gravitational pull equal from all directions)

### 4.3 Variation with Latitude

| Location | g value | Reason |
|---------|---------|--------|
| Poles | Maximum g | Closer to Earth's centre (Earth is oblate — flatter at poles) |
| Equator | Minimum g | Farthest from Earth's centre + centrifugal effect |

> **Earth is oblate spheroid** — flattened at poles, bulging at equator. Equatorial radius > Polar radius by ~21 km.

### 4.4 Summary Table

| Condition | Effect on g |
|-----------|------------|
| Going to higher altitude | g decreases |
| Going to deeper depth | g decreases |
| Going from equator to poles | g increases |
| Going to moon | g = g_earth/6 ≈ 1.63 m/s² |
| At Earth's centre | g = 0 |

---

## 5. Mass and Weight

| Property | Mass | Weight |
|---------|------|--------|
| Definition | Measure of matter in a body | Gravitational force on a body |
| Formula | — | W = mg |
| Unit | kg (kilogram) | N (Newton) |
| Scalar/Vector | Scalar | Vector |
| Changes with location? | NO (constant everywhere) | YES (depends on g) |
| On moon | Same as on Earth | W_moon = mg_moon = mg/6 |
| In space | Same | 0 (weightless) |

---

## 6. Escape Velocity

> The minimum velocity required for an object to escape from Earth's gravitational field (without further propulsion).

```
v_escape = √(2gR) = √(2GM/R)
```

**For Earth:**
```
v_escape = √(2 × 9.8 × 6.4 × 10⁶) ≈ 11.2 km/s
```

| Body | Escape Velocity |
|------|----------------|
| Earth | 11.2 km/s |
| Moon | 2.4 km/s |
| Jupiter | 59.5 km/s |
| Sun | 620 km/s |

> **Escape velocity > orbital velocity** for any given planet.

---

## 7. Orbital Velocity

> Velocity required for a satellite to maintain a circular orbit.

```
v_orbital = √(gR) = √(GM/R)
```

**Relation:**
```
v_escape = √2 × v_orbital
```

**For Earth:**
```
v_orbital = √(9.8 × 6.4 × 10⁶) ≈ 7.9 km/s
```

---

## 8. Satellites and Weightlessness

### 8.1 Geostationary Satellites

- Orbit at height ~36,000 km above equator
- Period = 24 hours (same as Earth's rotation)
- Appears stationary with respect to Earth
- **Uses:** TV broadcasting, weather forecasting, communication
- **Examples:** INSAT series (India)

### 8.2 Polar Satellites

- Orbit over poles
- Period = ~1.5–2 hours
- **Uses:** Weather monitoring, spy satellites, resource mapping
- **Example:** IRS (Indian Remote Sensing satellites)

### 8.3 Weightlessness

- In a freely falling system (satellite in orbit = continuously falling toward Earth), objects appear weightless
- **Not because gravity = 0** — gravity still acts (that's what keeps satellite in orbit)
- Weight = apparent weight = 0 (no normal force to measure)
- **Astronauts are weightless in orbit** — not because they are "far from Earth" but because they are in free fall

---

## 9. Kepler's Laws of Planetary Motion

| Law | Statement |
|-----|-----------|
| **First (Law of Orbits)** | Every planet orbits the sun in an **elliptical orbit** with the sun at one focus |
| **Second (Law of Areas)** | A line joining planet to sun sweeps **equal areas in equal times** (planet moves faster when closer to sun) |
| **Third (Law of Periods)** | T² ∝ a³ (square of period ∝ cube of semi-major axis) |

---

## 10. Tides

- **Caused by:** Gravitational pull of Moon (primarily) and Sun on Earth's oceans
- **Spring tides:** Sun, Moon, Earth aligned (new/full moon) → highest tides (strongest pull)
- **Neap tides:** Sun-Moon at 90° to Earth (quarter moon) → smallest tidal range

---

## 11. Exam Traps

> ⚠️ **TRAP 1:** G is UNIVERSAL and CONSTANT — it does NOT change with location. g CHANGES with location.

> ⚠️ **TRAP 2:** g is MAXIMUM at poles, MINIMUM at equator — many reverse this.

> ⚠️ **TRAP 3:** g = 0 at Earth's CENTRE, not at equator.

> ⚠️ **TRAP 4:** Mass remains constant everywhere; Weight changes with g.

> ⚠️ **TRAP 5:** Weightlessness in satellites is NOT because there is no gravity — gravity is very much present (it keeps the satellite in orbit). Weightlessness is because the satellite is in free fall.

> ⚠️ **TRAP 6:** Moon's gravity = Earth's gravity / 6. Weight on moon = 1/6 of Earth weight. Mass is same.

---

## 12. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  GRAVITATION — QUICK REVISION                        ║
╠══════════════════════════════════════════════════════╣
║  F = Gm₁m₂/r² | G = 6.67×10⁻¹¹ N·m²/kg² (constant) ║
║  g = 9.8 m/s² at Earth's surface (varies)           ║
║  g: max at poles, min at equator, zero at centre     ║
║  Moon: g = g_earth/6; mass unchanged                ║
║  Escape velocity Earth = 11.2 km/s                   ║
║  Orbital velocity Earth = 7.9 km/s                   ║
║  v_escape = √2 × v_orbital                           ║
║  Geostationary: 36,000 km, 24h period               ║
║  Weightlessness = free fall (gravity still present)  ║
║  Kepler's 3rd: T² ∝ a³                               ║
╚══════════════════════════════════════════════════════╝
```
