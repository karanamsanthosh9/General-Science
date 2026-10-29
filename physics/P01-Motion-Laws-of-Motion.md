# P01 — Motion, Laws of Motion & Force 🔥 Priority 1

> **Exam Importance:** This is consistently one of the top-3 Physics topics across RRB NTPC, RRB JE, SSC CGL, SSC CHSL, and APPSC AEE. Every paper has 3–5 questions from this chapter. Newton's Laws, momentum, impulse, and equations of motion generate direct marks.

**Cross-links:** [P02 Work-Energy-Power](P02-Work-Energy-Power.md) · [P07 Gravitation](P07-Gravitation.md) · [P08 Pressure-Fluid-Mechanics](P08-Pressure-Fluid-Mechanics.md)

---

## 1. Chapter Importance Analysis

| Exam | Avg Questions from This Chapter | Type |
|------|--------------------------------|------|
| RRB NTPC | 3–4 | Conceptual MCQ + 1 Numerical |
| RRB JE | 2–3 | Conceptual + formula-based |
| SSC CGL/CHSL | 2–3 | Conceptual MCQ |
| SSC JE | 2–3 | Conceptual + Numerical |
| APPSC AEE | 2–3 | Conceptual |

---

## 2. PYQ Trend Analysis

| Topic | Frequency | Recent Trend |
|-------|-----------|-------------|
| Newton's First Law — Inertia examples | Very High 🔥 | Consistently asked |
| Newton's Third Law — examples/applications | Very High 🔥 | Consistently asked |
| F = ma numerical | High ⭐ | Nearly every paper |
| Conservation of Momentum | High ⭐ | Numerical + conceptual |
| Impulse = change in momentum | High ⭐ | Formula and application |
| Projectile motion | Moderate 📘 | SSC JE and RRB JE |
| Circular motion & centripetal force | Moderate 📘 | Definition and examples |
| Equations of motion numericals | High ⭐ | 1–2 per paper |
| "Which law explains..." type | Very High 🔥 | 1 guaranteed question |

---

## 3. Scalars vs Vectors

### 3.1 Definitions

- **Scalar quantity** — has only magnitude; no direction
- **Vector quantity** — has both magnitude and direction

### 3.2 Classification Table

| Scalar | Vector |
|--------|--------|
| Distance | Displacement |
| Speed | Velocity |
| Mass | Force |
| Time | Acceleration |
| Energy | Momentum |
| Temperature | Weight |
| Work | Impulse |
| Power | Torque |
| Pressure | Electric field |

> **Exam Trap:** Work is a scalar even though F and d are vectors. Work = F · d · cosθ (dot product = scalar).

---

## 4. Types of Motion

| Type | Description | Example |
|------|-------------|---------|
| Uniform motion | Equal displacement in equal time intervals; zero acceleration | Car at constant speed on highway |
| Non-uniform motion | Unequal displacement in equal time; non-zero acceleration | Car accelerating from traffic signal |
| Rectilinear motion | Motion along a straight line | Falling stone |
| Circular motion | Motion along a circular path | Planet orbiting sun |
| Oscillatory / Vibratory | Motion to and fro about a fixed point | Pendulum |
| Rotational motion | Body rotates about its own axis | Earth spinning |
| Projectile motion | Object thrown at angle; follows parabolic path | Cricket ball, shell from gun |

---

## 5. Distance vs Displacement

| Property | Distance | Displacement |
|---------|----------|-------------|
| Definition | Total path length covered | Shortest straight-line path from start to end |
| Type | Scalar | Vector |
| Always | Positive | Can be positive, negative, or zero |
| Can be zero? | Only if no movement | Yes — if you return to starting point |
| Example | Running 400m track once = 400m | Start = End → displacement = 0 |

---

## 6. Speed vs Velocity

