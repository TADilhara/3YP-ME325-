# Field Visit & Prototyping Notes: Meewathura Field Premises

**Date:** 10/06/2026  
**Purpose:** Field testing of the physical prototype for 'Guide A'.  
**Attendees:** 
* E/21/097 Dilhara
* E/21/099 Dilshan
* E/21/218 Kaushalya

**Academic Contacts:**  Prof. A.J. Mohotti (Department of Crop Science, Faculty of Agriculture, University of Peradeniya)

## Technical Prototyping Workflow

### 1. Prototype Fabrication
* **Material Selection:** To allow maximum visual tracking of the tea shoots as they slide through the channel, a 5 mm thick clear **Perspex (Acrylic)** sheet was selected.
* **Manufacturing Process:** Using the precise CAD layout from our design files (`Guide_A.pdf`), a 275 mm long scaled test segment of the guide channel was processed using the CNC laser cutter machine located in the Department of Manufacturing and Industrial Engineering.

### 2. Field Testing Methodology
* **Location:** Field experiments were conducted at the tea plots within the Meewathura premises under the guidance of Prof. A.J. Mohotti.
* **Mechanism Simulation:** To validate the tooth spacing, channel width, and sequence of the dual-sorting concept without building full spring sub-assemblies, the physical Perspex guide was passed over living bushes. Human fingers were utilized to manually simulate the mechanical resistive forces of the 1st and 2nd gates.

---

## Key Technical Observations & Encountered Challenges

The initial test confirmed that the basic sliding clearance and physical pathing of the guide work well. However, three critical behavioral problems were isolated during shoot interaction:

### 1. Second Gate Angular Misalignment (Harvestable Shoot Escape)
* **Observation:** The 1st gate successfully filters out the flexible *Arimbu* shoots. This leaves a dense mixture of optimal harvestable shoots and stiff over-mature stalks entering the zone of the 2nd gate.
* **The Problem:** Because the 2nd gate's angular geometry was identical to the first, optimal harvestable shoots were frequently forced to bend too heavily and slip right past the 2nd gate instead of triggering it. As a result, these high-quality leaves bypassed the cutting plane entirely and were left unharvested.

### 2. Shoot Clustering (Bunch of Tea Shoots Phenomenon)
* **Observation:** Tea shoots do not always enter the guide teeth as isolated, individual stalks; they frequently enter as a tightly packed **bunch of tea shoots**.
* **The Problem:** When a dense bunch of tea shoots strikes the gates, the combined collective force of multiple harvestable/mature shoots easily overpowers the gate pre-load simultaneously. This causes the gates to blow wide open, destroying the sorting selectivity and allowing *Arimbu* within the bunch to be cut, or mature wood to pass.

### 3. Forward Leaning Stalks & Collection Loss (Falling Defect)
* **Observation:** As shoots approach the final cutting plane near the reciprocating blades, they exhibit a distinct forward leaning profile (bending toward the front of the machine).
* **The Problem:** Immediately after the cutter bar shears the stem, the forward momentum and preset lean cause the severed shoot to flip and **fall down forward** onto the field floor instead of being swept backward into the collection bag. This introduces an unacceptable crop collection loss.

---

## Iterative Design Modifications & Solutions

To resolve these three field-identified bottlenecks, our group is shifting from a single geometry to an comparative array testing workflow:

* **Development of Guides B and C:** We are designing two additional guide variants with localized, targeted geometric adjustments:
  * **Optimized 2nd Gate Trajectory:** Altering the entry angle and length of the second channel slot to reduce the deflection requirements for harvestable leaves, ensuring they are consistently guided directly to the blade.
  * **Anti-Tumble Extension Profiles:** Modifying the front lip of the teeth to brace leaning stalks upright right up to the millisecond of the cut, preventing the forward falling defect.
  * **Cluster-Breaking Tooth Profiling:** Introducing subtle modifications to the entry nose of the teeth to mechanically break apart "Pokura" clusters into individual lines before they strike the first gate pocket.
