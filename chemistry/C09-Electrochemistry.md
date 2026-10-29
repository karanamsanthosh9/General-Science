# C09 — Electrochemistry ⭐ Priority 2

> **Exam Importance:** Electrolysis, electroplating, cathode/anode identification, galvanic vs electrolytic cells, Faraday's laws, and battery types are exam-tested topics. Cathode = reduction = deposition is a critical distinction.

**Cross-links:** [C04 Metals](C04-Metals-NonMetals.md) · [P05 Electricity](../Physics/P05-Electricity-Magnetism.md) · [C06 Chemical Reactions](C06-Chemical-Reactions.md)

---

## 1. Electrochemistry — Introduction

Electrochemistry studies the relationship between electrical energy and chemical reactions.

**Two types of electrochemical cells:**

| Type | Energy Conversion | Process | Example |
|------|-----------------|---------|---------|
| **Galvanic (voltaic) cell** | Chemical → Electrical | Spontaneous oxidation-reduction | Battery, Daniel cell, fuel cell |
| **Electrolytic cell** | Electrical → Chemical | Non-spontaneous (forced) | Electrolysis, electroplating |

---

## 2. Key Definitions

| Term | Definition |
|------|-----------|
| **Electrode** | Conductor that connects electric circuit to electrolytic solution |
| **Anode** | Electrode where OXIDATION occurs (positive in electrolytic; negative in galvanic) |
| **Cathode** | Electrode where REDUCTION occurs (negative in electrolytic; positive in galvanic) |
| **Electrolyte** | Substance that conducts electricity when dissolved/molten (contains free ions) |
| **Electrolysis** | Decomposition of electrolyte by passage of electricity |
| **EMF** | Electromotive force — driving potential of the cell |

**Memory Aid:**
```
AN OX — Anode = Oxidation
RED CAT — Reduction = Cathode
```

---

## 3. Electrolytic Cell — Anode and Cathode Rules

| Electrode | Sign (Electrolytic) | Process | Event |
|-----------|-------------------|---------|-------|
| **Cathode** | Negative (−) | Reduction | Cations (positive ions) migrate here; metal deposits here |
| **Anode** | Positive (+) | Oxidation | Anions (negative ions) migrate here; gas/metal dissolves |

**Electrolysis of water:**
```
2H₂O → 2H₂ + O₂

At CATHODE (−): 4H⁺ + 4e⁻ → 2H₂↑   (H₂ gas — DOUBLE the volume)
At ANODE (+): 2H₂O → O₂ + 4H⁺ + 4e⁻  (O₂ gas)

Volume ratio H₂:O₂ = 2:1
```

**Electrolysis of NaCl solution (brine):**
```
At CATHODE: 2H⁺ + 2e⁻ → H₂↑         (hydrogen gas)
At ANODE: 2Cl⁻ → Cl₂↑ + 2e⁻          (chlorine gas)
In solution: NaOH is formed
This is the CHLOR-ALKALI process (industrial importance)
```

---

## 4. Faraday's Laws of Electrolysis

### 4.1 Faraday's First Law

> *"The mass of a substance deposited/dissolved at an electrode is directly proportional to the quantity of electricity passed."*

```
m = ZIt = ZQ
where:
m = mass deposited (g)
Z = electrochemical equivalent (g/C)
I = current (A)
t = time (s)
Q = It = charge (Coulombs)
```

### 4.2 Faraday's Second Law

> *"When the same quantity of electricity is passed through different electrolytes, the masses of substances deposited are proportional to their equivalent weights.*"

```
m₁/m₂ = E₁/E₂   (where E = equivalent weight = M/n, n = valency)
```

**Faraday's constants:**
```
1 Faraday (F) = 96,500 Coulombs = charge on 1 mole of electrons
Q = nF (for n moles of electrons)
```

---

## 5. Electroplating

**Definition:** Depositing a thin layer of a desired metal on another metal using electrolysis.

**Setup:**
- **Cathode:** Object to be plated (gets coated)
- **Anode:** Metal used for plating (dissolves)
- **Electrolyte:** Salt solution of the plating metal

**Process (silver plating example):**
```
Cathode = object (spoon to be plated)
Anode = silver bar
Electrolyte = AgNO₃ solution
Result: Ag deposits on cathode (spoon); Ag dissolves from anode
```