| Property | Speed | Velocity |
|---------|-------|---------|
| Type | Scalar | Vector |
| Formula | Distance / Time | Displacement / Time |
| Unit | m/s | m/s (with direction) |
| Average speed | Total distance / total time | Total displacement / total time |
| When = 0 | Only at rest | At rest OR when displacement = 0 (circular full turn) |

---

## 7. Acceleration

- **Definition:** Rate of change of velocity with time
- **Formula:** a = (v − u) / t
- **Unit:** m/s²
- **Deceleration / Retardation:** Negative acceleration (slowing down)
- A body moving in a circular path at **constant speed** has acceleration (direction changes) → called **centripetal acceleration**

---

## 8. Equations of Uniformly Accelerated Motion

> These three equations are the most-tested formulas in this chapter. Memorise them without error.

```
v = u + at                       ... (1)
s = ut + ½at²                    ... (2)
v² = u² + 2as                    ... (3)

Distance in nth second:
Sₙ = u + a(2n − 1)/2             ... (4)
```

Where:
- u = initial velocity (m/s)
- v = final velocity (m/s)
- a = acceleration (m/s²)
- t = time (s)
- s = displacement (m)
- n = nth second

### 8.1 Derivations (Conceptual Only)

| Equation | Eliminates | Use when |
|---------|-----------|---------|
| v = u + at | s | Given u, a, t → find v |
| s = ut + ½at² | v | Given u, a, t → find s |
| v² = u² + 2as | t | Given u, a, s → find v |
| Sₙ = u + a(2n−1)/2 | — | Distance in nth specific second |

### 8.2 Special Cases

| Condition | Result |
|-----------|--------|
| u = 0 (starts from rest) | v = at; s = ½at² |
| a = 0 (uniform motion) | v = u; s = ut |
| Free fall (a = g, u = 0) | v = gt; s = ½gt² |
| Thrown upward (a = −g) | At max height: v = 0; t_up = u/g; max height = u²/2g |

---

## 9. Newton's Laws of Motion

### 9.1 First Law — Law of Inertia

> *"Every body continues in its state of rest or of uniform motion in a straight line unless compelled by an external unbalanced force."*

**Key Concept: Inertia**
- Inertia = resistance of a body to change its state of rest or motion
- **Inertia ∝ Mass** (heavier object = more inertia)
- Inertia is a **property**, NOT a force

**Types of Inertia:**

| Type | Description | Example |
|------|-------------|---------|
| Inertia of rest | Tendency to remain at rest | Coin on card falls into glass when card is flicked |
| Inertia of motion | Tendency to continue moving | Passenger thrown forward when bus brakes suddenly |
| Inertia of direction | Tendency to continue in same direction | Mud flies off rotating wheel tangentially |

**PYQ Examples of Inertia:**
- Dust falls off carpet when beaten → inertia of rest (dust was at rest, prefers to stay at rest)
- Passenger lurches forward when bus brakes → inertia of motion
- Ball thrown inside moving train continues moving with train → inertia of motion
- Athlete runs before long jump → builds inertia of motion

### 9.2 Second Law — F = ma

> *"The rate of change of momentum of a body is directly proportional to the applied force, and takes place in the direction of the force."*

**Key Formulas:**
```
F = ma
F = Δp/Δt = m(v − u)/t
Impulse J = F × t = Δp = m(v − u)
```

**Units of Force:**
| System | Unit | Definition |
|--------|------|-----------|
| SI | Newton (N) | Force that accelerates 1 kg by 1 m/s² |
| CGS | Dyne (dyn) | Force that accelerates 1 g by 1 cm/s² |
| Conversion | 1 N = 10⁵ dyne | — |

**Impulse:**
- Impulse = Force × time = change in momentum
- **Why airbag saves lives:** Increases time of impact → reduces force on occupant (J = Ft, same J, large t → small F)
- **Why cricketers draw hands back while catching:** Increases time → reduces force of impact
- **Why thick mattress is better for falling:** Increases stopping time → reduces impact force

### 9.3 Third Law — Action-Reaction

