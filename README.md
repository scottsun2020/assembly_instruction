
# PCB Test Stand — Assembly Guide

> **Purpose**: This document explains how to assemble the PCB test stand shown below. It’s written to be pasted into your repo as `README.md` (or `docs/assembly.md`).

![Front view](docs/images/front-view.jpg)
![Side view](docs/images/side-view.jpg)

> Replace the two image file paths above with your actual image locations on GitHub (e.g., `docs/images/front-view.jpg`).

---

## 1) Overview

A compact, rigid test stand built from 2020 aluminum extrusions and printed/metal corner brackets. It provides:
- A stable **base plate** with PCB **standoffs**.
- Two **vertical uprights**.
- A **movable crosshead** on linear guide rods for fixtures/probes.
- Adjustable **lower rails** for anchoring accessories.

---

## 2) Bill of Materials (BOM)

| # | Item | Spec / Notes | Qty |
|---|------|---------------|-----|
| 1 | 2020 aluminum extrusion – **base rails** | Length: __TODO__ mm (2 pcs) | 2 |
| 2 | 2020 aluminum extrusion – **uprights** | Length: __TODO__ mm (2 pcs) | 2 |
| 3 | 2020 aluminum extrusion – **crossbars** | Length: __TODO__ mm (2 pcs) | 2 |
| 4 | **Base plate** (machined/printed) | Hole pattern for M3/M4/M5; countersunk | 1 |
| 5 | **Corner brackets** (yellow in photo) | L or triangular plates | 4 large + 2 triangular |
| 6 | **Linear guide rods** | Ø __TODO__ mm × __TODO__ mm | 2 |
| 7 | **Crosshead carriage blocks** | Slide on rods; includes clamp screws | 2 |
| 8 | **Rod ends / ball joints** | For linkage/fixture (seen at front) | 2 |
| 9 | **PCB standoffs** | M3 × __TODO__ height | 4–6 |
| 10 | End caps for 2020 | Plastic | 4 |
| 11 | T‑nuts (drop‑in or roll‑in) | M5 for extrusion slots | ~40 |
| 12 | Socket head screws | M5×8/10/12 (for brackets/extrusions) | ~40 |
| 13 | Base plate screws | M4/M5 as needed, with washers | 8 |
| 14 | Washers & spring washers | M5 | as req. |
| 15 | Threadlocker | Medium strength (Loctite 243) | — |
| 16 | Optional feet | Rubber bumpers | 4 |

> **Note:** Fill in `__TODO__` lengths to match your cut stock. If you standardize to 250/300/350 mm, note it here.

---

## 3) Required Tools

- 3 mm & 4 mm hex keys (for M5 hardware)
- 2.5 mm hex (if using M4 screws)
- Torque wrench with hex bits (range 2–6 N·m) — _optional but recommended_
- Digital calipers or steel ruler
- Small square for squaring the frame
- Marker/tape for part labeling
- Threadlocker (medium strength)
- Soft‑jaw pliers (optional for rod ends)
- Spirit level (optional)

---

## 4) Preparation

1. **Label** every extrusion with masking tape (`Base‑L`, `Base‑R`, `Upright‑L`, `Upright‑R`, `X‑Bar‑Top`, `X‑Bar‑Bottom`).  
2. **Deburr** aluminum ends. Blow out chips from T‑slots.  
3. **Pre‑load T‑nuts** in each slot you’ll need. It’s much easier than adding them later.  
4. **Dry‑fit** brackets and confirm hole alignment on the base plate.

> **Torque guideline**: For **M5** in aluminum, tighten to **3–4 N·m** (hand‑snug + 1/8 turn). Use **threadlocker** on joints you don’t plan to re‑position.

---

## 5) Assembly Steps

### A. Build the Base
1. Lay the **two base rails** parallel on the bench. Install **end caps**.  
2. Position the **base plate** centered across the rails. Loosely fasten with M5 screws + washers into T‑nuts. Do **not** fully tighten.  
3. Attach **front rod‑end tabs** (if used) to the front of the base plate/rails with two M5 screws each; keep loose for now.

**Square & Level Check**  
- Measure the base plate **edge to rail** distances on both sides; make them equal.  
- Tighten base plate screws uniformly to ~3 N·m.