**Applications of Electroplating:**

| Application | Metal Deposited | Purpose |
|------------|----------------|---------|
| Silvering cutlery | Silver (Ag) | Decorative, cost-effective |
| Chrome plating | Chromium (Cr) | Car bumpers, shiny finish, corrosion resistance |
| Gold plating | Gold (Au) | Jewellery, electronics |
| Nickel plating | Nickel (Ni) | Corrosion resistance |
| Tinplating | Tin (Sn) | Food cans (tin can) — prevents rust |
| Zinc plating (galvanising) | Zinc (Zn) | Protecting iron from rust |
| Copper plating | Copper (Cu) | Making printed circuit boards |

---

## 6. Galvanic Cells (Voltaic Cells)

### 6.1 Daniel Cell (Zinc-Copper cell)

```
Zn | ZnSO₄ || CuSO₄ | Cu

Anode (−): Zn → Zn²⁺ + 2e⁻       (zinc dissolves)
Cathode (+): Cu²⁺ + 2e⁻ → Cu      (copper deposits)
EMF = +1.1 V
```

### 6.2 Types of Batteries

| Battery | Type | Electrolyte | Reaction | Use |
|---------|------|------------|---------|-----|
| **Dry cell (Leclanché)** | Primary (non-rechargeable) | NH₄Cl paste | Zn−MnO₂ | Torch, remotes |
| **Lead-acid battery** | Secondary (rechargeable) | H₂SO₄ (dilute) | Pb−PbO₂ | Car battery |
| **Lithium-ion battery** | Secondary (rechargeable) | Li salt in organic solvent | Li chemistry | Mobile phones, laptops |
| **Nickel-cadmium (NiCd)** | Secondary | KOH | Ni−Cd | Cordless devices |
| **Nickel-metal hydride (NiMH)** | Secondary | KOH | Ni−metal hydride | Hybrid cars |
| **Alkaline battery** | Primary | KOH | Zn−MnO₂ | Longer-lasting than dry cell |
| **Fuel cell** | Continuous | Various | H₂ + O₂ → H₂O | Spacecraft, vehicles |

**Lead-acid battery (car battery):**
```
Anode: Pb → Pb²⁺ + 2e⁻ (oxidation)
Cathode: PbO₂ + 4H⁺ + 2e⁻ → Pb²⁺ + 2H₂O (reduction)
Electrolyte: Dilute H₂SO₄ (density ~1.28 g/mL when charged)
EMF per cell ≈ 2V; 6-cell car battery = 12V
```

---

## 7. Corrosion and its Prevention (Electrochemical Basis)

- **Rusting** is an electrochemical process — iron acts as anode (Fe → Fe²⁺), oxygen and water form cathode
- Requires electrolyte (moisture) and oxidant (O₂)
- **Galvanic corrosion:** Two different metals in contact in electrolyte → more reactive metal corrodes faster

**Prevention:**
- **Galvanising** (Zn sacrificial anode)
- **Cathodic protection** (make iron cathode by attaching Mg/Zn block)
- Painting, coating

---

## 8. Conductors, Semiconductors, Electrolytes

| Conductor Type | Charge Carrier | Example |
|---------------|---------------|---------|
| Electronic conductor (metallic) | Free electrons | Metals, graphite |
| Electrolytic conductor | Ions | Salt solutions, molten salts, acids/bases |
| Semiconductors | Electrons and holes | Si, Ge |

---

## 9. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  ELECTROCHEMISTRY — QUICK REVISION                   ║
╠══════════════════════════════════════════════════════╣
║  AN OX / RED CAT: Anode=Oxidation; Cathode=Reduction ║
║  Cathode (−): metal deposits; Anode (+): dissolves   ║
║  Faraday's 1st: m = ZIt (mass ∝ charge)             ║
║  1 Faraday = 96,500 C = charge of 1 mol electrons   ║
║  Water electrolysis: H₂ at cathode, O₂ at anode    ║
║  Brine electrolysis: H₂ at cathode, Cl₂ at anode   ║
║  Daniel cell: Zn anode, Cu cathode, EMF=1.1V        ║
║  Lead-acid: car battery, 2V/cell, 12V total (6 cells)║
║  Electroplating: cathode=object, anode=plating metal ║
╚══════════════════════════════════════════════════════╝
```