> *"For every action, there is an equal and opposite reaction. The two forces act on different bodies simultaneously."*

**Critical Points:**
- Action and reaction are **always equal in magnitude** and **opposite in direction**
- They act on **DIFFERENT bodies** — therefore they do NOT cancel each other
- Both forces exist simultaneously

**PYQ Applications:**

| Action | Reaction | Application |
|--------|----------|-------------|
| Rocket expels gases backward (action) | Gases push rocket forward (reaction) | Rocket propulsion |
| Gun pushes bullet forward | Bullet pushes gun backward | Gun recoil |
| Swimmer pushes water backward | Water pushes swimmer forward | Swimming |
| Earth pulls ball down | Ball pulls Earth up | Gravity |
| You push wall | Wall pushes you back | Leaning on wall |
| Foot pushes ground backward | Ground pushes foot forward | Walking |

---

## 10. Law of Conservation of Momentum

> *"The total momentum of an isolated system remains constant if no external force acts on it."*

```
m₁u₁ + m₂u₂ = m₁v₁ + m₂v₂
Total initial momentum = Total final momentum
```

**Applications:**
- Rocket propulsion (gases expelled → rocket gains momentum)
- Gun recoil
- Elastic and inelastic collisions
- Newton's cradle demonstration

**Types of Collisions:**

| Type | KE conserved? | Momentum conserved? | Example |
|------|--------------|--------------------|----|
| Elastic | Yes | Yes | Billiard balls, gas molecules |
| Inelastic | No (some lost as heat) | Yes | Car crash, clay hitting wall |
| Perfectly inelastic | No (max KE lost) | Yes | Objects stick together |

---

## 11. Projectile Motion

- A body thrown at an angle to horizontal follows a **parabolic path**
- Horizontal velocity: constant (no force in horizontal direction)
- Vertical velocity: changes due to gravity (g)

```
Time of flight:    T = 2u sinθ / g
Maximum height:    H = u² sin²θ / 2g
Horizontal range:  R = u² sin2θ / g
Maximum range:     when θ = 45°
```

**Key Facts:**
- Horizontal and vertical motions are **independent** of each other
- A ball dropped from hand and a ball thrown horizontally from same height **hit the ground simultaneously** (same vertical motion)
- Range is same for angles θ and (90° − θ): e.g., 30° and 60° give the same range

---

## 12. Circular Motion

- **Uniform circular motion:** speed is constant, but direction changes → velocity changes → acceleration exists
- **Centripetal acceleration:** a = v²/r = ω²r (directed toward centre)
- **Centripetal force:** F = mv²/r (not a separate force — it is the NET force directed toward centre)
- **Centrifugal force:** Apparent outward force felt in rotating (non-inertial) frame; NOT a real force

**Examples of centripetal force:**
| Situation | What provides centripetal force |
|-----------|--------------------------------|
| Planet orbiting sun | Gravity |
| Car turning on road | Friction between tyres and road |
| Ball on string | Tension in string |
| Electron around nucleus | Electrostatic attraction |

---

## 13. Friction

- **Definition:** Force that opposes relative motion between surfaces in contact
- **Direction:** Always opposes motion (opposite to direction of motion or intended motion)

**Types of Friction:**

| Type | Description | Magnitude |
|------|-------------|-----------|
| Static friction | Acts when body is at rest; prevents motion | Highest |
| Limiting friction | Maximum value of static friction just before motion begins | — |
| Kinetic (sliding) friction | Acts when body slides over surface | Less than static |
| Rolling friction | Acts when body rolls over surface | Least |

**Order:** Static > Kinetic (sliding) > Rolling

**Coefficients:**
```
Static friction:   fs ≤ μₛN
Kinetic friction:  fk = μₖN
Where N = Normal force, μ = coefficient of friction
```

**Friction in daily life:**

| Useful friction | Harmful friction |
|----------------|-----------------|
| Walking (feet on ground) | Engine wear |
| Brakes on vehicles | Heat generation |
| Writing with pen | Energy loss in machines |
| Lighting matches | Slowing down of moving parts |

