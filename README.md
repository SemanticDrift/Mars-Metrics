## Mars Metrics
### Metonic Frequency Analysis of Mars, Phobos and Deimos

**Series:** Harmonic Orbital Mechanics
**Author:** Carolina Johnson (CJ)
**Date:** June 2026
**License:** CC BY 4.0, Attribution required
**DOI:** https://doi.org/10.5281/zenodo.20606778
**ORCID:** https://orcid.org/0009-0002-8819-3347

---

## What This Does

Derives the orbital and physical architecture of the Mars Phobos Deimos system from discrete harmonic constraints. No gravitational constants, mass terms, or continuous differential equations are used.

The spatial lattice pathway and the temporal frequency pathway converge on a theoretical aphelion of 5/3 AU. The satellite cavity recovers the global grid resolution step k = 64. The axial tilt (26.11°) is derived from the cavity ratio Γ = 28/57. The orbital eccentricity is derived from the lattice boundaries and the precession buffer. The lattice closure residual of 0.0040 defines the distance from perfect rational closure.

Every parameter locks to integer nodes and rational fractions. The system is not fitted. It is discovered.

---

## The Core Derivation Chain

1. The frequency pathway (f_M = f_E · 3/5) yields aphelion at 5/3 AU
2. The spatial pathway (n = 40, ε = 1/64, torque = 8/5) converges on the same value
3. The satellite cavity recovers the global grid resolution step k = 64
4. Phobos at node n = 112, no torsion → 2.75 R_Mars
5. Deimos at node n = 228, torsion τ = 5/3 → 6.9375 R_Mars
6. Axial tilt derived from cavity ratio Γ = 28/57 → 26.11°
7. Lattice eccentricity from aphelion and perihelion nodes → 1/19 ≈ 0.0526
8. Predicted eccentricity (with buffer) → 0.0685
9. Lattice closure residual → 0.0040

---

## Repository Contents

| File | Description |
|------|-------------|
| `README.md` | This file |
| `Annex MRS.pdf` | Full paper with derivations, tables, and references |

---

## Dependencies

| Work | DOI |
|------|-----|
| Law of Admissibility (R = 4) | https://doi.org/10.5281/zenodo.18223592 |
| Calculating Planetary Distance | https://doi.org/10.5281/zenodo.19720428 |
| Harmonic Orbital Mechanics | https://doi.org/10.5281/zenodo.18314933 |
| The Origami Principle | https://doi.org/10.5281/zenodo.18293883 |

Full framework available at https://www.SemanticShift.net

---

## Citation

```
Johnson, C. (2026). Mars Metrics: Metonic Frequency Analysis of Mars, Phobos and Deimos.
Annex MRS to Harmonic Orbital Mechanics. Series: Harmonic Orbital Mechanics. SemanticShift.
DOI: https://doi.org/10.5281/zenodo.20606778
License: CC BY 4.0
```
---

## License

© 2026 Carolina Johnson (CJ)
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)
Attribution required. https://creativecommons.org/licenses/by/4.0/