### B. Install Uprights
1. Bolt **L‑brackets** to the rails at the back corners (left/right). Leave screws **finger‑tight**.  
2. Stand the **uprights** vertically into the L‑brackets. Ensure the rear faces are flush to bracket shoulders.  
3. Using a small **square**, set each upright to 90° relative to the base. Tighten bracket screws to **3–4 N·m**.  
4. Fit the **triangular side plates** to tie the uprights to the base rails. Tighten to 3–4 N·m.

### C. Fit Linear Guide & Crosshead
1. Insert the **linear rods** through the **lower carriage blocks**, then into the **upper blocks** mounted on the crosshead brackets.  
2. Slide the assembly between uprights. Secure the **rod clamps** (on the yellow crosshead pieces) so the crosshead moves smoothly without racking.  
3. Adjust the **block spacing** so both rods are parallel and the crosshead does not bind. Tighten the clamp screws lightly (≈2 N·m).

> **Smoothness test**: Raise the crosshead ~100 mm and let go. It should descend smoothly without sticking. If it binds, loosen clamps, tap the rod ends gently, and re‑square.

### D. Install Crossbars
1. Add the **two horizontal 2020 crossbars** between uprights at the top and mid‑section using M5 screws/T‑nuts in the side slots.  
2. Ensure both crossbars are level and parallel; then tighten to 3–4 N·m. These can support probe holders, cameras, or cable guides.

### E. Mount PCB Standoffs
1. Thread **M3 standoffs** into the base plate’s mounting pattern.  
2. Verify spacing matches your target PCB. Adjust/add hole adapters if needed.  
3. Add **thumb screws** or M3 screws from top to secure the PCB during tests.

### F. Final Tightening & Safety
- Re‑check all joints; apply medium threadlocker where final.  
- Confirm there are **no sharp edges** protruding into operator area.  
- Add **rubber feet** to base rails if the rig will sit on a sensitive benchtop.

---

## 6) Alignment & QA Checklist

- [ ] Base plate centered; equal setback from both rails.  
- [ ] Uprights square to base (≤0.5°).  
- [ ] Crosshead travels smoothly full stroke; no racking/binding.  
- [ ] Crossbars level and parallel (±0.5 mm over span).  
- [ ] All M5 hardware torqued to 3–4 N·m; threadlocker used where appropriate.  
- [ ] PCB standoffs match board hole pattern; board sits flat without rocking.  
- [ ] No collisions between moving parts and PCB/work area.

---

## 7) Mounting Accessories

- **Probe holders / spring pins**: attach to the crosshead or crossbars using T‑nuts.  
- **Cable strain relief**: zip‑tie anchors into the side slots.  
- **Camera/light**: add an L‑plate to the top crossbar.  
- **ESD**: bond the base plate to ground with a ring terminal + M5 screw.

---

## 8) Maintenance

- Inspect screws monthly; re‑torque loose joints.  
- Wipe rods with lint‑free cloth; add a thin film of light machine oil if needed.  
- Replace worn printed brackets if cracks appear.

---

## 9) Repository Layout (suggested)

```
.
├─ README.md                 # This file
├─ /docs
│  ├─ assembly.md            # (optional) longer form with more photos
│  └─ /images
│     ├─ front-view.jpg
│     └─ side-view.jpg
├─ /cad
│  ├─ extrusion_lengths.txt
│  ├─ base_plate.dxf
│  └─ brackets/
└─ /stl (if using printed parts)
```

---

## 10) License

Choose a license that fits your use (e.g., CERN‑OHL‑P for hardware, or MIT). Add `LICENSE` to the repo root.

---

## 11) Quick Start (TL;DR)

1. Build and square **base**.  
2. Bolt on **uprights**.  
3. Insert **linear rods + crosshead**; tune for smooth motion.  
4. Add **crossbars**, **standoffs**, and any **fixtures**.  
5. Tighten, threadlock, and run the **QA checklist**.

Happy testing!

---

### Photo References
Front view (example):  
![Front view](docs/images/front-view.jpg)

Side view (example):  
![Side view](docs/images/side-view.jpg)