**Reducing friction:** Lubricants, ball bearings, polishing surfaces, streamlining

---

## 14. Important Formulas Summary

| Formula | Quantity | Unit |
|---------|----------|------|
| v = u + at | Final velocity | m/s |
| s = ut + ½at² | Displacement | m |
| v² = u² + 2as | Velocity-displacement | — |
| Sₙ = u + a(2n−1)/2 | Distance in nth second | m |
| F = ma | Force | Newton (N) |
| p = mv | Momentum | kg·m/s |
| J = Ft = Δp | Impulse | N·s |
| F = mv²/r | Centripetal force | N |
| fk = μₖN | Kinetic friction | N |

---

## 15. Shortcut Tricks & Memory Techniques

> **"VIA"** for equations of motion: **V**=u+at | **I**=½at² in s=ut+½at² | **A**=v²−u²=2as

> **"Inertia = IDLENESS"** — Bodies are idle (lazy), they resist change. Inertia of rest = laziness to start; Inertia of motion = laziness to stop.

> **"3rd Law = TWINS"** — Action and reaction are twin forces: equal, simultaneous, opposite, but on DIFFERENT bodies.

> **"Impulse = Saving life"** — Airbag, cushion, follow-through in cricket = increase time = decrease force.

> For numericals: Always write u, v, a, t, s and see which 3 are known, then pick the right equation.

---

## 16. Frequently Confused Concepts

| Concept A | Concept B | Key Difference |
|-----------|-----------|----------------|
| Mass | Weight | Mass = amount of matter (kg, constant everywhere); Weight = gravitational force (N, varies with g) |
| Speed | Velocity | Speed = scalar (magnitude only); Velocity = vector (magnitude + direction) |
| Distance | Displacement | Distance = total path; Displacement = shortest straight path (can be zero or negative) |
| Momentum | Impulse | Momentum = mv (state at a moment); Impulse = Δp = change in momentum (process) |
| Inertia | Mass | Inertia = the concept (tendency to resist); Mass = the quantitative measure of inertia |
| Centripetal | Centrifugal | Centripetal = real force toward centre; Centrifugal = pseudo force felt in rotating frame |
| Action force | Reaction force | Equal, opposite, simultaneous — but act on DIFFERENT bodies |
| Friction static | Friction kinetic | Static > Kinetic; static prevents motion, kinetic opposes ongoing motion |

---

## 17. Examiner Favourite Questions (PYQ-Style)

1. **Q:** Which of Newton's laws explains the working of a rocket?
   **A:** Newton's Third Law (action-reaction — gas expelled backward, rocket moves forward)

