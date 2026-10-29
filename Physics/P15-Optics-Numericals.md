# P15 — Optics: Advanced Numericals & Combinations 📘 Priority 3

> **Exam Importance:** Mirror and lens numericals with sign convention, combinations of lenses, and power calculations appear in RRB JE and SSC JE technical papers. This chapter complements P04.

**Cross-links:** [P04 Light](P04-Light-Reflection-Refraction.md)

---

## 1. Sign Convention — Full Rules

**New Cartesian Sign Convention:**

1. All distances are measured from the **pole (mirror) or optical centre (lens)**
2. Distances measured in the **direction of incident light = POSITIVE**
3. Distances measured **against incident light = NEGATIVE**
4. Heights above principal axis = **positive**; below = **negative**

**For mirrors:**
- Object is always in front of mirror → u is always NEGATIVE
- Real image forms in front of mirror → v is NEGATIVE (real)
- Virtual image forms behind mirror → v is POSITIVE (virtual)
- Concave mirror: f is NEGATIVE | Convex mirror: f is POSITIVE

**For lenses:**
- Object is always on left → u is always NEGATIVE
- Real image on right → v is POSITIVE | Virtual image on left → v is NEGATIVE
- Convex (converging) lens: f is POSITIVE
- Concave (diverging) lens: f is NEGATIVE

---

## 2. Mirror Formula — Derivations and Cases

```
1/f = 1/v + 1/u
m = -v/u = h'/h
R = 2f  (radius of curvature = 2 × focal length)
```

### Solved Examples

**Example 1:** Object at 30 cm from concave mirror (f = 15 cm). Find v and m.
```
u = -30 cm, f = -15 cm
1/f = 1/v + 1/u
1/(-15) = 1/v + 1/(-30)
1/v = -1/15 + 1/30 = -2/30 + 1/30 = -1/30
v = -30 cm (real image, same side as object)
m = -v/u = -(-30)/(-30) = -1 (inverted, same size)
```

**Example 2:** Object 10 cm from convex mirror (f = 20 cm). Find image.
```
u = -10 cm, f = +20 cm
1/f = 1/v + 1/u
1/20 = 1/v + 1/(-10) = 1/v - 1/10
1/v = 1/20 + 1/10 = 1/20 + 2/20 = 3/20
v = +20/3 = +6.67 cm (virtual, behind mirror)
m = -v/u = -(20/3)/(-10) = 2/3 (erect, diminished)
```

---

## 3. Lens Formula — Cases and Examples

```
1/f = 1/v - 1/u
m = v/u = h'/h
P = 1/f(m)  [Dioptre]
```

**Example 1:** Object 40 cm from convex lens (f = 10 cm).
```
u = -40 cm, f = +10 cm
1/f = 1/v - 1/u
1/10 = 1/v - 1/(-40) = 1/v + 1/40
1/v = 1/10 - 1/40 = 4/40 - 1/40 = 3/40
v = 40/3 ≈ +13.3 cm (real, on other side)
m = v/u = (40/3)/(-40) = -1/3 (inverted, diminished)
```

**Example 2:** Object 5 cm from convex lens (f = 10 cm) → magnifying glass
```
u = -5 cm, f = +10 cm
1/10 = 1/v - 1/(-5) = 1/v + 1/5
1/v = 1/10 - 1/5 = 1/10 - 2/10 = -1/10
v = -10 cm (virtual, same side as object)
m = v/u = -10/(-5) = 2 (erect, magnified)
```

---

## 4. Combination of Lenses

When two or more thin lenses are placed in contact:

```
1/f_eq = 1/f₁ + 1/f₂ + 1/f₃ + ...
P_eq = P₁ + P₂ + P₃ + ...   [Powers add in Dioptre]
```

**Example:** Convex lens P₁ = +5D combined with concave lens P₂ = −3D
```
P_eq = +5 + (−3) = +2D
f_eq = 1/P_eq = 1/2 = 0.5 m = 50 cm (converging)
```

---

## 5. Magnifying Power of Optical Instruments

**Simple microscope (magnifying glass):**
```
M = 1 + D/f     (when image at near point D = 25 cm)
M = D/f         (when image at infinity)
```

**Compound microscope:**
```
M = M_objective × M_eyepiece
M = (L/f_o) × (D/f_e)
```
where L = tube length, f_o = objective focal length, f_e = eyepiece focal length

**Astronomical telescope (normal adjustment):**
```
M = f_o/f_e
```
- Large objective focal length → high magnification
- Large aperture (diameter) → more light → better resolution

---

## 6. Quick Practice Numericals

**Q1:** Find the focal length of a concave mirror if the image of a distant object forms at 15 cm from the mirror.
```
For object at infinity, image forms at F.
f = -15 cm (concave)
R = 2f = -30 cm
```

**Q2:** A lens produces a virtual, erect, magnified image. What type of lens is it?
```
Virtual + erect + magnified → Convex lens (object between F and O)
This is a magnifying glass.
```

**Q3:** A doctor prescribes −2.5D lens. What is the focal length?
```
f = 1/P = 1/(-2.5) = -0.4 m = -40 cm (concave lens → corrects myopia)
```

---

## 7. Quick Revision Box

```
╔══════════════════════════════════════════════════════╗
║  OPTICS NUMERICALS — QUICK REVISION                  ║
╠══════════════════════════════════════════════════════╣
║  Mirror: 1/f = 1/v + 1/u | m = -v/u                 ║
║  Lens: 1/f = 1/v - 1/u | m = v/u                   ║
║  Concave mirror: f < 0 | Convex mirror: f > 0        ║
║  Convex lens: f > 0, P > 0 | Concave: f < 0, P < 0  ║
║  P = 1/f(m) [Dioptre] | Combination: P = P₁+P₂+...  ║
║  R = 2f for all spherical mirrors                    ║
║  Magnifying glass: convex lens (object inside F)     ║
║  Telescope M = f_o/f_e                               ║
╚══════════════════════════════════════════════════════╝
```
