# P14 — Semiconductors & Electronics 📖 Priority 4

> **Exam Importance:** Low frequency in RRB NTPC/APPSC; moderate in RRB JE. Know p-type/n-type distinction, p-n junction, diode (rectifier), transistor (switch/amplifier), and basic logic gates.

---

## 1. Conductors, Semiconductors, Insulators

| Type | Resistivity | Band Gap | Example |
|------|------------|---------|---------|
| Conductor | Very low (10⁻⁸ Ω·m) | No gap | Copper, silver, gold |
| Semiconductor | Intermediate (10⁻² – 10⁴ Ω·m) | Small gap (~1 eV) | Silicon, germanium |
| Insulator | Very high (10⁸ – 10¹⁶ Ω·m) | Large gap (>5 eV) | Glass, rubber, plastic |

**Semiconductor properties:**
- Conductivity increases with temperature (unlike metals)
- Conductivity can be controlled by doping

---

## 2. Intrinsic vs Extrinsic Semiconductors

| Type | Description | Example |
|------|-------------|---------|
| Intrinsic | Pure semiconductor; few free carriers at room temp | Pure Si, pure Ge |
| Extrinsic | Doped with impurity atoms to increase conductivity | Si doped with P (n-type) or B (p-type) |

### 2.1 Doping

**n-type semiconductor:**
- Doped with **pentavalent** impurity (5 valence electrons): Phosphorus (P), Arsenic (As), Antimony (Sb)
- Majority carriers: **Electrons** (negative)
- Minority carriers: Holes

**p-type semiconductor:**
- Doped with **trivalent** impurity (3 valence electrons): Boron (B), Aluminium (Al), Indium (In)
- Majority carriers: **Holes** (positive)
- Minority carriers: Electrons

---

## 3. p-n Junction Diode

- Junction of p-type and n-type semiconductors
- **Depletion region:** Region at junction depleted of charge carriers; creates a potential barrier

**Forward bias:** p-side to +, n-side to − → current flows (barrier reduced)
**Reverse bias:** p-side to −, n-side to + → current barely flows (barrier increased) → very small leakage current

**Uses of diode:**
- **Rectifier:** Converts AC to DC (half-wave or full-wave)
- **LED (Light Emitting Diode):** Emits light when forward biased; used in indicators, displays, fibre optic
- **Photodiode:** Detects light; works in reverse bias
- **Zener diode:** Voltage regulation (reverse breakdown mode)
- **Solar cell:** Converts light to electrical energy

---

## 4. Transistor

- Semiconductor device with three layers: **Emitter, Base, Collector**
- Two types: **npn** and **pnp**

**Functions:**
1. **Amplifier** — small input signal → large output signal
2. **Switch** — controls ON/OFF of circuit
3. **Oscillator** — generates AC signals

---

## 5. Logic Gates

| Gate | Symbol | Truth Table Concept | Output |
|------|--------|--------------------|----|
| AND | A · B | Output 1 only if ALL inputs are 1 | 1 only when A=1 AND B=1 |
| OR | A + B | Output 1 if ANY input is 1 | 1 when A=1 OR B=1 |
| NOT (Inverter) | Ā | Output = opposite of input | 0→1, 1→0 |
| NAND | (A · B)' | NOT AND — 0 only when both inputs 1 | Universal gate |
| NOR | (A + B)' | NOT OR — 1 only when both inputs 0 | Universal gate |
| XOR | A ⊕ B | 1 when inputs DIFFER | 1 when A≠B |
| XNOR | (A ⊕ B)' | 1 when inputs are SAME | 1 when A=B |

> **Universal gates:** NAND and NOR can be used to build any other logic gate.

---

## 6. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  SEMICONDUCTORS & ELECTRONICS — QUICK REVISION       ║
╠══════════════════════════════════════════════════════╣
║  Semiconductor: conductivity ↑ with temperature      ║
║  n-type: pentavalent dopant (P, As); electrons       ║
║  p-type: trivalent dopant (B, Al); holes             ║
║  Diode: AC→DC rectifier | LED: light emission       ║
║  Transistor: amplifier + switch                      ║
║  AND: both must be 1 | OR: at least one 1           ║
║  NOT: inverts | NAND/NOR: universal gates           ║
╚══════════════════════════════════════════════════════╝
```