2. **Q:** A person standing in a bus is thrown forward when the bus brakes suddenly. This is due to:
   **A:** Inertia of motion (Newton's First Law)

3. **Q:** The unit of momentum in SI system is:
   **A:** kg·m/s

4. **Q:** A body of mass 5 kg is moving with velocity 10 m/s. What is its momentum?
   **A:** p = mv = 5 × 10 = 50 kg·m/s

5. **Q:** The force required to accelerate a body of mass 10 kg at 5 m/s² is:
   **A:** F = ma = 10 × 5 = 50 N

6. **Q:** Impulse is defined as:
   **A:** Change in momentum (= Force × time)

7. **Q:** Which of the following is NOT a vector?
   **A:** Speed (scalar); Velocity is a vector

8. **Q:** When a gun is fired, the gun recoils. This is explained by:
   **A:** Newton's Third Law / Conservation of momentum

9. **Q:** A cricket player moves his hands backward while catching a ball to:
   **A:** Increase the time of impact to reduce the impulsive force

10. **Q:** Friction is least for:
    **A:** Rolling motion (rolling friction < kinetic friction < static friction)

---

## 18. Common Mistakes & Exam Traps

> ⚠️ **TRAP 1:** "Inertia is a force" — WRONG. Inertia is a property of matter. It is not a force.

> ⚠️ **TRAP 2:** "Action and reaction cancel each other out" — WRONG. They act on DIFFERENT bodies, so they cannot cancel.

> ⚠️ **TRAP 3:** "A body moving in a circular path at constant speed has zero acceleration" — WRONG. Direction changes, so velocity changes, so acceleration exists (centripetal).

> ⚠️ **TRAP 4:** "Free fall acceleration = 10 m/s²" — Use 9.8 m/s² for exact answers; 10 m/s² is an approximation used in calculations unless stated.

> ⚠️ **TRAP 5:** "Momentum is a scalar" — WRONG. Momentum (p = mv) is a vector because velocity is a vector.

> ⚠️ **TRAP 6:** "Heavier objects fall faster" — WRONG (Galileo's finding). All objects fall with same acceleration g in vacuum regardless of mass.

> ⚠️ **TRAP 7:** "The third law pair is: weight of a book on table and normal reaction from table" — This is CORRECT. They are action-reaction pairs on different bodies.

> ⚠️ **TRAP 8:** "A body at rest has no forces acting on it" — WRONG. It has balanced forces (net force = 0, not no forces).

---

## 19. Solved Numericals

### Numerical 1
**Q:** A car starts from rest and reaches a velocity of 20 m/s in 10 seconds. Find (a) acceleration, (b) distance covered.

```
Given: u = 0, v = 20 m/s, t = 10 s
(a) a = (v − u)/t = (20 − 0)/10 = 2 m/s²
(b) s = ut + ½at² = 0 + ½ × 2 × 100 = 100 m
    OR s = (u+v)/2 × t = (0+20)/2 × 10 = 100 m
```

### Numerical 2
**Q:** A ball of mass 0.5 kg moving at 10 m/s is stopped by a wall in 0.02 s. Find the average force exerted by the wall.

```
Given: m = 0.5 kg, u = 10 m/s, v = 0, t = 0.02 s
Impulse = m(v − u) = 0.5(0 − 10) = −5 N·s
|Impulse| = 5 N·s
F = |Impulse|/t = 5/0.02 = 250 N
```

### Numerical 3
**Q:** A bullet of mass 50 g is fired from a gun of mass 2 kg. The bullet moves with velocity 100 m/s. Find the recoil velocity of the gun.

```
Given: m_bullet = 0.05 kg, v_bullet = 100 m/s, m_gun = 2 kg, u_gun = 0, u_bullet = 0
By conservation of momentum: 0 = m_bullet × v_bullet + m_gun × v_gun
0 = 0.05 × 100 + 2 × v_gun
v_gun = −5/2 = −2.5 m/s
Recoil velocity of gun = 2.5 m/s (backward)
```

### Numerical 4
**Q:** A body dropped from rest falls 45 m. Find the velocity when it hits the ground. (g = 10 m/s²)

```
Given: u = 0, s = 45 m, a = g = 10 m/s²
v² = u² + 2as = 0 + 2 × 10 × 45 = 900
v = 30 m/s
```

### Numerical 5
**Q:** A body of mass 4 kg is acted upon by a force of 20 N. Starting from rest, find the distance covered in 3 seconds.

```
a = F/m = 20/4 = 5 m/s²
s = ut + ½at² = 0 + ½ × 5 × 9 = 22.5 m
```

---

## 20. Conceptual Questions (Self-Test)

1. Why does a runner lean forward while running?
2. Why are road vehicles fitted with seat belts?
3. Why does a ball bounce higher on a hard floor than on a soft carpet?
4. Why does a ship float while a coin sinks?
5. Why does a fast-moving vehicle take more distance to stop than a slow-moving one?
6. Why are car bumpers made of rubber/plastic rather than hard steel?
7. Why does a ball thrown straight up on a moving train land back in the thrower's hands?

---

## 21. Must-Remember Points

- Newton's 1st Law → Inertia → "Lazy Law"
- Newton's 2nd Law → F = ma = Δp/Δt → quantitative
- Newton's 3rd Law → Action-Reaction → different bodies → no cancellation
- Momentum p = mv → vector → unit kg·m/s
- Impulse J = Ft = Δp → explains airbags, cricket
- Equations of motion: 3 equations, 5 variables (u, v, a, t, s)
- Free fall: g = 9.8 m/s² downward; independent of mass
- Projectile: max range at 45°; parabolic path
- Circular motion: centripetal force toward centre; centrifugal = pseudo force
- Friction: rolling < kinetic < static; necessary for walking, brakes
- Conservation of momentum: holds in all collisions (elastic + inelastic)

---

## 22. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  MOTION & NEWTON'S LAWS — QUICK REVISION             ║
╠══════════════════════════════════════════════════════╣
║  Newton's 1st Law → Inertia (no F → no change)       ║
║  Newton's 2nd Law → F = ma = Δp/Δt                   ║
║  Newton's 3rd Law → Equal+opposite on DIFF. bodies   ║
║  Momentum p = mv (vector, kg·m/s)                    ║
║  Impulse J = Ft = Δp (explains airbag, cushion)      ║
║  Equations: v=u+at | s=ut+½at² | v²=u²+2as           ║
║  Free fall: g=9.8 m/s², ALL objects fall same rate   ║
║  Projectile: parabola, max range at 45°              ║
║  Friction: rolling < kinetic < static                ║
║  Momentum conserved in ALL collisions                ║
╚══════════════════════════════════════════════════════╝
```

---

## 23. Last-Minute Revision Sheet (Exam Morning)

```
✅ 1st Law = Inertia; 2nd = F=ma; 3rd = Action-Reaction (diff bodies)
✅ p = mv (kg·m/s) | J = Ft = Δp
✅ v=u+at | s=ut+½at² | v²=u²+2as
✅ Free fall: all objects = same g (Galileo)
✅ Projectile max range = 45°
✅ Centripetal force = toward centre = REAL
✅ Centrifugal = pseudo force (non-inertial frame)
✅ Rocket = Newton's 3rd law
✅ Airbag = increases time → decreases force
✅ Inertia ∝ mass (NOT velocity)
✅ Momentum conserved in all isolated collisions
✅ Elastic: KE conserved | Inelastic: KE NOT conserved
✅ Friction order: rolling < sliding < static
```

---

## 24. Concept Map

```
MOTION
├── Types: Uniform | Non-uniform | Rectilinear | Circular | Projectile
├── Quantities
│   ├── Scalar: distance, speed, mass, time, energy
│   └── Vector: displacement, velocity, acceleration, force, momentum
├── Equations of Motion (uniform a)
│   ├── v = u + at
│   ├── s = ut + ½at²
│   └── v² = u² + 2as
└── Newton's Laws
    ├── 1st: Inertia → no external force = no change
    ├── 2nd: F = ma = Δp/Δt → Impulse = Ft = Δp
    └── 3rd: Action-Reaction (equal, opposite, different bodies)
        └── Applications: rocket, gun recoil, swimming, walking

FRICTION
├── Static > Kinetic > Rolling
├── Useful: walking, brakes, writing
└── Harmful: engine wear, heat loss

CONSERVATION OF MOMENTUM
├── Total p before = Total p after (no external force)
├── Elastic: KE conserved
└── Inelastic: KE not fully conserved
```

---

## 25. Expected Future Question Areas

- Questions on **impulse and force reduction** (airbag, padding) — conceptual
- **Numerical on equations of motion** — moderate difficulty
- **Newton's Laws applied to everyday situations** — which law explains each scenario
- **Gun-bullet recoil** numerical using conservation of momentum
- **Projectile at 45°** → maximum range concept
- **Difference between mass and weight** in context of moon/space missions
- **Circular motion** — centripetal vs centrifugal force (which is real)
