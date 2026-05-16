# Structural Analysis of a 4-Stroke 4-Cylinder Engine Crankshaft

Comprehensive FEA of an engine crankshaft covering static, dynamic, fatigue and thermal behaviour.

## What I did

- Derived real loading from first principles — combustion pressures, inertia forces, bending and torsion — before setting up the simulation
- Static and dynamic structural analysis for von Mises stress distribution and deformation; peak stress confirmed at the fillets, consistent with typical crankshaft failure locations
- Fatigue analysis using S-N curves; modal analysis to identify natural frequencies and confirm no operating RPM ranges coincide with resonance modes
- Harmonic response and transient thermal analysis under cyclic loading to assess temperature distribution
- Parametric material study across several alloys; final selection achieved **FOS 2.0 (static)** and **FOS 1.8 (fatigue)**

## Tools

ANSYS Static Structural

## Key results

- Peak stress location: crankshaft fillets (matches real-world failure data)
- Factor of safety: 2.0 (static), 1.8 (fatigue) — meets standard engine component requirements
- No resonance modes within operating RPM range

<img width="1555" height="619" alt="image" src="https://github.com/user-attachments/assets/489d2d19-db7b-49bd-b4b0-49c652959b2b" />
<img width="1554" height="626" alt="image" src="https://github.com/user-attachments/assets/b162555a-42fb-4dc9-bac9-9852ae52605e" />
<img width="1551" height="228" alt="image" src="https://github.com/user-attachments/assets/93463935-e363-4007-ac1e-95e75218f60a" />
<img width="1557" height="626" alt="image" src="https://github.com/user-attachments/assets/f8765132-39f6-451f-90b3-d9b4bbb4c852" />
<img width="1556" height="843" alt="image" src="https://github.com/user-attachments/assets/6c1538f4-c115-42ca-bc18-2126756b51d7" />
