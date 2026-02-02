# Mixers Australia — Internal References (NOT for Client-Facing Use)

> **CONFIDENTIAL INTERNAL NOTE**
>
> This file contains internal benchmark references and must **never** be used in client-facing proposals, emails, reports, or presentations.
> Any external benchmark project names must not be disclosed.

---

## 1. Benchmark Reference System (Gilmore Space Welding System)
### Reference material
- Internal reference: **MEXX-PROP-Q3016 - Gilmore Space Welding System REV B.pdf**
- This system is used as an internal benchmark for:
  - heavy-duty rotating workpiece welding
  - robot-on-track circumferential welding
  - headstock/tailstock alignment and force closure
  - long seam / circumferential seam welding automation

### High-level concept summary
The benchmark system is designed to weld large cylindrical tank assemblies (rocket fuel tank sections), assembled from multiple sections (front / middle / rear).

Key elements:
- **Heavy headstock** fixed on base
- **Tailstock** on long travel track (to accommodate variable tank lengths)
- Tailstock applies axial force to **push / close** sections together prior to welding
- **ABB welding robot** mounted on a **linear track** parallel to the workpiece
- Robot fitted with **Fronius MIG welding package**
- Robot traverses along the track to reach weld locations and complete weld passes
- Work envelope includes guarding / safety zoning

### Why this is relevant to Mixers Australia
Mixers Australia mixer bowls follow a similar “multi-section assembly” workflow:
- bowl consists of **front cone + middle + rear cone**
- sections require circumferential weld joints after fit-up
- bowl is heavy, awkward, and requires controlled alignment and support during welding

The benchmark system architecture provides a proven approach for:
- high stiffness / alignment control
- variable length assembly handling
- high-quality robotic MIG welding along long seam paths
- safe, repeatable manufacturing

---

## 2. Mixers Australia Adaptation Notes (Engineering Translation)
### Key adaptation: workpiece type
Benchmark workpiece:
- large cylindrical rocket tank sections

Mixers workpiece:
- concrete mixer bowl/barrel
- three primary sections:
  - front cone
  - middle barrel section
  - rear cone

### Key adaptation: upstream manufacturing cells
Mixers workflow requires additional cells not present in the benchmark:
1) **Clamshell seam welding cell**
   - each bowl section is formed from two rolled halves (“clamshells”)
   - robot seam welds both longitudinal seams (rotate part between welds)

2) **Helix insertion + welding cell**
   - each section requires internal helical blade installation
   - robot inserts pre-rolled helix and welds to internal surface

3) **Final assembly cell (benchmark analogue)**
   - join the three finished sections and circumferentially weld joints
   - headstock/tailstock + robot on track concept applies directly

---

## 3. Process Mapping (Benchmark vs Mixers)
### Benchmark sequence (tank)
1) Place section(s) between headstock/tailstock
2) Tailstock advances, closes joints
3) Robot traverses and welds circumferential seams
4) Completed assembly removed by crane

### Mixers sequence (bowl)
**Cell A — Clamshell seam welding**
- front cone clamshell seam welds (2 seams)
- middle clamshell seam welds (2 seams)
- rear cone clamshell seam welds (2 seams)

**Cell B — Helix insertion + welding**
- front cone helix install + weld
- middle helix install + weld
- rear cone helix install + weld

**Cell C — Final assembly circumferential welding (benchmark analogue)**
- align front + middle + rear sections
- tailstock advances to close joints
- robot welds circumferential joints
- finished bowl removed by crane

---

## 4. Technical Notes / Assumptions (Internal)
- Welding process assumed **MIG**
- Benchmark system uses **ABB robot + Fronius welder**
- Mixers material set likely includes:
  - SS400
  - Rheemalloy
  - Hardox
- Material grade and thickness will influence:
  - weld procedure specification (WPS)
  - wire selection and shielding gas
  - preheat/interpass requirements
  - cycle time and heat distortion control

---

## 5. Confidentiality Control (Operational Rule)
- Do not disclose benchmark project name(s) externally.
- In client-facing documents, refer only to:
  - “internal benchmark reference system”
  - “prior heavy-duty robotic circumferential welding system experience”
- All references to Gilmore Space are restricted to internal engineering / concept justification only.

---

## 6. Internal-Only Diagram Description (Concept Reference)

### Diagram: “Headstock/Tailstock + Robot on Track” (Benchmark Architecture)
**Purpose:** Describe the reference architecture without exposing the third-party proposal externally.

**Layout (plan view):**
- A long straight base frame contains a **headstock** at one end and a **tailstock** on a **linear rail/track**.
- The **workpiece axis** runs longitudinally between headstock and tailstock.
- Parallel to the workpiece axis is a second long track carrying an **ABB welding robot**.
- A **Fronius MIG welder** is mounted adjacent to the robot/track system (either track-mounted or stationary with managed cable routing).

**Main components:**
1) **Headstock (fixed)**
   - Rigid fixture that supports and locates the workpiece section.
   - Provides alignment datum and rotational/positional reference.

2) **Tailstock (movable on track)**
   - Moves forward/backward to suit varying assembly length.
   - Applies axial force to **close section joints** (“push-fit” / squeeze-fit) prior to welding.

3) **Robot on linear track**
   - Robot traverses along the track to reach weld zones.
   - Performs circumferential weld passes and/or longitudinal weld passes depending on joint type.
   - Torch angle control maintained through robot articulation + track positioning.

4) **Workpiece support**
   - Workpiece supported along its length via rollers / support stands to control deflection.
   - Alignment maintained during clamping and welding.

5) **Material handling**
   - Overhead crane lifts completed assembly out of the cell once welding is complete.

**Functional sequence (concept):**
1. Load subassemblies onto supports between headstock and tailstock.
2. Tailstock advances to align and close the joint faces.
3. Robot traverses to weld location(s) and performs MIG weld passes.
4. Assembly is released and removed by crane.

**Mixers Australia translation:**
- Replace the long cylinder with the **3 mixer bowl sections** (front cone + middle + rear cone).
- Use the same headstock/tailstock closure method for circumferential fit-up and welding.
- Upstream cells feed completed sections to this final assembly cell.
