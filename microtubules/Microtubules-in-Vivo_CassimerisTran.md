# Microtubules in vivo -- Lynne Cassimeris and Phong Tran (Eds_) -- Methods in Cell Biology 97

- Microtubules have critical cellular functions:
  - Forming mitotic spindles
  - Providing tracks for vesicle and organelle movement
  - Forming the core structure of cilia and flagella

- Microtubule assembly and turnover are essential for:
  - Maintaining the genome over generations (error-free mitosis)
  - Cell shape changes and movements during development

- Methods for studying microtubules have evolved:
  - 20 years ago: Limited to injecting dye-labeled tubulin into living cells
  - Current: Expanded use of green fluorescent protein and other fluorescent variants

- New tools and techniques include:
  - Studying microtubule-associated proteins at microtubule tips
  - Photobleaching and photoactivation methods
  - High-resolution approaches like electron microscopy tomography and single molecule analyses

## Contents
- [Chapter 1: Determination of Microtubule Dynamic Instability in Living Cells](#chapter-1-determination-of-microtubule-dynamic-instability-in-living-cells)
- [Chapter 2: Analysis of Microtubule Polymerization Dynamics in Live Cells](#chapter-2-analysis-of-microtubule-polymerization-dynamics-in-live-cells)
- [Chapter 3: The Use of Fluorescence Redistribution After Photobleaching for Analysis of Cellular Microtubule Dynamics](#chapter-3-the-use-of-fluorescence-redistribution-after-photobleaching-for-analysis-of-cellular-microtubule-dynamics)
- [Chapter 4: Kinetochore Microtubule Dynamics and Attachment Stability](#chapter-4-kinetochore-microtubule-dynamics-and-attachment-stability)
- [Chapter 5: Photoactivatable Green Fluorescent Protein Tubulin](#chapter-5-photoactivatable-green-fluorescent-protein-tubulin)
- [Chapter 6: Microtubule Dynamics at the Cell Cortex Probed by TIRF Microscopy](#chapter-6-microtubule-dynamics-at-the-cell-cortex-probed-by-tirf-microscopy)
- [Chapter 7: Microtubule Dynamics in Dendritic Spines](#chapter-7-microtubule-dynamics-in-dendritic-spines)
- [Chapter 8: Protein Micropatterns using Deep UVs](#chapter-8-protein-micropatterns-using-deep-uvs)
- [Chapter 9: New and Old Reagents for Fluorescent Protein Tagging of Microtubules in Fission Yeast: Experimental and Critical Evaluation](#chapter-9-new-and-old-reagents-for-fluorescent-protein-tagging-of-microtubules-in-fission-yeast-experimental-and-critical-evaluation)
- [Chapter 10: Optical Trapping and Laser Ablation in Fission Yeast](#chapter-10-optical-trapping-and-laser-ablation-in-fission-yeast)
- [Chapter 11: Microfluidic Temperature Control Device for Studying Microtubule Dynamics in Fission Yeast](#chapter-11-microfluidic-temperature-control-device-for-studying-microtubule-dynamics-in-fission-yeast)
- [Chapter 12: Microtubule-Dependent Spatial Organization of Mitochondria in Fission Yeast](#chapter-12-Microtubule-Dependent-spatial-organization-of-mitochondria-in-fission-yeast)
- [Chapter 13: Microscopy Methods for the Study of Centriole Biogenesis and Function in Drosophila](#chapter-13-microscopy-methods-for-the-study-of-centriole-biogenesis-and-function-in-drosophila)
- [Chapter 14: Drosophila S2 Cells as a Model System to Investigate Mitotic Spindle Dynamics, Architecture, and Function\_243](#chapter-14-drosophila-s2-cells-as-a-model-system-to-investigate-mitotic-spindle-dynamics-architecture-and-function_243)
- [Chapter 15: Assessment of Mitotic Spindle Phenotypes in Drosophila S2 Cells](#chapter-15-assessment-of-mitotic-spindle-phenotypes-in-drosophila-s2-cells)

## Summary

### Chapter 1: Determination of Microtubule Dynamic Instability in Living Cells

**I. Introduction**
- Microtubules are dynamic filamentous polymers assembled from tubulin, a heterodimer composed of an a and b subunit
- In vitro and in cells, microtubules exhibit dynamic instability: nonequilibrium behavior with alternating periods of slow growth and rapid shortening at their ends
- Dynamicity refers to the overall rate of exchange between the tubulin end and the microtubule

**II. Methods and Materials**

**A. Choice of Cell Line:**
- MCF7 cells used for analysis due to their adherent growth, relatively large size, and ease of transfection or microinjection

**B. Optimization of Cell Growth Conditions:**
- Cells grown in DMEM media supplemented with 10% FBS, 2 mM L-glutamine, and 1% penicillin/streptomycin at 37C and 5% CO2

**C. Detailed Protocol for Preparation of MCF7 Cells:**
- Cell preparation for microinjection: trypsinization, centrifugation, resuspension in injection buffer (HEPES-buffered RPMI), and cell concentration
- Cell preparation for time-lapse fluorescence microscopy: cell seeding on polylysine-coated coverslips, transfection with desired construct or microinjection of fluorescent tubulin, and mounting on microscope slides

**D. Optimization of Microinjection:**
- Parameters to optimize: injection pressure, duration, and volume
- Methods for microinjection: manual or automated

**E. Preparation of Cells for Time-Lapse Fluorescence Microscopy:**
- Cell seeding on polylysine-coated coverslips
- Transfection with desired construct or microinjection of fluorescent tubulin
- Mounting on microscope slides using a coverslip holder and immersion oil

**F. Acquisition of Time-Lapse Images:**
- Use of appropriate microscope setup, objectives, and filters for fluorescence imaging
- Collecting images at desired frame rate and duration

**G. Analysis of Microtubule Dynamic Instability:**
- Analyzing time-dependent microtubule length changes using specialized software or custom scripts

**III. Discussion and Summary:**
- Role of microtubules in cell cycle progression, signaling, intracellular transport, polarization, and organizational development
- Regulation of microtubules through various proteins (MAPs, MIPs) and drugs
- Significance of studying microtubule dynamic instability in living cells using fluorescent tubulin and time-lapse microscopy.

---

#### Microtubule Dynamics in Living Cells Selection and Preparation

**Plasmids**
- Available from CLONTECH (Palo Alto, CA)
- Can be transformed using Superfect (Qiagen, Valencia, CA) or standard transfection protocols
- Technique has advantages: avoids purification and fluorescent labeling of tubulin, microinjecting cells instead
- Microtubules formed with expressed GFP-tubulin have similar dynamics as rhodamine-tubulin injected cells
- However, rhodamine-tubulin is more photostable, allowing longer recording and better signal-to-noise ratio
- With fluorescent tubulin transfection, freedom to experimentally alter other cellular characteristics

**Optimizing Cell Choice and Growth Conditions**

**Cell Line Selection**:
- Most important criterion for successful microinjection and imaging of microtubule dynamics
- Cells must:
  - Adhere tightly to the substrate for successful microinjection
  - Have a flat, well-spread morphology for successful imaging of microtubules

**Cell Growth Optimization**:

**Coverslips**:
- Glass coverslips are used for imaging due to less autofluorescence compared to plastic
- No. 1 or 1.5 thickness can be used
- Coverslips etched with grid squares marked by an identifying code are useful

**Substrate**:
- Cells grown on poly-L-lysine-treated coverslips may adhere and spread adequately
- If not, substrates like laminin, collagen, or fibronectin can promote cell adherence and spreading
- Optimal substrate and concentration vary with the cell type

---

#### Optimizing Rhodamine-Labeled Tubulin Microinjection in Living Cells for Visualization of Microtubule Dynamics

**MCF7 Cell Preparation for Microinjection and Analysis of Microtubule Dynamic Instability**

**Solutions**:
- Stock solution of poly-L-lysine (2.5 mg/ml) in sterile water, store at 4C
- Laminin and fibronectin dissolved in sterile water (0.33 mg/ml for laminin, 1.0 mg/ml for fibronectin), store at 80C
- Injection buffer: 50 mM potassium glutamate, 0.5 mM MgSO4, in 6 aliquots and freeze
- Versene solution (137 mM NaCl, 2.7 mM KCl, 1.5 mM KH2PO4, 8.1 mM Na2HPO4, 0.5 mM EDTA, pH 7.2)
- Cell culture media supplemented with 10% fetal bovine serum (FBS)
- Media supplemented with 2% FBS

**Materials**:
- Coverslips etched with identified grid squares, if necessary
- 4- or 6-well plates
- Sterile water
- Silver foil
- Silane (hexamethyldisilazane)

**Preparation of Rhodamine-Labeled Tubulin for Microinjections**:
- Label tubulin with carboxyrhodamine succinimidyl ester using the method by Hyman et al. (1991)
- Determine rhodamine:tubulin stoichiometry and adjust to 10 mg/ml in injection buffer
- Rhodamine tubulin concentrations less than 10 mg/ml appear less stable and denature when stored for long periods

**Protocol**:
1. Clean coverslips with ethanol, dry overnight, and autoclave; or clean with Alconox and rinse with sterile water
2. Incubate coverslips with 0.05 mg/ml poly-L-lysine for 2 hours at 37C
3. Incubate with laminin (10 g/ml) and fibronectin (20 g/ml) for an additional 2 hours
4. Rinse coverslips with sterile water and transfer to a new plate
5. Resuspend MCF7 cells in growth media, break up clumps, and adjust concentration to 3 x 10^6 cells/ml
6. Plate cells into 4- or 6-well plates containing pretreated coverslips
7. Serum-starve cells for 24 hours prior to microinjection by replacing normal growth media with 2% FBS media
8. Choose isolated or edge cells for microinjection and imaging
9. **Preventing Tubulin Polymerization/Clogging**:
   - Clogs can occur from tubulin polymerization/aggregation or debris
   - Inspect the microneedle with a 40 objective to distinguish between clog types

---

#### Microtubule Dynamics in Living Cells - Lab Protocol for Time-Lapse Fluorescence Imaging of Microtubules in Cancer Cells

**Tubulin Aggregation and Microinjection**

**Precautions for Minimizing Clogging**
- Pretreat injection needles (silver foil Femto tips) with silane (hexamethyldisilazane)
- Silanize several needles together in a 100 mm glass Petri dish
- Press the large part of each needle into a thin linear rolled piece of modeling clay to keep tip away from bottom of dish and prevent breakage
- Use a small syringe to place approximately five drops of hexamethyldisilazane into the bottom of the Petri dish
- Cover dish in a fume hood overnight
- Prior to microinjection, clarify tubulin solution by centrifuging at 4C for 20 min at 65,000g (35K RPM) to remove aggregates and denatured tubulin
- Transfer supernatant to a clean tube and store on ice
- Chill medium on ice prior to use and place on cells before injection to prevent polymerization in needle during injection
- Cover Femtotips, microloaders, pipette tips, Eppendorf tubes, and anything contacting the tubulin solution with clay or tissue to prevent dust from getting into the tubulin and clogging microneedle
- Use the clean function on the microinjection apparatus frequently during injection to flush out tip of microneedle

**Microinjection Pressure**
- Optimal pressure settings vary with cell size
- Deliver 10% of total cell volume for visible wave across surface without causing cell damage or blebbing
- Set compensation pressure high enough to allow constant solution flow out of needle
- Routinely use 2.1 psi injection pressure and 1.5 compensation pressure for MCF7 cells with Eppendorf 5246 Transjector and Injectman, maintaining 0.3 s injection time

**Microinjection Protocol**
- Make circular well on large glass slide using VALAP (equal parts vaseline, lanolin, paraffin)
- Place coverslip with cells in circle and cover with cold medium
- Load 2 ml of clarified rhodamine-labeled tubulin into chilled silanized Femtotip
- Inject cells under 40 objective lens of an inverted phase-contrast microscope mounted with microinjector
- After injection, return cells to incubator for at least 3 h for recovery and incorporation of labeled tubulin before imaging
- Microtubules remain strongly labeled for up to 16 hours after injection

**Addition of Drug**
- If drug effects are being studied, allow drug uptake time (e.g., taxanes and vinca alkaloids take 46 hours depending on concentrations) before imaging
- Include drug in recording medium if rapid efflux time (e.g., 2-methoxyestradiol) is being studied to maintain equilibrium between drug content of medium and cells

**Preparation of Cells for Time-Lapse Fluorescence Microscopy**
- Use recording medium: Dulbecco's modified Eagles medium lacking phenol red, supplemented with 25 mM Hepes, 4.5 g/l glucose, and 10% OxyFluor (oxygen scavenger) to minimize photo-bleaching and photodamage
- If drug with rapid efflux time is being studied, include drug in recording medium and remove equilibrated medium from incubation of second identical coverslip of cells to maintain equilibrium

**Preparation of Cell-Containing Coverslips**
- Rinse precoated coverslip containing attached cells in warm recording media and seal in Rose chamber
- Assemble chamber: place three Parafilm or silicone rings between sandwich surfaces and metal plates, and on interior surfaces of plates. Use a single internal spacer between the 25 mm diameter coverslips and ensure cells face interior of sandwich. Avoid air bubbles.

---

#### Microtubule Dynamics Tracking in Living Cells Methods and Data Analysis

**Microtubule Dynamics in Living Cells**

**Chamber Assembly**:
- Rings can be cut from sheets using a cork borer and used repeatedly
- Parts of the chamber, from top to bottom: metal plate, ring, coverslip, spacer, coverslip with cells attached, ring, and metal plate
- Flat outer surface (A) and depressions for objective/condenser touching coverslips (B) are machined

**Microscopes Used**:
- 100x 1.3 N.A. objective lens coupled to a PerkinElmer spinning disc confocal scan head
- Axiovert 200 M with an LSM510META scan head
- Leica DM-IRBE or an Axio Image MI scope with a 63 Plan Fluor 1.4 N.A. objective

**Temperature Control**:
- Stage should be enclosed in a Plexiglass/wooden box with a constant 37C temperature
- Use a forced air heating system to maintain sample temperature within 36C (precaution against upwards temperature fluctuations)

**Time-Lapse Imaging**:
- Acquire time-lapse images using a CoolSNAP HQ2 camera and Uniblitz shutter system
- Others have used Princeton Instruments Micro-max interline transfer cooled CCD camera or a CoolsnapFX CCD camera
- Typically acquire 41 sequential images at 3-s intervals with approximately 300--1500 ms exposure time and a gain of 23

**Tracking Microtubule Dynamics**:
- Track microtubules in interphase using Metamorph Software or MetaView imaging software
- Print an image of each cell, mark the microtubules with an identifier as they are tracked
- Data from Track Points sent to Microsoft Excel spreadsheet and converted to Real-Time Measurement (RTM) or Microtubule Life History Analysis Package (MT-LHAP) software

**Criteria for Analyzing Life History Traces**:
- Determine the beginning and end of each event based on overall shape of microtubule trace
- Compare traces and time-lapse sequence to determine most accurate one
- Changes less than 0.5m are considered a pause, unless occurring within growth/attenuation
- Catastrophe occurs when a microtubule switches from pause/growth to shortening, rescue is when it switches back to growth/pause

---

#### Mechanisms of Drug Action and Microtubule Dynamics in Cellular Processes

**Frequency of Rescue**
- The frequency of rescue is the number of rescues divided by total time in seconds
- Can be calculated per microtubule or population basis

**Variability of Microtubule Dynamic Instability Parameters**
- Individual microtubule dynamic instability parameters vary depending on cell type
- Mammalian interphase cells injected with rhodamine-tubulin or transfected with GFP-tagged -tubulin show a range in parameter values:
  - Mean growth rates: 6 to 20 m/min in A549 human lung carcinoma and CHO fibroblasts, respectively
  - Mean shortening rates: 9 to 32 m/min in A498 human kidney carcinoma and CHO cells, respectively
  - Mean catastrophe frequencies: 1/min to 4/min in CaOV3 ovarian adenocarcinoma and MDCK kidney cells, respectively
  - Mean rescue frequencies: 4/min to 7/min in A549 and A498 cells, respectively
- Overall, the system has allowed analysis of drug mechanisms and cellular regulators and established microtubule dynamic instability as a crucial drug target

**Acknowledgments**
- Thanks to Dr. Nikki LaPointe and Ms. Jennifer Smith for critically reading the chapter
- Study was supported by National Institute of Health CA57291

---

### Chapter 2: Analysis of Microtubule Polymerization Dynamics in Live Cells

**Introduction:**
- Discuss importance of understanding microtubule (MT) dynamics for cell processes
- Overview of dynamic instability and its regulation
- Objective is to provide an overview of techniques to observe and analyze intracellular MT dynamics through continuous labeling or fluorescently labeled proteins recognizing growing MT ends.

**Rationale:**
- Emphasize strengths and limitations of each approach
- Discuss theoretical boundaries imposed by spatial and temporal resolution limits on intracellular MT dynamics analysis.

**Microtubules (MTs):**
- Composed of a/b tubulin dimers
- Precise regulation is crucial for various cell processes, including mitosis and cell migration
- Switch between growth and shortening phases due to GTP hydrolysis in the MT lattice

**Dynamic Instability:**
- Growing MT ends: GTP-loaded tubulin polymerizes into flat open sheet that closes into a tube
- Shortening MT ends: Loss of GTP cap leads to catastrophic depolymerization and frayed ends
- Four main parameters measured: growth rate (polymerization), shortening rate (depolymerization), catastrophe frequency, rescue frequency.

**Intracellular MT Dynamics:**
- More complex due to regulation by numerous accessory proteins and physical interactions with other intracellular structures
- In cells: only plus ends exhibit dynamic instability; free minus ends are stabilized or depolymerize
- Growth and shortening rates are highly variable, fluctuate significantly over time periods
- Long pauses during which MT ends do not grow or shorten within resolution limit of light microscope
- Intracellular MTs subject to pulling and pushing forces, resulting in buckling, breakage, and movements not due to polymerization dynamics.

---

#### Visualizing Dynamic Microtubules with Fluorescent Probes

**Dynamic Imaging of Microtubules (MTs)**

**A. Probes for Visualizing Dynamic MTs:**
- Conventional analysis: Homogeneous labeling of MT network using fluorescent dyes or FP-tagged tubulin
- Fluorescent dye-conjugated tubulin has advantages over FP-tagged tubulin in terms of brightness and photobleaching
- EGFP-tagged tubulin is the most commonly used variant for dual-color imaging

**B. Preparation of Purified, Concentrated Adenovirus Particles:**

**1. Required Materials:**
- PacI-linearized and purified AdEasy viral plasmid containing gene of interest
- Transfection reagent (e.g., Lipofectamine 2000)
- Adenovirus packaging cell line (AD-293)
- Dulbecco's Modified Eagle Medium (DMEM), supplemented with 10% FBS, 10 mM MgCl2, 2mM L-glutamine, and antibiotics
- Low-density (1.2 g/ml) and high-density (1.45 g/ml) CsCl buffers in 10 mM Tris-Cl pH 8.0
- ARCA buffer: 10 mM Tris-Cl, 1 mM MgCl2, 5% sucrose, 1% glycine, and 0.05% Tween-80
- Beckman ultracentrifuge and tubes (38.5 ml for SW 28 Ti rotor and 13.2 ml for SW 41 Ti rotor)
- Econo-Pac 10DG Desalting Columns (Bio-Rad Laboratories)

**2. Adenovirus Production and Amplification:**
- Transfect AD-293 cells with the linearized AdEasy viral genome using Lipofectamine 2000 according to manufacturer's instructions.
- After transfection, collect media containing virus particles and centrifuge at low speed to remove cellular debris.
- Ultracentrifuge the media in a swinging bucket rotor (SW 28 or SW 41) with CsCl buffers to band the virus particles.
- Carefully transfer the virus band to a clean ultracentrifuge tube and dialyze against ARCA buffer using Econo-Pac columns.
- Repeat ultracentrifugation in a fixed-angle rotor (JA 17 XE or JA 20) to further purify the virus particles.
- Lyophilize the purified virus particles and resuspend them in sterile PBS or 0.9% saline solution for use.

---

#### Large-Scale Adenovirus Production and Purification Methods

**Adenovirus Production Protocol**

**1. Transfection**:
- Grow cells until cytopathic effect (CPE) is visible, approximately 12 weeks
- Change medium when it becomes acidic without disrupting cell monolayer
- Transfection efficiency can be estimated by fluorescence microscopy

**2. Harvesting Cells**:
- Gently tap plate and pipette up/down to collect cells and media into a 15ml tube
- Centrifuge at 4C, 1200 rpm for 5 minutes, discard supernatant, resuspend pellet in 1 ml sterile 10 mM Tris-Cl pH 8.0

**3. Lysing Cells**:
- Freeze/thaw cells three times at -78C and 37C
- Centrifuge at 4000 rpm for 20 minutes, 4C to remove debris
- Collect supernatant containing first-generation virus

**4. Subsequent Amplification**:
- Infect AD293 cells with harvested virus
- Repeat infection and amplification cycles until CPE is visible within 48 hours (approximately 23 cycles)

**5. Large Scale Adenovirus Production**:
- Prepare 20 plates of AD-293 cells using DMEM with 5% FBS
- Grow to confluency, dilute virus and infect cells
- Harvest cells/medium when CPE is visible

**6. Virus Purification by Cesium Chloride Density Gradient Centrifugation**:
- Prepare CsCl step gradients in 38.5ml tubes with low/high density buffers
- Carefully overlay virus supernatant on top and balance with excess Tris buffer
- Centrifuge at 20,000 rpm for 2 hours, isolate purified virus band

**7. Concentrating Virus**:
- Dilute virus to reduce density below 1.2g/ml
- Repeat purification steps with smaller gradients
- Desalt virus on a 10DG column and measure OD260 for titer estimation

**8. Imaging Intracellular MT Dynamics**:
- Use fluorescence microscopy modalities like wide-field, confocal, or TIRF
- Wide-field has limitations in thicker cell regions and only works well in flat areas

---

#### Analysis and Imaging of Microtubule Polymerization Dynamics in Live Cells

**Microtubule Polymerization Dynamics in Live Cells**

**Sarah Gierke et al. (20XX) Fig. 2:**
- Semi-manual analysis of continuously labeled MTs using time-lapse sequence and computer-assisted hand-clicking for tracking changes.
- Images acquired every 625 ms (1.6 frames per second) for 1 min with a scale bar of 5 m.
- Traces of two MT ends obtained by analyzing images with a frame rate of 0.4 frames per second, demonstrating averaging of high variability intracellular MT polymerization dynamics at slower frame rates.

**Microscopy Methods:**
- TIRF microscopy: superior contrast but only allows imaging of MTs in close proximity to the bottom cell membrane (Krylyshkina et al., 2003; Chapter 6, this book).
- Spinning disk confocal microscopy: versatile method that combines thin optical sectioning with better sample penetration compared with TIRF.
- Acquire images at best possible spatial resolution (resolution limit of fluorescence light microscope is ~250 nm).
- Use high-resolution scientific grade CCD camera to oversample the optical resolution and fulfill Nyquist sampling criterion.
- Avoid two-photon microscopy or binning, as they halve the optical resolution.
- Optimized imaging conditions include cells grown in two dimensions on #1.5 cover glasses and environmentally controlled system.

**Imaging Challenges:**
- Higher resolution imaging is more challenging for three-dimensional samples.
- Use a high-resolution CSU-10 spinning disk confocal head, 488 nm and 561 nm solid-state lasers, and high-resolution CoolSNAP cooled CCD camera to achieve highest spatial resolution possible with conventional light microscopy.
- Control image acquisition using Nikon NIS-Elements software.
- Minimize sample exposure and photodamage by maintaining high shutter efficiency, using optimized emission filter sets, and minimizing exposure times.

**End of Text Summary:**
The provided text discusses the semi-manual analysis of continuously labeled microtubules (MTs) using time-lapse sequences and computer-assisted hand-clicking for tracking changes. This method allows demonstrating the high variability in intracellular MT polymerization dynamics at slower frame rates by analyzing images with a simulated frame rate of 0.4 frames per second. The authors recommend using spinning disk confocal microscopy as a versatile and effective method to image dynamic MTs due to its combination of thin optical sectioning, better sample penetration, and ability to achieve high spatial resolution. They also emphasize the importance of optimizing imaging conditions for accurate analysis of MT polymerization dynamics in live cells.

---

#### Analysis and Limitations of Microtubule Dynamics Tracking in Live Cells

**Microtubule Polymerization Dynamics Analysis in Live Cells**

**Tracking MT End Displacements**:
- Use the tracking function in NIS-Elements (Nikon) or similar functions in other software packages (e.g., MetaMorph, ImageJ)
- Output: List of positions/displacements of the MT end over time
- Important to remember: List does not include information on whether an end displacement represents growth or shortening

**Designating Shortening Events**:
- After initial tracking, go through list a second time to designate shortening events by negative numbers
- MT end displacement can then be plotted and analyzed in various ways to calculate growth/shortening rates, transition frequencies, and the percent of time MTs spend in growth, shortening, or pause phases.

**Calculating Instantaneous Growth/Shortening Rates**:
- Due to large intracellular MT growth rate variations, it is difficult to a priori designate constant growth/shortening velocity phases
- Calculate instantaneous growth/shortening rates on a frame-to-frame basis
- Positional uncertainty and hand-clicking errors introduce limitations

**Drawbacks of Method**:
- At very short time intervals, positional error becomes dominant, resulting in different MT dynamics parameter measurements depending on the frame rate
- Simulated frame rates obtained by temporal subsampling truncate lower end of true growth/shortening rate populations and overestimate average rates.

**Transition Frequencies**:
- Catastrophe frequency: Number of transitions from growth to shortening divided by time MTs spend in growth
- Rescue frequency: Number of transitions from shortening to growth divided by time MTs spend in shortening
- Limitations: Imaging frame rate defines upper boundary for transition frequencies, and pauses/growth intervals shorter than the imaging interval cannot be observed

**Conclusion**:
- Semi-manual analysis is best performed on time-lapse sequences acquired every 25 seconds at high spatial resolution
- It is important to only compare quantifications obtained from time-lapse sequences acquired at identical magnification and frame rate.

---

#### Visualizing MT Ends with TIP Proteins Fluorescent Labeling of Growing Microtubules

**Analysis of Microtubule Polymerization Dynamics in Live Cells**

**MT Fluorescent Speckle Microscopy (FSM)**
- Distinguishes between MT polymerization dynamics and translocation
- Reveals different types of MT movement that would be misinterpreted as polymerization if the MT were homogenously labeled
- Uses fluorescently speckled tubulin subunits to create intensity variations along the MT
- Best contrast achieved at labeling ratios below 1%
- Simple image processing techniques increase speckle contrast for better analysis

**Imaging and Analysis of Growing MT Ends**

**Probes to Visualize Growing MT Ends**
- Conventional analysis of intracellular MT dynamics is subjective and biased due to the inability to observe growing ends clearly in more central cell areas
- Fluorescently tagged proteins that specifically recognize growing MT plus ends (TIPs) allow for clear visualization of intracellular MT dynamics
- TIPs, such as EBs, bind weakly along MTs, making it possible to observe growing MT ends in more central cell areas
- C-terminally tagged EB1- or EB3-EGFP constructs are commonly used for this purpose due to the exponential decay of available binding sites and rapid kinetics
- Concerns about disruption of endogenous localization of other TIPs when using EB-EGFP constructs, but low-level expression appears relatively benign
- Alternative TIPs, such as CLIP-170 or CLASPs, can be used to validate experimental results and eliminate potential artifacts
- Minimal EB-binding motif identified for plus end localization, which should allow for the engineering of artificial TIPs with minimal interference in intracellular MT dynamics.

---

#### Quantitative Analysis of Microtubule Dynamics in Live Cells Methods and Challenges

**Computational Tracking and Analysis of TIP Dynamics**
- **Determining Growth Rates:**
  - Time-lapse sequences of FP-tagged TIPs can be used to calculate growth rates directly from comet distance or through computer tracking methods.
- **Challenges:**
  - Difficulty in measuring pause and shortening phases as MT ends are not visible during these times.
  - To address this, a computational framework has been developed to analyze TIP time-lapse sequences in three steps: detection, tracking, and geometrical cluster analysis.

**TIP Dynamics Analysis Framework:**
1. **Detecting Objects:**
   - Band-pass filter is used to detect objects of TIP comet size scale.
2. **Tracking:**
   - Automated single-particle tracking yields statistically large populations of MT growth rates.
3. **Geometrical Cluster Analysis:**
   - Tracks belonging to the same MT are linked using geometrical constraints and a cost function algorithm.
   - Limitations: misses long shortening phases, slow and short growth phases, terminal shortening phases.

**Advantages of this Approach:**
- Large numbers of MTs can be analyzed relatively quickly.
- Useful for comparing different experimental conditions on a relative basis.

**Availability:**
- The plusTipTracker software package is soon to be available at http://lccb.hms.harvard.edu.

**Conclusion:**
- Spatiotemporal regulation of intracellular MT dynamics is important in many aspects of cell biology, leading to high interest in methods for quantitative analysis of MT dynamics.
- Absolute MT dynamics parameters are limited by imaging conditions and analysis methods, making comparisons between experimental conditions more valuable.

---

#### Analyzing Microtubule Polymerization Dynamics in Live Cells with Computational Clustering of TIPs

**Microtubule Polymerization Dynamics in Live Cells**

**Problem Aggravation**:
- MT polymerization dynamics are more variable in cells due to regulation by associated proteins
- New methods for analyzing MT dynamics are needed

**New Methods Outlook**:
- Utilizes computational clustering of MT growth tracks defined by association of fluorescently labeled TIPs with growing MT ends

**Acknowledgments**:
- S.G.: NSF Graduate Research Fellowship
- T.W.: National Institutes of Health grant R01 GM079139
- This research conducted in part at a facility supported by the Research Facilities Improvement Program C06 RR16490

---

### Chapter 3: The Use of Fluorescence Redistribution After Photobleaching for Analysis of Cellular Microtubule Dynamics

**Microtubules and Fluorescence Redistribution After Photobleaching (FRAP)**

**I. Introduction**
- **Rationale**: Understanding MT dynamics is crucial for studying cellular processes
- FRAP method used since the 1970s to investigate protein mobility and dynamics in cells
- Reveals information about dynamic properties of proteins or structures, such as MTs

**II. Choice and Preparation of Cells**
- **Cell Type**: Mammalian cells
- **General Tissue Culture Conditions**: Proper growth media and environment are essential for cell viability during imaging

**III. Maintaining Cell Viability While Imaging**
- **Maintenance and Imaging Media**: Choosing appropriate media to maintain cell health during experiments
- **Maintaining Constant Temperature**: Ensuring consistent temperature in the imaging chamber
- **Choice of FRAP/Imaging Chamber**: Selecting a suitable chamber for imaging

**IV. Imaging and Data Analysis**
- **The Imaging and Photobleaching System**: Describes the system used for imaging and photobleaching
- **Microscopy**: Explanation of microscopy techniques used in FRAP experiments
- **Measuring Fluorescence Recovery**: Explains how to measure fluorescence recovery after photobleaching
- **Data Analysis**: Discusses methods for analyzing the data collected during an FRAP experiment

**V. Summary and Conclusions**
- FRAP is a valuable tool for studying MT dynamics in living cells, although it does not yet provide information on individual MT dynamics parameters.

---

#### FRAP Experimentation of Microtubules in PtK-2 Cells

**FRAP Analysis of Cellular Microtubules**

**I. FRAP Measurements**
- Unlike with conventional FRAP, photobleached polymers undergoing dynamic instability do not exhibit simple diffusion-limited recovery of fluorescent tubulin
- Recovery profile is an estimate of total turnover in polymer for a given cellular area dependent on the composite dynamic profile of the MT array
- Despite limitations, FRAP experiments have provided significant insight into complex regulation of MT dynamics within cells

**II. Cell Choice and Preparation**
**A. Cell Type Choice**
- Variety of cell lines used for FRAP studies of the MT cytoskeleton
- Cells must be either expressing GFP-tubulin or injected with fluorescently labeled tubulin
- Flatter cells like PtK-1 or 2, COS-7, RPE-1, NIH/3T3, and LLCPK are more suitable for FRAP analysis as they do not round up during mitosis
- **PtK-T cells**: stably expressing GFP-alpha tubulin used for FRAP experiments

**B. General Tissue Culture Conditions**
1. Check confluency of cells prior to passaging
2. Prepare coverslips for plating by placing in a plate, sterilizing with ethanol and allowing to dry
3. Trypsinize cells and prepare dilutions; plate at concentrations ranging from 1/3 to 1/5
4. Allow growth time in CO2 incubator (35 days)
5. Use Complete Opti-MEM medium supplemented with 20 mM HEPES, penicillin/streptomycin, and GlutaMAX for FRAP imaging
6. Maintain constant temperature using an air stream incubator (ASI) or other available temperature-controlled stage or chamber
7. Monitor temperature using a digital thermometer probe taped to the specimen holder on the microscope stage
8. Choose appropriate imaging chamber based on experiment duration: short-term or long-term

**III. Maintaining Cell Viability During Imaging**
**A. Imaging Media and Oxygen Scavenging Mix**
1. Use complete Opti-MEM medium supplemented with 20 mM HEPES, penicillin/streptomycin, GlutaMAX, and oxygen scavenging mix for FRAP/imaging experiments
2. Prepare the media in a capped conical and warm it on a slide warmer before imaging chamber assembly
3. Warm the microscope stage and metal ring using the ASI
4. Transfer the coverslip with cells onto a 35 mm culture plate containing prewarmed imaging media, overlay the coverslip, and carefully seal with VALAP or other appropriate mounting medium
5. Monitor temperature during the experiment to maintain cell health and prevent photodamage
6. Discard chamber after 20-30 minutes of imaging (short-term) or replace with fresh media as needed for longer experiments (long-term)
7. Use a rose chamber for long-term live imaging, which holds up to 1 ml of media under mineral oil while allowing high-resolution imaging through a cover glass
8. Keep the chamber clean by wetting a kimwipe or lens paper with ddH2O and gently drawing it across the coverslip and slide before mounting on the microscope stage
9. Record the time of imaging and discard/replace the chamber after a certain duration to maintain cell health and prevent photodamage.

---

#### Live Cell FRAP Imaging Protocol for Microtubules

**FRAP Experiment for Cellular Microtubules Analysis**

**Components of FRAP System:**
- Widefield or confocal microscope system with rapid fluorescence extinction and high dynamic range images
- Nikon TE2000U inverted microscope
- Yokogawa CSU-10 spinning disk confocal head
- 75 mW krypton/argon illumination laser
- Photometrics Cascade II EM-CCD camera (60C, 512 x 512 pixels, 16 m pixels) with wide-band emission filters
- Additional laser (300 mW, 488 nm Argon) for photobleaching

**Microscopy**:
- Balance two goals: accurate time evolution of fluorescence recovery and enough signal to estimate relative level of fluorescence recovery
- Recommended exposure time and illumination intensity for a signal-to-noise ratio of 5
- Determine linearity of detector using beads with calibrated fluorescence intensities
- Variable exposure times based on cell type: interphase cells (300 ms), mitotic cells (500 ms)
- Interval between images depends on dynamic properties of sample being imaged
  - Collect sufficient number of images for accurate estimation of t1/2 recovery time

**Photobleaching Pulse**:
- Minimum size bleach zone to collect required information
- Critical to bleach equivalent positions in each cell due to different MT dynamics at interior vs edge and near pole or spindle equator
- Determine exposure time for photo-bleaching laser empirically without killing the cell
- Not critical to bleach 100% of fluorescence but easier to determine recovery properties with more extensive bleaching.

---

#### FRAP Experiment and Analysis in Cellular Microtubules Measuring Fluorescence Recovery

**FRAP Experiment Procedure**
* Turn on all components of FRAP/imaging setup and prewarm stage and equipment
* Place cell-containing chamber on microscope stage, record start time
* Scan surface of coverslip quickly to find cell of interest
* Center cell in eyepiece or live view camera
* Adjust focus and include unbleached areas for data collection
* Set acquisition settings (signal-to-noise ratio, exposure time)
* Use software to specify region of interest (ROI) and duration of photobleaching
* Acquire three reference images before bleaching
* Use laser to bleach specified area
* Continue acquiring images postbleach at same exposure time and interval as prebleach

**FRAP Analysis**
* Measure quantitative changes in relative image intensity for reliable t1/2 and fluorescence recovery measurements
* Reject data with obvious specimen or focal drift
* Use Metamorph software to create ROIs and tabulate fluorescence intensity values with time stamps
* Export data to spreadsheet, scientific graphing software, or command line-driven data analysis software (e.g., MATLAB) for further processing
* Quantifiable properties from FRAP experiments: extent, modal property (mono or multiphase), halftime(s) of fluorescence recovery
* Define regions for data collection: background (bg), bleached region (bl), and unbleached region (ub). Subtract background value to obtain background-corrected data (bl0 and ub0).

---

#### Data Analysis and Photobleaching Correction in Fluorescence Recovery After Photobleaching FRAP

**FRAP (Fluorescence Recovery After Photobleaching) Analysis for Cellular Microtubules**

**Data Collection:**
- For interphase cells: draw ROI on unbleached region, record average fluorescence intensity
- For mitotic cells: draw ROI on unexposed spindle half, collect average fluorescence intensity
- Bleached region: single ROI inside borders to measure relative intensity values
  - Draw box for interphase and mitotic cells, exclude unbleached area
  - Record average fluorescence intensity for each frame of time-lapse series

**Data Analysis:**
1. Plot Raw Data:
   - Rapid inspection for fluctuations in bleached and unbleached regions
   - Assess background measurement constancy across imaging duration
2. Background Subtraction:
   - Subtract background (bg) value from all other data associated with image
3. Correcting for Photobleaching:
   - FRAP data must be corrected for photobleaching that occurs during image capture
   - Methods to account for photobleaching depend on noise in intensity measurements and degree of photobleaching over experiment duration
45. **Data Analysis (Continued)**
   - Create separate column for background-corrected bleached (bl0) and unbleached (ub0) data
   - Correct for photobleaching that occurs during image capture:
      a. Use individual ub0 data points to correct bl0 or model fluorescence loss over time
      b. Fit single exponential decay curve to unbleached measurements for low signal samples
      c. Use other models if necessary, but sufficient reason must be provided
   - Add photodissipation estimate to ub0 data or divide bl0 by ub0
5. Reporting:
   - Explicitly state methods and measurement used for photobleach correction in any manuscript reporting these measurements.

---

#### FRAP Analysis and Data Fitting of Cellular Microtubules

**FRAP Analysis of Cellular Microtubules**

**Background-corrected UB data (ub0)**:
- Paste into a subsequent column, each cell represents a single time point
- Plot as scatter plot: X = time, Y = ub0

**Determine best mathematical model for UB0 data**:
- Fit to exponential, power, or logarithmic models
- Use R2 value or residuals test to find the best fit model
- Record values of the equation (PDM) for analysis as photodissipation model (PDM)

**Calculate theoretical fluorescence intensity (TFI)**:
- TFI at each time point by plugging in the value of X into the PDM equation
- Create a new column called "theoretical fluorescence intensity" (TFI)

**Calculate actual fluorescence loss (FL)**:
- Subtract TFI at each time from the initial (T = 0) TFI value

**FRAP Analysis of Cellular Microtubules**:

**FRAP analysis**:
- Examine data from unbleached part to create PDM to correct bleaching in fluorescence recovery data
- Example: Fluorescence intensity recovers as monophasic, indicating single recovery event with a half-time (t1/2)

**Correcting the Data**:
- Add the estimated FL to corrected bl data
- Multiply bl0 by the ratio of initial ub0 and bl0 values if they are not equal
- Divide bl0 by ub0 for each data point, renormalize for determining percent recovery

**Developing Normalized Fluorescence Recovery Curves**:

**Subtracting initial measurement from subsequent points**:
- Reset time axis so first bleached measurement is at 0

**Normalizing the Data**:
- Divide all values by prebleach intensity to estimate percent of total recovery, modal nature of curve, and approximate half-time
- Be clear if the fitting routine assumes the model goes from 0 to 1 (100% recovery) or not

---

#### FRAP Data Analysis and Interpretation in Microtubule Studies

**FRAP Analysis of Cellular Microtubules**

**Experimental vs. Control Specimens**:
- Attempt to fit a single exponential model to all or a significant portion of recovery data
- Determine what model to use for comparing control and experimental samples:
  - Model-fitting criteria
  - Extrapolation to biological properties being explored

**Data Descriptions**:
- Interphase cells: best described by a single (monophasic) exponential association model
- Mitotic spindles: best fit by a biphasic exponential association model

**Calculating t1/2 Values**:
- Halftime to fluorescence recovery (t1/2) can be calculated directly using graphing software or manually
- For monophasic model, there will be one t1/2; for biphasic, there will be two t1/2 values

**Determining Percent of Fluorescence Recovery**:
- If there is a stable underlying MT population, corrected fluorescence recovery may not return to prebleach intensity level
- Determine percent recovery:
  - **Monophasic curve**: Calculate percentage of total recovery using exponential function and normalize data to 0-1 or 0-100%
  - **Biphasic curve**: Extrapolate fluorescence recovery for each phase, add values, and calculate percent contribution

**Compiling Data from Multiple FRAP Experiments**:
- Calculate t1/2 and % fluorescence recovery averages, standard deviations, and SEM for each experimental condition

---

#### Quantitative Analysis of Microtubule Dynamics in Living Cells

**FRAP Methods for Assessing Dynamics of Microtubules (MTs)**
* **FRAP of Cellular MTs**: assesses overall dynamic state of MTs
* Developed methods to simplify acquisition and analysis:
+ Compare both t1/2 and fluorescence recovery values after experimental manipulations
+ Provides a tool for understanding impact on MTs at different stages during cell cycle
* Applicable to yeast and plant cells with some modifications (e.g., decrease in region sizes used for collecting fluorescence data)
* Methods can be compared to studies on mitotic spindles in mammalian cells

**FRAP Procedure**:
1. Define experimental conditions:
- Control or perturbation groups
2. Perform FRAP experiments:
- Record time series of fluorescence intensity at a specific location within cell
3. Analyze data:
- Calculate average percent fluorescence recovery for each condition
4. Compare experimental conditions:
- Use two-tailed student's t-test with a confidence interval of 95% or better to determine statistically significant differences between conditions

**FRAP Applications**:
- Understanding impact of different proteins or treatments on MT dynamics and function at various stages during cell cycle.

---

### Chapter 4: Kinetochore Microtubule Dynamics and Attachment Stability

**I. Introduction**
- Mitosis is a process of cell division involving genetic material distribution
- Successful division requires persistent but compliant attachments between kinetochores and spindle microtubules (MTs)
- Kinetochore MT attachment stability and dynamic instability must be controlled to avoid errors in chromosome segregation

**II. Materials**

**A. Cells**:
- Adherent cell lines for experimental approaches assessing kinetochore MT attachment stability and dynamics
- **HeLa cells**: easy to culture, transfect, synchronize, but round up during mitosis (unfavorable for imaging)
- **PtK1 cells**: remain flat during mitosis, amenable to microscopic imaging, have fewer chromosomes than HeLa

**B. Cell Culture, Treatments, Transfection, and Live-Cell Imaging**:
- HeLa cell culture media: Dulbecco's Modified Eagle Medium (DMEM) supplemented with 10% FBS and antibiotic-antimycotic
- PtK1 cell culture media: Ham's F-12 Medium supplemented with 10% FBS and antibiotic-antimycotic
- Sterile coverslips prepared by adding empty coverslips to a beaker, separating gently, and autoclaving

**III. Methods**:
- RNA interference-based protein depletion
- Immunofluorescence staining
- Cold-induced MT depolymerization assay
- Inter-kinetochore tension measurement
- Kinetochore MT turnover dynamics
- Kinetochore MT polymerization/depolymerization dynamics correction

---

#### RNA Interference Protein Depletion in Kinetochore Microtubule Dynamics

**Kinetochore Microtubule Dynamics and Attachment Stability**

**Immunofluorescence Protocols:**
- **PHEM Buffer**: 60 mM PIPES, 25 mM HEPES, 1 mM MgCl2, pH 7.0
- **2X PHEM Buffer**: 120 mM PIPES, 50 mM HEPES, 20 mM EGTA, 8 mM MgSO4, pH 7.0
- **PHEM-T Buffer**: PHEM + 0.1% Triton X-100, sonicated for 5 minutes in a sonicator bath immediately prior to use
- **Permeabilization Buffer**: PHEM + 0.5% Triton X-100, sonicated for 5 minutes in a sonicator bath immediately prior to use
- **Fixative**: 4% paraformaldehyde diluted from 16% stock solution into PHEM buffer
- **Bovine Serum Albumin (BSA)**: Prepare 10 mg/ml stock in water, aliquot and store at -20C. For use: dilute to 1x concentration with PBS or PHEM buffer, then add Tween 20 to a final concentration of 0.1%
- **Primary Antibodies**: anti--tubulin (DM1A), anti-Hec1 (9G3), anti-centromere, CENP-A
- **Secondary Antibodies**: donkey anti-human IgG, Cy-5 conjugated; donkey anti-mouse IgG, rhodamine Red-X conjugated; donkey anti-mouse IgG, DyLight 488 conjugated

**Coverglass Staining**:
- **Preparation**: clean glass coverslips with detergent, rinse with water, and dry
- **Mounting Media/Antifade Solution**: 0.5% N-propyl gallate in 90% glycerol diluted in PHEM buffer

**RNA Interference**:
- **Protein Depletion by siRNAs**: RNAi-based protein depletion using siRNAs and the transfection agent Fugene 6, as described for HeLa cells above.
- **Rescue Experiments**: Express wild-type or mutant versions of a protein of interest after depleting endogenous levels to determine their contribution to kinetochore MT attachment stability and dynamics.

---

#### Microtubule Dynamics in Cell Division Immunofluorescence Methods

**General Methods for Immunofluorescence Staining**

**Before Silence and Rescue Experiments:**
- Thoroughly characterize phenotype of siRNA-transfected cells:
  * Analyze by Western blotting and fluorescence intensity measurements
  - Determine extent of depletion and optimal post-transfection time points for kinetochore MT assays

**Points to Consider:**
1. **Characterizing Phenotype**: Before silence and rescue experiments, it is important to thoroughly characterize the phenotype of siRNA-transfected cells alone to determine:
   - Extent of depletion (analyzed by Western blotting and fluorescence intensity measurements)
   - Timing of depletion (determine optimal post-transfection time points for kinetochore MT assays)
2. **Stability of Exogenously Expressed Protein**: For silence and rescue experiments, ensure that exogenously expressed protein is stable and its coding sequence is not targeted for destruction by the RNAi machinery:
   - Design siRNAs to target noncoding regions (3' UTR) or mutate expression constructs at the siRNA target site to avoid recognition by the siRNA
3. **Labeling SiRNAs**: Use directly fluorescently labeled siRNAs for confirmation of positive transfection on a cell-to-cell basis by fluorescence microscopy
4. **Immunofluorescence Staining Protocol**:
   - Rinse coverslips in PHEM buffer prewarmed to 37C
   - Fix cells for 10 seconds in fixative prewarmed to 37C
   - Permeabilize cells for 5 minutes in permeabilization solution prewarmed to 37C
   - Rinse cells in PHEM buffer and incubate in PHEM-T (3  5 min)
   - Block nonspecific antibody binding with 10% BSA
   - Incubate coverslips with primary antibodies diluted in 5% BSA for 1 hour at 37C or 12 hours at 4C
   - Wash cells with PHEM-T (3  5 min) and incubate with fluorescently conjugated secondary antibodies diluted 1:300 in 5% BSA for 1 hour at room temperature, protected from light
   - Rinse coverslips with PHEM-T (3  5 min), followed by a quick rinse in PHEM
   - Stain DNA with DAPI diluted to 2 ng/ml in PHEM for 1 minute
   - Mount the slides using mounting media and antifade solution, then store them in the dark at 4C.
5. **Optimizing New Antibodies**: When characterizing a new antibody, optimize the immunofluorescence protocol by trying both protocols with PHEM buffer and methanol as the fixative. Adjust steps accordingly to achieve desired results.

---

#### Cold-Induced Microtubule Depolymerization Assay in HeLa Cells

**Cold-Induced Microtubule Depolymerization Assay**

**Background:**
- Kinetochore microtubules (MTs) are stable during mitosis in mammalian cells
- Initiated at onset of mitosis between kinetochore and MT from closest spindle pole
- Rapidly transported along length of MT towards attached pole
- Lateral attachments become end-on, form kinetochore fiber
- Important for proper chromosome alignment and anaphase initiation

**Observations:**
- Decades ago: stable kinetochore MTs observed against non-kinetochore MT depolymerization conditions like cold treatment, heat, hydrostatic pressure, or drugs

**Protocol:**
1. Seed HeLa cells on sterile coverslips in 35mm dishes until ~80% confluency
2. Cool dishes in shallow ice bath for 15 min and remove from bath
3. Aspirate media and replace with precooled growth media (4C)
4. Fix and permeabilize cells using room temperature buffers instead of 37C
5. For PtK1 cells: add calcium, incubate in MT destabilization buffer for 30 min, then continue with immunofluorescence protocol

**Data Acquisition:**
- Collect through-series (Z-stack) images of cells using 60x or 100x objective and 200nm step size
- Import TIFF files into MetaMorph Imaging software program

**Analysis:**
- Sum total tubulin fluorescence of a 20-image Z-stack for quantification
- Create circles for constant area (mitotic spindle) and background measurement
- Determine integrated fluorescence intensity within both circles using Region Measurements function
- Subtract background from total fluorescence to calculate portion due to kinetochore MTs.

---

#### Measuring Inter-Kinetochore Distance in Mitotic Cells for Analyzing Kinetochore Microtubule Dynamics and Attachment Stability

**Tubulin Fluorescence Measurement**
* Calculate background-subtracted tubulin fluorescence intensity using the following equation: Fspindle = (FS * [(FL / AS) \* (AL / C0AS)])
+ FS: total integrated fluorescence intensity with the small circle
+ FL: total integrated fluorescence intensity with the large circle
+ AS: area of the small circle
+ AL: area of the large circle
+ Fspindle: final value for background-corrected spindle fluorescence intensity
* Measure tubulin fluorescence intensity from at least 20 cells in each experimental condition
* Average spindle fluorescence intensities and normalize to 1 for comparison

**Cold Stable MT Polymer**
* Ideally, only kinetochore fibers are retained during cold incubation
* Adequate depolymerization is confirmed by checking for little MT polymer in interphase cells
* Different cell types may require unique assay conditions for optimal MT depolymerization

**Inter-Kinetochore Tension**
* When sister kinetochores accumulate stable MTs, tension is established across the centromere region
* Measuring inter-kinetochore distances is a useful assay to gauge inter-kinetochore tension and presence of stable kinetochore MT attachments

**Kinetochore Microtubule Dynamics and Attachment Stability**
* Procedure:
+ Permeabilize, fix, and immunostain cells using anti-kinetochore primary antibody (e.g., Hec1 or CENP-A) and anti-alpha tubulin antibody
+ Collect a Z-stack of images for each cell and measure inter-kinetochore distances between two kinetochores in the same plane of focus
+ Determine control rest length by measuring inter-kinetochore distance in prophase cells or by treating with nocodazole to depolymerize MTs
+ Determine control stretched length by measuring sister kinetochore pairs in metaphase of untreated cells
* Points to consider:
+ Depending on experimental condition, some cells may have uniform population of kinetochore pairs or discrete subpopulations with different inter-kinetochore distances.
+ In case of a subset of stranded kinetochore pairs at the spindle poles, it is helpful to keep distinct populations segregated when analyzing and interpreting datasets.

---

#### Kinetochore Microtubule Dynamics and Turnover in Mitosis through Photoactivation

**Kinetochore Microtubule Dynamics and Attachment Stability**

**Measuring Inter-kinetochore Distances**:
- Reflects inter-kinetochore tension, not intra-kinetochore tension
- Recent reports indicate silencing of the spindle requires generation of intra-kinetochore tension
- For these experiments, intra-kinetochore distance is measured between a protein in the kinetochore outer domain and a protein in the inner domain

**Kinetochore MT Turnover**:
- Stability of kinetochore MT attachments must be regulated throughout mitosis to ensure accurate chromosome segregation
- Early in mitosis, kinetochore MTs are labile to allow release of erroneous attachments
- Late in mitosis, kinetochore MTs are stabilized to generate forces for chromosome congression and silence the spindle assembly checkpoint
- Kinetochore MT turnover rate can be measured using a photoactivation assay with fluorescence photoactivation
- Fluorescent marks on tubulin fade quickly in free dimeric tubulin and non-kinetochore MTs, while they persist in kinetochore fibers due to their selective stability

---

#### Photoactivated Microtubule Dynamics Analysis in PtK1 Cells

**Photoactivation Experiments using Mosaic Laser Ablation/Photoration System**
- Requires a spinning disc confocal microscope equipped with Mosaic Laser Ablation/Photoactivation System
- Allows for software-driven demarcation and activation of user-defined regions on the specimen field

**Preparing for Experiments:**
1. Locate mitotic cell using transmitted light
2. Capture DIC and fluorescence (473 nm) preactivation images
3. Create narrow rectangular region adjacent to chromosome mass
4. Activate tubulin fluorescence within the rectangular region for 100 ms
5. Acquire DIC and 473 nm excitation images immediately after activation, 10 seconds postactivation, and every 20 seconds for 10 minutes
6. Draw larger rectangle encompassing entire cell, activate tubulin fluorescence, and acquire final fluorescence image

**Data Analysis:**
1. Determine loss of tubulin fluorescence due to photobleaching
   a. Measure fluorescence intensity of activated tubulin in taxol-treated cells using a rectangular region that encompasses the initial bleached region
   b. Record total integrated fluorescence within this region (A)
2. Determine background fluorescence
   a. Move rectangle off the activated tubulin region and place it at a similar distance from chromosome mass in opposite half-spindle
   b. Record total integrated fluorescence within this region (B)
3. Subtract background fluorescence measurement (B) from fluorescence intensity measurements (A) of activated region for each time point
4. Calculate percent loss of fluorescence at each time point relative to initial postactivation time point (photobleaching correction value)
5. Average the percent loss at each time point from data collected in at least 10 cells
6. For experimental data sets, determine fluorescence dissipation as described above.

---

#### Monitoring Kinetochore MT Attachment and Error Correction in Live Cells

**Live Cell Fluorescence Imaging: MT Attachment Stability and Error Correction**

**Background:**
- Photobleaching correction for fluorescent region movement during activation
- Double exponential curve fit to determine MT half-life values
- Importance of kinetochore MT stability in chromosome biorientation

**Techniques:**
1. Mosaic system: activating a small, bar-shaped region on the specimen
2. Narrow region activation using a slit and focusing light
3. Live-cell fluorescence imaging considerations (choice of microscope, temperature control, photo-bleaching)

**Errors in Kinetochore Attachment:**
1. Merotelic: one kinetochore attaches to MTs from both poles
2. Syntelic: both kinetochores of a sister pair attach to MTs from one pole
3. Monotelic: one kinetochore attached to MTs emanating from one pole, while its sister remains unattached
4. Importance of dynamic cycles for error correction through Aurora B serine/threonine kinase
5. Eg5-inhibitor washout experiment to gauge ability of cells to correct kinetochore attachment errors

**Procedure:**
1. Culture HeLa or PtK1 cells on multiple coverslips until 80% confluency
2. Incubate with monastrol for 2 hours at 37C and 5% CO2 to induce monopolar spindles
3. Prepare one coverslip for immunofluorescence (time point 0)
4. Wash off monastrol and incubate in MG132-containing media for 1 hour, removing coverslips for immunofluorescence at intervals: 20, 40, and 60 minutes after washout initiation.
5. Fix, permeabilize, and immunostain cells using anti--tubulin antibody and either anti-centromere or kinetochore antibody; counterstain with DAPI.

---

#### Characterizing Kinetochore Dynamics in Live Cells Using Fluorescence Microscopy

**Image Acquisition Using Fluorescence Microscope:**
- Capture Z-stacks of mitotic cells using a fluorescence microscope, with a step size of 200 nm
- Analyze at least 75 cells per time point and create maximum intensity projections for each cell
- Categorize mitotic cells based on phenotype: monopolar, bipolar prometaphase, or bipolar metaphase

**Controlling Experiment:**
- Use Aurora B kinase inhibitor (e.g., monastrol) to prevent efficient correction of kinetochore MT attachment errors and observe a delay in bipolar spindle assembly and formation of bipolar metaphase cells

**Kinetochore MT Polymerization/Depolymerization Dynamics:**
- Mitotic microtubules undergo dynamic instability, with periodic growth and shortening at plus-ends
- This behavior is essential for chromosome movements during anaphase
- Understanding the mechanisms regulating kinetochore oscillations is ongoing research

**Data Acquisition:**
- Culture cells expressing fluorescently labeled kinetochore protein on sterile coverslips or glass-bottom dishes
- Collect Z-stack images every 3 seconds for a total of 10 minutes, then generate maximum projection time-lapses
- Convert time-lapse sequences into TIFF files and import into MetaMorph to create an image stack (STK file)

**Data Analysis:**
- Use the Kymograph Function or Montage function in MetaMorph to analyze kinetochore oscillations
- Choose well-separated sister kinetochore pairs with minimal movement during imaging for accurate results.

---

#### Kinetochore Movement and Poleward Flux Analysis in Mitosis

**Tracking Kinetochore Oscillations:**

**Preparation:**
- Ensure proper image calibration in MetaMorph for objective used during acquisition
- Assign time interval for tracking (Track Points > Set Interval)
- Choose parameters to be exported to Excel spreadsheet: image name, time, distance, velocity

**Manual Tracking:**
- Place cursor over kinetore centroid and click on each frame of time-lapse sequence using Track Points function
- Export data to Excel spreadsheet

**Analyzing Data:**
1. Velocity: MetaMorph calculates velocity, export average velocity over time
2. Pause: Determine percentage time spent in pause by identifying non-moving kinetochores for 6s and dividing sum by total time of sequence
3. Average excursion length: Subtract regression line values from original position data; calculate deviation from average position using SigmaPlot or other software
4. Deviation from average position sensitive to oscillation curve shape, especially time spent in pause at switching point
5. **Points to Consider:** Choose appropriate kinetochore protein for fluorescent tagging, ensure exogenous protein does not alter wild-type oscillations; consider poleward flux effect on mitotic chromosome segregation by measuring velocity of photoactivated tubulin marks or fluorescent speckles using fluorescent speckle microscopy.

---

#### Measuring Kinetochore MT Stability and Dynamics during Mitosis

**Summary of Techniques for Assessing Kinetochore Microtubule Attachments**

**Fluorescence Microscopy Techniques**:
- Measuring stable kinetochore microtubule attachments:
  - Counting end-on bound MTs using electron microscopy
    - Successfully carried out in HeLa and PtK1 cells (McEwen et al., 1998; Rieder, 1982; Wendell et al., 1993)
    - Cannot assess real-time dynamic behavior of kinetochore MTs
    - Provides valuable data to assess stability of kinetochore MT attachments

**Kinetochore Microtubule Dynamics and Attachment Stability**:
- Kinetochore microtubule attachment stability: Persistence of force-producing, end-on-associated kinetochore MTs within attachment sites
- Kinetochore microtubule polymerization and depolymerization dynamics: Extent and ability of kinetochore MT plus-ends to grow/shorten within attachment sites
- Distinct behaviors, may be regulated separately
- Example: Change in attachment stability does not necessarily coincide with a change in kinetochore MT plus-end dynamics (Cimini et al., 2006)

**Relationship Between Kinetochore Microtubule Attachment Stability and Dynamics**:
- Increase in kinetochore MT turnover requires both:
  - Decrease in kinetochore MT attachment stability (release from kinetochores)
  - Subsequent MT plus-end depolymerization to prevent reattachment
- Kinetochore MT attachment strength affects polymerization/depolymerization within the attachment site

**Acknowledgments**:
- Gratitude to Keith DeLuca, Lisa Cameron, Daniela Cimini, Barbara Bernstein, O'Neil Wiggan, and members of the author's lab for helpful comments on the manuscript
- Thanks to Jason Stumpff for suggestions on the chapter and advice on kinetochore oscillation measurements
- Work in the author's laboratory is supported by National Institutes of Health grants K01CA125051 and R01GM088371, and the Pew Scholars Program in the Biomedical Sciences

---

### Chapter 5: Photoactivatable Green Fluorescent Protein Tubulin

**I. Introduction**
- Rationale: Understanding cellular and molecular behaviors through live imaging
- Limitations of uniformly fluorescent microtubules in live cells
- Use of photoactivatable proteins to examine dynamic processes, including spindle formation

**II. Conclusions**
- PA-GFP tagging allows for following the behavior of a subset of tagged molecules in live cells
- Powerful approach to examine dynamic processes, such as mitosis
- PA-GFP allows for local photoactivation and recording the dynamic behavior of the photoactivated molecules in live cells.

**PA-GFP and Expressing it in Mammalian Cells:**
- Cloning and expression of GFP from jellyfish
- Live imaging revolution, allowing deeper questions
- PA-GFP tagging provides a new way to discover the workings of the cell
- Using GFP-tagged tubulin to study microtubule behavior in live cells
- Generating cell lines permanently expressing GFP-tubulin
- Comparing dynamic instability parameters in interphase cells with parental cells injected with fluorescent tubulin
- Mitotic index and doubling time not different from parental cells
- Studying microtubule dynamicity increase during mitosis using PA-GFP tagged tubulin.

**Alternatives to Uniformly Fluorescent Microtubules:**
- Fluorescence speckle microscopy (FSM) and fluorescence recovery after photobleaching (FRAP)
- Limitations: Require individual cell injection, time-consuming procedures.

**Use of Photoactivatable GFP (PA-GFP):**
- PA-GFP is a variant of wild-type EGFP with a threonine to histidine mutation at position 203
- Not fluorescent until exposed to UV light
- User-selected subset of photoactivatable PA-GFP-tagged proteins can be activated, while the remainder is left inactive and nonfluorescent.

**Generating Cells Expressing PA-GFP Tubulin:**
- Replacing EGFP sequence with PA-GFP using either a pCMV or IRES vector
- Improved selection when using IRES vectors due to the tagged gene and selection marker being expressed from a single promoter.

---

#### Cell Line Generation and Characterization for Live Microtubule Imaging

**Advantages of Clonal Cell Lines**
* All cells are identical, unlike transiently transfected cells with varying expression levels
* Easier to gauge expression level before experimentation
* Can characterize multiple clonal cell lines prior to experimentation
* More efficient for live imaging of transient events

**Making a Clonal Cell Line**
1. Transfect parental cells with PA-GFP-tubulin using nucleofection or lipid-based reagents
2. Allow expression of antibiotic resistance gene and undergo positive selection in the presence of antibiotic for 2 weeks
3. Harvest individual colonies using cloning rings or discs, transfer to multiwell plates, and analyze for PA-GFP-tubulin expression by photoactivation
4. For non-colonized cells: count, dilute, and transfer cells to wells in a 96-well plate; when growth is visible, transfer to 24-well plates for further growth
5. Repeat procedures if multiple cell types are detected in the stable line
6. Use Western blotting to identify useful clones and determine expression level of tagged protein relative to endogenous protein
7. Characterize PA-GFP-tubulin cell line: Fig. 1 shows that 99% of total tubulin is tagged with GFP or PA-GFP (A) before and after photoactivation (B), and no detectable abnormalities in mitotic microtubules are observed during the mitotic process (C).

---

#### Photoactivation of PA-GFP-Tubulin in Live Cells

**Photoactivation Experiments with PA-GFP-Tubulin:**
* Performed on Nikon Eclipse TE300 inverted microscope
* Use of X-cite 120 or 100W mercury arc lamp, filtered at 413 nm for activation (405 nm laser also applicable)
* Minimal exposure time determined by exposing cells to various intervals and quantifying fluorescence
* Slit or pinhole in filter wheel used to control photoactivation region
* Larger areas activated using field diaphragm in epi illumination pathway
* Objective position corrected using piezo Z-motor for imaging and photoactivation alignment
* Cells imaged before and after activation with Perkin Elmer spinning disk confocal scan head and Hamamatsu Orca ER camera.

**PA-GFP-Tubulin Analysis:**
* Examined microtubule dynamics in live cells through photoactivation experiments
* Fraction of microtubules exhibit flux behavior in prophase cells, others move more rapidly
* Microtubules transported inward toward forming spindle in prometaphase cells in dynein-dependent manner
* Release of microtubules from centrosome documented using pinhole activation in anaphase cells
* Study of interphase cell microtubule turnover facilitated by PA-GFP-tubulin expression.

---

#### Microtubule Dynamics Analysis Using Photoactivatable Green Fluorescent Protein

**PA-GFP-Tubulin and Microtubule Dynamics in Live Cells**

**Studies on PA-GFP-Tubulin:**
- Powerful method to examine microtubule dynamics in live cells (Bancaud et al., 2010; Patterson & Lippincott-Schwartz, 2002)
- Suitable for various cell types and stages of the cell cycle
- Data analysis is easy using image analysis software
- Large number of proteins have been shown to function normally after tagging with GFP

**Microtubule Behavior:**
- Anterograde microtubule transport drives bending in LLC-PK1 epithelial cells (Bicek et al., 2009)
- Flux-like behavior of prophase microtubule arrays in mammalian cells (Ferenz et al., 2007)
- Peripheral non-centrosome associated microtubules contribute to spindle formation (Tulu et al., 2003)
- Centrosome fragments and microtubules are released and transported asymmetrically away from the division plane in anaphase (Rusan & Wadsworth, 2005)

**Photoactivation Techniques:**
- Used to study mobility and molecular dynamics of proteins in live cells: FRAP, photoactivation, photoconversion, and FLIP (Bancaud et al., 2010)
- Quantifying microtubule motion by placing rectangular boxes around a photoactivated mark of interest and creating a montage to obtain rates of motion
- Determining turnover of microtubules by measuring dissipation of photoactivated fluorescence (Patterson & Lippincott-Schwartz, 2002; Rusan et al., 2001)

**Conclusions:**
- Photoactivation of PA-GFP-tubulin is a valuable method to examine microtubule dynamics in live cells
- Suitable for diverse cell types and stages of the cell cycle
- Experimentally straightforward with standard laboratory equipment.

---

### Chapter 6: Microtubule Dynamics at the Cell Cortex Probed by TIRF Microscopy

**I. Introduction**
- Discusses the application of TIRF microscopy in studying cortical microtubules
- Describes advantages, such as excellent signal-to-noise ratio and high sensitivity, of this technique

**II. Rationale**

**A. TIRF Microscopy**
- Explanation of the technique: selective excitation at a liquid/solid interface within a short distance from the boundary
- Variable penetration depth (typically 250 nm to 450 nm)

**B. Objective**
- Study cortical microtubule attachment and stabilization, interactions with matrix adhesion structures, behavior of specific molecules involved in these processes

**III. Materials and Equipment**

**A. TIRF Setup**

**B. Cell Lines**
- Not specified in the provided text

**C. Fluorescent Markers**
- Markers used for studying microtubules by TIRF microscopy

**D. Cell Culture**
- Details of cell culture methods and conditions not provided

**IV. Methods**

**A. Generation of Stable Cell Lines with Fluorescent Microtubule Markers**

**B. Sample Preparation**

**C. Imaging**
- Explanation of imaging techniques used in TIRF microscopy

**D. Image Analysis**

**V. Discussion**

**A. TIRF Microscopy in Studies of Cortical Microtubules**

**B. TIRF Microscopy as a General Tool for Highly Sensitive Imaging**

**VI. Summary**
- Summary of the chapter's content and significance

---

#### TIRF Microscopy and its Objective-Type Setup in Cell Biology Investigations

**Rationale: TIRF Microscopy**

**TIRF Microscopy**:
- Based on the optical phenomenon of total internal reflection (TIR)
- When light strikes a boundary between two media with different refractive indices, it creates an evanescent wave that can excite fluorophores in the second medium
- The intensity of the evanescent wave decreases exponentially, providing superior z-resolution compared to typical confocal microscopes

**Objective-Type TIRF Setup**:
- Two types: prism-type and objective-type
- Objective-type TIRF microscopes have gained popularity in recent years
- Constructed as an inverted microscope, convenient for cell manipulation
- The numeric aperture of the objective is critical, as it determines the laser beam deflection angle
- High-numeric aperture objectives allow for smaller penetration depths

---

#### TIRF Microscopy Setup and Procedure for Cortical Microtubules Investigation

**TIRF Microscopy Setup**

**Components:**
- Nikon TIRF microscope with perfect focus system, motorized illuminator, and high numeric aperture objective (CFI Apo TIRF 100/C2)
- Additional lens adapter (Nikon C mount adapter 2.5/C2) for increased magnification
- Lasers: Calypso 491 nm and Jive 561 nm (Cobalt)
- Mercury lamp HBO 100W/2 (Osram) for conventional epifluorescent illumination
- TIRF illuminator motorized and manual options to adjust angle of incidence
- Optical fiber delivery system into the microscope
- Filter cubes ET series from Chroma, including excitation filters and dichroic filters
- Beam splitter (DV2) with dichroic 565dcxr (Chroma) for simultaneous imaging of green and red fluorophores
- Back-illuminated QuantEM 512SC EM-CCD camera or interlined CoolSNAP HQ2 CCD camera for image acquisition

**Adjusting Angle of Incidence:**
- Manual: faster but harder to reproduce angles
- Motorized option: easier to achieve reproducibility by choosing values in software
- Laser beam position can be adjusted manually or motorized along X and Y axes.

**Filters:**
- Use filter cubes for excitation, removal of excitation filters not necessary with lasers
- Green fluorophores: Chroma ET-GFP (49002) filter set and Chroma ET-mCherry/GFP double dichroic (59022)
- Red fluorophores: Chroma ET-mCherry (49008) filter set and Chroma ET-mCherry/GFP double dichroic (59022)
- Beam splitter equipped with a dichroic 565dcxr (Chroma) and HQ530/30m emission filter (Chroma) to minimize bleed-through between channels.

---

#### Cell Line Development and Marker Expression

**QuantEM System Features:**
- More sensitive and faster than CoolSNAP
- Smaller chip (512/C2, 512 pixels) with larger pixel size (16 um compared to 6.45 um)
- Equipped with motorized stage and two Smart-shutters for front of mercury lamp and halogen lamp
- Image acquisition controlled using MetaMorph 7.5 software
- Keeps cells at 37C with incubator, water bath, and objective heater
- Cells plated on 25 mm diameter round coverslips assembled in Attofluor cell chamber

**Cell Lines:**
- Choice depends on experimental question and ease of maintenance/transfection
- HeLa cells: easy to transfect, dense microtubule array but less convenient for internal region imaging
- Human lung fibroblasts MRC5-SV, CHO cells, cultured astrocytes, Swiss 3T3 cells, or B16 melanoma cells suitable for studying microtubule cortex and actin cross-talk during cell migration

**Fluorescent Markers:**
- Visualize live cells using microinjection of labeled tubulin or fluorescently tagged tubulin cDNA
- Preferred marker: mCherry--tubulin; GFP or YFP--tubulin can also be used but inhibit cell division and stability
- Alternative strategy: use microtubule plus end tracking (TIP) markers like EB1, EB3, or CLIP-170 for specific visualization of growing microtubule ends

**Cell Culture:**
- Cells maintained in humidified incubator at 37C with 5% CO2
- Typical medium: DMEM (45%), Hams F10 (45%), fetal bovine serum (10%), penicillin (100 U/ml), streptomycin (100 g/ml)

**Generating Stable Cell Lines with Fluorescent Microtubule Markers:**
- Adapt this protocol for other cell lines as needed
- Split cells into 6-well plate to achieve 40% confluence by next day
- Prepare DNA: Linearize fluorescent protein and selective marker expression cassettes without disruption; purify using phenol extraction, ethanol precipitation, or DNA purification kit.

---

#### TIRF Microscopy Linear DNA Transfection and Cortical Microtubule Imaging

**Linearized DNA for Transfection:**
- Lower initial transfection efficiency but better for establishing stably expressing cells
- Use circular plasmid DNA as an alternative

**Transfecting Cells:**
1. Day after plating, split cells and transfer to 10 cm dishes
2. Add culture medium supplemented with G418 (0.5-0.6 mg/ml)
3. Perform fluorescence-activated cell sorting (FACS) using FACS Aria II cell sorter
4. After confluent cells, freeze or continue selection process or imaging

**Sample Preparation:**
1. Plate cells onto coverslips at appropriate density
2. Use appropriate thickness coverslips based on objective design (0.17 m for Nikon CFI Apo TIRF)
3. Transfect stable cell line 1 day after plating using FuGene 6 reagent and manufacturer's protocol
4. Add immersion oil, mount into observation chamber, focus using transmitted or epifluorescent light
5. Switch to TIRF mode with appropriate angle adjustment for desired penetration depth

**Imaging:**
1. Acquire image using conventional epifluorescent mode first
2. Adjust angle of incidence until loss and recovery of signal indicates TIRF mode
3. Determine exact refractive index at spot of observation, calibrate for accurate penetration depth estimation
4. Choose desired angle and collect images or movies

**Image Analysis:**
1. Count number or measure length of visible microtubule segments by TIRF microscopy as sufficient analysis
2. Perform direct tracking of microtubule ends using kymograph analysis to determine dynamic parameters if required.

---

#### Exploring Microtubules in Cortex with TIRF Microscopy Dynamics and Interactions

**TIRF Microscopy in Studies of Cortical Microtubules**

**Overview:**
- TIRF microscopy allows selective illumination of thin cell slices near coverslip
- Used to prove close proximity of structures like microtubules to cortex

**Examples:**
1. **Krylyshkina et al., 2003**: studied microtubule attachment to focal adhesions using TIRF microscopy and RNA interference
2. **Etienne-Manneville et al., 2005; Lansbergen et al., 2006; Mimori-Kiyosue et al., 2010**: used TIRF to investigate protein complexes stabilizing microtubule plus ends
3. **Shaw et al., 2007**: explored gap junction hemichannels targeted by microtubules and adherens junctions
4. **Webb et al., 2009**: described cortical microtubule organization in Drosophila embryos at the syncytial blastoderm stage using TIRF microscopy
5. **Schober et al., 2007**: distinguished cortical microtubule population and studied relationships with filopodia
6. **Vale et al., 2009**: explored localization of myosin filaments, microtubules, and kinesin-6 during cytokinesis in Drosophila S2 cells
7. **Hadjidemetriou et al., 2005; Gell et al., 2009**: obtained quantitative information about microtubule position along Z-axis with uniform labeling and calibration using agarose-embedded fluorescent microtubules

**Advantages:**
- Strong enrichment of TIRF-visible microtubule segments at peripheral cortex
- Improved signal-to-noise ratio due to very thin optical section
- Suitable for single molecule in vitro experiments, widely used in the microtubule field.

---

#### Total Internal Reflection Fluorescence Microscopy for Probing Cortical Events and Dynamics in Cells

**TIRF Microscopy and Cortical Microtubules**

**Advantages of TIRF Microscopy:**
- Improved signal-to-noise ratio compared to conventional epifluorescence microscopy or confocal microscopes
- Reduced photo-bleaching and cell photodamage due to limited illumination depth
- Suitable for studying cortical events and microtubule organization and dynamics in thin, vulnerable cells like hippocampal neurons

**Applications of TIRF Microscopy:**
- Detecting single kinesin molecules moving on individual microtubule tracks to determine preferences for posttranslational tubulin modifications (Cai et al., 2009)
- Improving imaging contrast for measuring microtubule dynamics, sometimes called semi- or near-TIRF (Figs. 1 and 6)
- Observing simultaneous extension of microtubules and ER tubules in the ventral part of HeLa cells (Grigoriev et al., 2008)

**Background Information:**
- TIRF microscopy uses a laser to excite fluorescence from a specific plane close to the glass surface
- Can be used to study cytoskeletal elements localized near the basal cortex and their behavior with different markers (Akhmanova et al., 2009; Akhmanova & Steinmetz, 2008)
- Commercial TIRF microscopes are increasingly popular among cell biologists for generating high-quality data suitable for quantitative analysis.

---

### Chapter 7: Microtubule Dynamics in Dendritic Spines

- **Introduction:** Neurons are complex cells with various processes including axon and dendrites. Signal transmission occurs at synapses between neurons. Understanding neuronal structure and function requires studying microtubules, which play essential roles in neuronal differentiation and mature functioning. Primary culture techniques allow for the development of specialized subdomains such as growth cones, axon initial segments, dendritic spines, and inhibitory and excitatory synapses.
- **Methods:** This chapter provides methods for live imaging of dynamic microtubules in mature hippocampal neurons using total internal reflection fluorescence microscopy (TIRFM) and spinning disk confocal microscopy. It covers protocols for culturing and transfecting mature hippocampal neurons, visualizing microtubules and microtubule plus-end binding proteins.
- **Rationale:** Recent evidence shows that microtubules and their associated proteins play essential roles in neuronal differentiation and function during various stages of development (formation and growth of axons, proper signaling in mature neurons). Dynamic microtubules and the EB3 protein have been shown to be important for structural and functional changes in dendritic spines.
- **Culturing Primary Hippocampal Neurons:**
  - **Buffers, Solutions, and Equipment:** Descriptions of buffers, solutions, and equipment used for neuronal cultures are provided.
  - **Preparing Coverslips for Neuronal Cultures:** Techniques for preparing coverslips for neuronal cultures are detailed.
  - **Hippocampal Dissection:** Procedures for hippocampal dissection and obtaining primary neurons from the hippocampus are discussed.
- **Expression of EB3-GFP in Hippocampal Neurons:** Two methods for expressing EB3-GFP in hippocampal neurons are described:
  - **Using Lipophilic Transfection:** Buffers, solutions, and equipment for lipophilic transfection using Lipofectamine 2000 are provided. Techniques for transfecting neurons with lipofectamine 2000 are discussed.
  - **Using SFV:** Procedures for preparing packaged SFV EB3-GFP replicons in BHK-21 cells and expressing them in hippocampal neurons are outlined.
- **Imaging EB3-GFP by TIRF and Spinning Disk Microscopy:** Techniques for maintaining neuronal health, performing total internal reflection fluorescence microscopy (TIRFM), and spinning disk confocal microscopy are provided.
- **Data Analysis:** Methods for data analysis are discussed.
- **Conclusion:** Summary of the importance of dynamic microtubules in dendritic spines and their potential role in adaptive processes, learning, and memory formation.

---

#### Culturing Mature Hippocampal Neurons for Spine Morphology Analysis

**III. Culturing Primary Hippocampal Neurons**

**Background:**
- Over a century of neuroscience research
- Pioneering work by Banker lab using in vitro dissociated hippocampal neuron cultures
- Studying neuronal cell biology, neuronal development and plasticity

**Original Protocol vs. Modern Approach:**
- Differences: medium density (375500 cells/mm), eliminating astrocyte cocultures, using serum-free Neurobasal medium supplemented with B27
- Longer culture duration (over 23 weeks) for detailed analysis of synaptic plasticity mechanisms and dendritic spine morphology

**Procedure:**
1. Prepare reagents:
   - Glass coverslips or tissue culture plates
   - Poly-D-lysine solution (10 g/ml)
2. Coat coverslips/plates with poly-D-lysine solution and incubate for 30 minutes at room temperature (RT)
3. Rinse with PBS twice
4. Aspirate excess liquid
5. Sterilize in UV light or autoclave
6. Neuron dissociation:
   - Isolate hippocampus from embryonic rats
   - Digest tissue using trypsin (0.25%) and DNAse (1 mg/ml) for 15 minutes at 37C
   - Triturate to dissolve cells into single-cell suspension
7. Plate neurons onto prepared coverslips/plates, spreading evenly in Neurobasal medium supplemented with B27 (2%). Incubate for 1 hour at RT to allow attachment.
8. Add Neurobasal medium supplemented with B27 (2%) and penicillin/streptomycin (50 U/ml) to cover the entire coverslip/plate, leaving a small air gap at the top for gas exchange.
9. Maintain cultures in an incubator at 37C, 5% CO2, and 80% humidity. Replace half of the medium every 3 days.
10. After 23 weeks (or longer), mature hippocampal neurons are ready for further analysis.

---

#### Materials and Procedures for Neuronal Culturing

**Preparation of Materials for Medium-Density Serum-Free Cultures:**

**Buffers, Solutions, and Equipment:**
- Glass coverslips: 19 mm and 24 mm (VWR or Gallard Schlesinger)
- Porcelain racks (Thomas Scientific)
- Oven gloves (VWR)
- 1 l glass beakers (pack of 6, VWR)
- Nitric acid, 65% solution (Sigma)
- 0.1 M borate buffer, pH 8.5 (500 ml)
- Poly-L-lysine (PLL) and laminin coating solution: 450 ml PLL + 300 l laminin in 120 ml of 0.1 M borate buffer
- 12-well plates (Falcon) and 6-well plates (Corning Costar)
- Neurobasal/B27 medium: 97.5 ml Neurobasal, 2 ml B27 supplement, 1 ml penicillin/streptomycin, 250 l glutamine, and 125 l glutamic acid (Invitrogen)
- Tissue culture incubator: 37C, 5% CO2

**Hippocampal Dissection:**
- Timed pregnant Wister rat with about 10-15 embryos at E19 (from Harlan Laboratories)
- 100% carbon dioxide gas
- Dissection tools: medium forceps, straight scissors, two forceps #5 and #4, small curved scissor (FST)
- Dissection M75 zoom stereomicroscope (Wild Heerbrugg)
- 0.3 M HEPES buffer (100 ml), Hanks Balanced Salt Solution (HBSS, 500 ml), and glass beakers (VWR)
- 10 cm dishes, TC dish with 20 mm style (BD Falcon), and polypropylene round-bottom tubes (BD Falcon)
- Trypsin (Invitrogen)
- Inverted phase contrast microscope for cell counting and checking viability.

**Preparing Coverslips:**
- Acid washing: Place coverslips in porcelain racks, incubate in nitric acid for 2 days at room temperature.
- Water washing: Carefully transfer racks into 1 l beakers containing tap water and allow to sit undisturbed for 1 h at room temperature; repeat at least three times for a total of 4 h.
- Dry and bake coverslips overnight at 200C.
- Transfer cooled coverslips to sterile plates (12-well or 6-well) in a laminar flow hood. Coat with PLL and laminin solution overnight, then wash with autoclaved MilliQ water and add Neurobasal/B27 medium; place in incubator until needed.

---

#### Isolation and Expression of Hippocampal Neurons in Culture

**Methods for Neuron Expression and Microtubule Dynamics in Hippocampal Neurons**
* **Expression of EB3-GFP in Hippocampal Neurons Using Lipophilic Transfection**

**I. Background**
- Approach to study neuronal proteins' subcellular localization and functions using recombinant genes in mature hippocampal neurons (Fig. 2A, B)
- Various methods for transfecting hippocampal neurons: calcium phosphate, microinjection, electroporation, Lipofectamine 2000 (Fig. 2C)

**II. Materials and Equipment**
- Tissue culture incubator (37C, 5% CO2)
- 1.5 ml Eppendorf tubes
- Tabletop microcentrifuge (5415D; Eppendorf)
- 50 ml tube (227261; Greiner)
- Lipofectamine 2000 (11668-027; Invitrogen)
- Neurobasal medium (21103-049; Invitrogen)
- 12-well plates (353043; Falcon) and 6-well plates (3506; Corning Costar)
- 250 mM glutamine stock (200 mM) (25030-081; Invitrogen)
- Sterile forceps #5 (11252-30; FST)
- NheI, HindIIIEco47III, NotI, StuIXbaI, HindIII, SalI, EcoRI, BamHI, MluI, AscI, SmaI, KpnI, and BglII restriction enzymes
- pactin vector (6.2 kb) with CMV promoter (Fig. 2B), NheI site at A and HindIII site at C
- pGW1 expression vector (4.9 kb) with various promoters (Fig. 2A) and different restriction enzymes for cloning

**III. Methods**
1. Prepare plasmid DNA mix:
   - Mix pactin vector (6.2 kb) and helper vectors in a 50 ml tube
   - Add Neurobasal medium to reach a total volume of 15 ml
   - Incubate at room temperature for 30 min
2. Prepare liposome mix:
   - In a separate 1.5 ml Eppendorf tube, dilute Lipofectamine 2000 with Opti-MEM I reduced serum medium to the required concentration (typically 2.5 mg/ml)
3. Incubate DNA/liposome:
   - Add liposome mixture to plasmid DNA mix and gently invert the tube to mix
   - Incubate at room temperature for 15-30 min (optimal transfection efficiency depends on various experimental variables)
4. Transfect neurons:
   - Aspirate old media from a well containing hippocampal neurons and replace with 2 ml of fresh Neurobasal medium
   - Add the DNA/liposome complex mixture gently to the well
   - Incubate at 37C for 4-6 hours
5. Remove lipofectamine:
   - Aspirate transfection media and add 2 ml of fresh Neurobasal medium with glutamine (2 mM)
   - Incubate at 37C for 23 weeks before performing DNA transfection or virus infection procedures
6. Optional: After one week in culture, exchange half the medium with fresh Neurobasal/B27 media. Do not replace all media.

---

#### Neuron Transfection using Lipofectamine and SFV Viruses for Microtubule Dynamics Research

**Microtubule Dynamics in Dendritic Spines Using Lipofectamine and SFV**

**Lipofectamine Transfection in Neurons**:
- Thaw plasmid DNA (bactin-EB3-GFP or bactin-cherry-a-tubulin)
- Prepare DNA mix with 1.8g of plasmid DNA per 19 mm coverslip, add 100ul Neurobasal medium
- Prepare L2K mix with 3.3l Lipofectamine 2000 per 19 mm coverslip, add 100ul Neurobasal medium
- Add L2K to DNA mixture and incubate for 30 minutes at room temperature
- Rinse coverslips with fresh warm Neurobasal medium
- Incubate transfected neurons in the incubator at 37C and 5% CO2 for desired time

**SFV Expression of EB3-GFP in Hippocampal Neurons**:
- SFV is an enveloped alphavirus virus with a positive-sense RNA genome
- SFV vector modified to be defective, requiring the use of a helper vector for viral propagation
- SFV gene expression established in dissociated hippocampal neurons and slice cultures
- Advantages include simplicity, ease, high-titer virus production, and efficient infection of cultured neurons (60-80%)
- Disadvantages include cytotoxicity, allowing only short-term transgene expression (424 hours)

**SFV Plasmid System**:
- **pSFV2**: SFV vector plasmid
- **pSFV-Helper2**: Packaging-defective helper vector for viral propagation

**Buffers, Solutions, and Equipment**:
- **G-MEM (BHK-21 culture medium)**: Glasgow MEM with 1% penicillin/streptomycin
- **PBS medium w/o Ca2+/Mg2+**: Phosphate-buffered saline without calcium and magnesium
- **Trypsin/EDTA**: For dissociating cells from tissue culture dishes
- **Fetal bovine serum (FBS)**: 5% FBS in G-MEM
- **10 cm TC dishes**: Treated tissue culture dishes with a diameter of 20 mm
- **Transfection reagents**: Opti-MEM I reduced serum medium, DMRIE-C reagent, aprotinin, and -chymotrypsin

---

#### Live Neuron Imaging with Spinning Disk Microscopy and Controlled Incubation Environment

**Microtubule Dynamics in Dendritic Spines**

**Ultracentrifuge**:
- SW41Ti rotor and ultra clear SW41Ti centrifuge tubes (13.2 ml, 14/C2 89 mm) used: Beckman Coulter
- 40 mM HNE buffer (pH 7.4): 40 mM HEPES, 138.5 mM NaCl, 0.1 mM EGTA, adjusted pH with 4 M NaOH
- Measure osmolarity (should be 300-310 mosm/l), autoclave, and store at 4C

**Preparation of Packaged SFV EB3-GFP Replicons in BHK-21 Cells**:
- Clone gene of interest into the multiple cloning site of pSFV2 vector (pSFV2)
- Digest 1.4 g recombinant pSFV2-EB3-GFP vector with NruI and pSFV Helper2 with SpeI to linearize plasmid DNA
- Clean up linear DNA by phenol/chloroform extraction, precipitate, add RNase-free water, use for in vitro transcription reaction
- Use Roche Sp6 transcription kit to synthesize single-stranded RNA for transfection in BHK-21 cells

**In Vitro Transcription**:
- Contains 15 ml linear DNA, 15 ml 10/C2 transcription buffer, 15 ml 10 mM m7G(50)ppp(50)G, 15 ml 50 mM DTT, 15 ml rNTP mix, 9 ml SP6 RNA polymerase, and 5.6 ml 40 U/l RNasin in a total volume of 150 ml dH2O
- Mix and incubate for 2 h at 37C

**Preparation of BHK-21 Cells**:
- Grow BHK-21 stock cells in 10 cm2 dishes with 5% FBS media complete
- When cells form a confluent monolayer, split using 1 ml prewarmed trypsin/EDTA
- Prepare BHK-21 cells in 175 cm2 flasks one day before transfection

**Transfection of BHK-21 Cells**:
- Discard medium and wash cells twice with 30 ml prewarmed Opti-MEM I media
- Add 17.5 ml Opti-MEM I, 175 ml DMRIE-C, 450 ml SFV-Helper2 RNA, 225 ml SFV2-EB3-GFP RNA
- Immediately add transfection mix to the washed BHK-21 cells and incubate for 4 h at 37C
- Replace transfection media with 36 ml 10% FBS media complete and allow cells to express and release virus particles

**Determining Virus Titer**:
- Harvest 36 ml of medium, filter through 0.22 m sterile Millipore filter
- Activate virus with 0.5 mg/ml a-chymotrypsin at room temperature for 30 min and add 900 l aprotinin (250 g/ml) to stop protease activity
- Concentrate virus by centrifugation in SW41 rotor for 2.5 h at 35,000 rpm
- Dissolve pellet in equal volume of 40 mM HNE buffer (pH 7.4)
- Make 5 aliquots and store at -80C

**Imaging EB3-GFP by TIRF and Spinning Disk Microscopy**:
- A. Maintaining Neuronal Health:
  - Observe and characterize dynamic cellular processes using TIRF microscopy or spinning disk confocal microscopy
  - Challenges include keeping primary neurons alive for long periods, as simple defined solutions lack survival components
  - Use full, conditioned medium as standard medium to promote neuron survival
- Using a small incubator system with temperature, humidity, and CO2 control to maintain cells in controlled environment.

---

#### TIRF Microscopy Setup for Cell Imaging and Analysis

**Environmental Control in Microscopy**
* Heating parts: objective heater (37C), incubator water bath (38C), stage heater (37C), and transparent top heater (40.5C) to prevent condensation
* Automatic digital gas mixer for CO2 and air
* Water supply system to compensate evaporation from the water bath
* Facilitates cell survival for long periods, mimicking regular cell culture incubator conditions

**Total Internal Reflection Fluorescence Microscopy (TIRFM)**
* Light refracts when traveling from one medium with different index of refraction (ni) to another
* Critical angle exists above which light cannot propagate through the second medium and is reflected on interface
* Evanescent wave emerges at interface with penetration depth of order 150 nm
* Used for high-contrast detection of fluorophores in situations with high particle density
* Applications: detecting single fluorophores, studying living cell dynamics

**Considerations when Applying TIRFM to Study Cells**
* Cellular index of refraction is higher than water, requiring higher angle of incidence for total internal reflection and affecting penetration depth
* Semi-TIRF mode used in some studies allows excitation deeper into the sample but does not provide evanescent wave, more appropriately called oblique illumination microscopy

**TIRF Microscope Setup**
* Based on inverted research microscope Nikon Eclipse TE2000E
* Equipped with Perfect Focus System (PFS) and motorized stage
* Controlled by Metamorph 7.1 software
* HBO 103 W/2 Mercury Short Arc Lamp used for episcopic wide-field illumination
* Evanescent wave excitation achieved through commercial TIRF arm
* Lasers: 113 mW 488 nm argon laser line and 11 mW 561 nm diode-pumped solid-state laser coupled into the TIRF arm using an optical fiber
* Precise focusing of laser in objective back focal plane critical for achieving total internal reflection on interface between cover glass and medium.

---

#### Live Cell Dendritic Spine Microtubule Dynamics Analysis Using TIRF and Confocal Microscopy

**Near-simultaneous Dual-color TIRFM**

**Achieving Near-simultaneous Dual-color TIRFM**:
- Achieved by alternating the emission filters in the filter wheel (e.g., ET525/25 or ET630/75) with the corresponding excitation laser
- The QuantEM:512SC EMCCD camera is used at the left port of the microscope
- This camera is well-suited for low-light level microscopy due to its high quantum efficiency (90%+ at 575 nm) and on-chip multiplication to minimize readout noise
- The camera can achieve high acquisition rates by using frame transfer, which shifts the accumulated charge distribution to the unexposed part of the CCD chip for readout
- The minimum exposure time of frames is limited by the readout time (about 35 ms)

**QuantEM:512SC Camera Specifications**:
- Exposed CCD area of 512 x 512 pixels with a 16 m pixel size and 82 m field of view
- Typically uses an additional 2.5x magnification lens to prevent undersampling of the point spread function

**True Simultaneous Dual-color TIRFM**:
- Achieved using a DualView (MAG Biosystems, DV2) with beam splitter and additional emitter in the GFP light path
- This optical device features two relay lenses to project the native image plane of the microscope onto the displaced camera
- The dichroic mirror separates the emissions from the two emitters (e.g., GFP and RFP), and adjustable mirrors redirect the emission paths onto the second relay lens at slightly different angles to create spatially and spectrally separated images on the same CCD chip

**Confocal Microscopy vs. TIRF Microscopy**:
- TIRF microscopy is excellent for studying processes close to the surface of the cover glass, but cannot reach large parts of dendrites and axons out of the evanescent wave
- Confocal microscopes can acquire high-contrast images throughout the sample by using a focused laser that scans the image plane
- The major disadvantage of conventional confocal laser scanning is its slow scanning, which makes it incompatible with fast live cell microscopy
- Spinning disk confocal microscopy overcomes this disadvantage by using two spinning disks containing pinholes and microlenses to focus the laser beams into the pinholes

**Confocal Microscope Equipment**:
- Nikon Eclipse Ti microscope with a CFI Apo TIRF 100/1.49 N.A. oil objective (Nikon)
- Motorized stage and Perfect Focus System (Nikon)
- MetaMorph 7.6.4 software to control the cameras and motorized parts
- Confocal excitation and detection using a 50 mW 491 nm laser (Cobolt Calypso) and spinning disk confocal scanning unit (CSU-X1-A1N-E, Roper Scientific) with a triple-band dichroic mirror (z405/488/568 trans-pc, Chroma) and filter wheel (CSU X1-FW-06P-01, Roper Scientific) containing GFP emission filter (ET525/50m, Chroma)

**Data Analysis**:
- Fluorescent EB3 comets can be readily imaged and followed over time using TIRFM or spinning disk confocal microscopy
- Speeds and directionality of microtubule growth can be analyzed by manual or automatic tracking of comet trajectories
- Potential spine-entering events can be rapidly identified by creating maximum or average projections of entire time-lapse recordings, which approximate the distribution of non-microtubule bound EB3-GFP

---

#### Microtubule Dynamics in Dendritic Spines EB3-GFP Imaging Techniques for Study of Neuronal Cytoskeleton

**Neuron Morphology Imaging Using EB3-GFP**

**Protocols for Studying Dynamic Cytoskeleton in Neuronal Cells:**
1. **EB3-GFP Imaging**:
   - Use of a spinning disk confocal microscope to record time series of 11 z-slices and merge into single image by maximum projection
   - Low-pass filtering before subsequent operations to enhance comet visibility
   - Subtracting average projection to obtain clearer images
2. **Analyzing Comets:**
   - Detectable entry events in maximum projection of time series
   - Kymography over total recording for line analysis
3. **Quantifying Spine Size Change**:
   - Compare spine area before first event to 5 minutes after last event without new entries
   - Use image regions, low-pass filtering, binarization, and morphological filtering to measure area
4. **Control Analysis**:
   - Analyze spines that exist but don't show EB3 entry events

**Background:**
1. Primary neuron cultures are essential for addressing fundamental neurobiology questions through live cell imaging experiments
2. Understanding the dynamic cytoskeleton in neuronal cells has seen a new era with advanced imaging techniques and protein expression/function modulation tools
3. Detailed protocols provided to contribute to better understanding of the dynamic cytoskeleton in neuronal cells

---

### Chapter 8: Protein Micropatterns using Deep UVs

**I. Introduction**
- Long history of microfabrication techniques in cell biology since the 1970s
- Recent development and burst of technical papers on various substrates, molecules, and cell types
- Four main methods: photolithography, microcontact printing, UV-based chemistry, laser/electron beam etching
- Advantages and drawbacks of each method
- Universal solution does not exist
- Two easy methods for biologists: microcontact printing and UV-based chemistry
- This paper presents deep UV (185 nm)-based protocol as an example for controlling cell adhesion geometry and easy implementation in a cell biology lab.

**II. Designing a Photomask**
- A few tips on designing and ordering a proper photomask

**A. Materials:**
- Software: Several programs available to design mask features, depending on the requirements of the mask manufacturer (e.g., GDS II, CIF, or DXF format)
- Photomask: Fused silica or synthetic quartz material for deep UV irradiation, transparent below 200 nm; fewer defects and better transparency than natural quartz but more expensive; specify this when ordering from a photomask producer. Examples of companies that provide fused silica photomasks: Delta Mask (The Netherlands), Toppan Photomasks (present in many countries), Microtronics Photomasks (USA).
- Resolution: Check the resolution provided by the company.

---

#### Designing and Fabricating Protein Micropatterns for Cell Culture Studies

**Micropattern Design and Fabrication**
* Size limitations of features:
  * Resolution of photomask: fraction of microns (expensive) to 1m (regular)
  * Quality of contact between substrate and photomask
* Single-cell patterns:
  * Range between 300 and 2000 m for mammalian cells
  * Distance between patterns: depends on cell type, 100m to 50m (HeLa) prevents most cells from jumping between patterns
* Lines of various widths: study cell migration, impose an axis for cell division without constraining cells on single-cell patterns, affect cell speed and morphology
* Other larger features: keep motile cells within the field of observation during long-term recording
* Designing a photomask: larger than a single coverslip (5" x 5in), leave a large line and mark for easy orientation. Order mask with many small regions to test ideas, then order a second mask with fewer patterns to produce multiple patterned coverslips at once.

**Micropattern Fabrication on Glass Coverslips or Cell Culture Polystyrene Substrates:**
* Use of deep UVs for protein micropatterns: Fig. 1 illustrates the basic geometric parameters for proper cell spreading and absence of cell spreading between adjacent patterns
* Materials: glass coverslip, MilliQ water, PBS, 10mM HEPES buffer (pH7.4), 100mM NaHCO3 buffer (pH8.5), ethanol 96%, PLL-g-PEG stock solution (1mg/ml in 10mM HEPES buffer, pH7.4), fibronectin or other proteins to be patterned, fluorescently labeled protein (optional)
* Note: Make new buffers if issues arise with the protocol; PLL-g-PEG coating on glass coverslips can improve results when using cell culture polystyrene substrates.

---

#### Deep UV Micropattern Fabrication for Protein Substrates

**Materials:**
- Glass coverslip (Acros Organics, 178890250)
- Toluene (Sigma Aldrich, 32249)
- TI Prime (MicroChemicals)

**Equipments:**
- Plasma cleaner (facultative, for micropatterns on PS-coated glass coverslips)
  - UV ozone oven or homemade deep UV oven
- Vacuum mask holder (facultative)
- Spin coater (for polystyrene-coated glass coverslips)

**Surface Preparation:**
1. Wash glass coverslip with ethanol and dry it using filtered airflow or leave it under the hood.
2. Expose to air plasma for 1 minute, oxygen plasma for 10 seconds at 30 W, or deep UV light at a distance of about 10 cm for 5 minutes.
3. Incubate in 0.1 mg/ml PLL-g-PEG solution in 10 mM HEPES buffer (pH 7.4) for 1 hour without rinsing or slowly lift off the coverslip to ensure complete dewetting of the PLL-g-PEG solution; remove any remaining drops with kimwipes and dry it at room temperature.

**Micropattern Fabrication:**
1a. Take a clean glass coverslip, proceed to Step 2, or take a clean PS coverslip and go to Step 2.
1b or 1c. Spin-coat TI prime for 30 seconds at 4000 rpm, cure for 1 minute at 120C, then spin-coat 0.5% PS in toluene for 30 seconds at 4000 rpm.
2. Oxidize with a plasma cleaner (30 W, 10 seconds) or UV light (3 minutes under deep UV light).
3. Incubate in PLL-g-PEG solution for 30 minutes and wash with MilliQ water.
4a. Place the coverslip and chrome mask on a vacuum mask holder or put the coverslip in contact with the chrome mask using a water drop. Expose to UV light under a transparent area (3 minutes) to oxidize the PLL-g-PEG layer.
5. Incubate with protein solution for 20 minutes, rinse in NaHCO3 buffer, and dry. Coverslips can be used within 24 hours for best results.

**Protein Micropatterns: A Direct Printing Protocol Using Deep UVs**
1. Clean the glass coverslip with ethanol and dry it using filtered airflow or leave it under the hood.
2. Place the coverslip on a spin coater, cover with TI PRIME, spin-coat for 30 seconds at 3000 rpm. Cure the coverslip for 1 minute at 120C on a hot plate.
3. Place the coverslip on a spin coater, cover with 0.5% PS in toluene, and spin-coat for 30 seconds at 3000 rpm.
4a (Vacuum mask holder):
  - Clean the photomask with acetone and isopropanol to remove organic residues; if no organic residues, cleaning with isopropanol only will suffice and is better. Dry with filtered airflow.
  - Place the coverslip on the vacuum holder with the pegylated side in contact with the chrome-coated side of the photomask on the mask holder. Open vacuum to ensure intimate contact between the coverslip and mask. Expose the mask-covered substrate to deep UV light for 3 minutes at about 5 cm from the lamp.
  - To remove the coverslip, use a 1 ml plastic micropipette tip and a plastic tweezer or vacuum suction to lift up the coverslip; the coverslip should detach easily if the mask has been cleaned with isopropanol only.
5a (Water drop):
  - Place the photomask under deep UV for 5 minutes to make it more hydrophilic.
  - Place the pegylated side of the coverslip in contact with the chrome-coated side of the photomask using a drop of water (the volume has to be adapted to the substrate size to allow complete coverage by water while keeping close contact).

---

#### Direct Printing of Protein Micropatterns using Deep UV Light

**UV Patterned Substrates: Preparation and Use**

**UV Light Exposure:**
- Recommended volume for mask spacing: about 5 m (for 25 mm coverslips, use a drop of 1.5 l water on the mask; for 12 mm coverslips, use a drop of 0.5 l)
- Prevent air bubbles between mask and substrate
- Expose mask-covered substrate to deep UV light (3 minutes, about 5 cm from lamp)
- Remove coverslip by adding water around it; wait for it to lift off

**Protein Attachment:**
- Incubate patterned substrates with fibronectin and Alexa fluor 488 nm protein (25 g/ml fibronectin, 10 g/ml Alexa fluor) in a basic buffer for 30 minutes or overnight at 4C
- Use any protein but note that some may form films; use no more than 10 g/ml to prevent film formation
- Incubate proteins in basic buffer as they will covalently bind to carboxyl groups on the patterned areas

**Cell Deposition:**
1. Wash adherent cells with PBS and detach using trypsin-EDTA or Versene EDTA
2. Centrifuge cells, remove supernatant, resuspend in culture medium at 150,000 cells/ml
3. Add cell solution to micropatterned substrate (about 10,000 cells/cm) and incubate
4. After sufficient attachment time (varies by cell type), remove nonattached cells and add fresh medium
5. Allow attached cells to spread fully before fixing or video recording

**Discussion:**
- Protocol is simple and robust for directly patterning glass substrates with fibronectin
- Success rate is high, with a limited number of steps and chemicals involved
- Can be adapted for specific applications: cells, patterned proteins, timescale.

---

#### Micropatterning Cellular Adhesion with Deep UV Irradiation on Various Substrates

**Substrate for Repulsive Surfaces**
- Can be made cell repulsive or naturally repulsive, such as: glass, plastic, silicone rubber, hydrogels
- Success depends on quality of passivation of the substrate

**Parameters to Modulate for Different Substrates and Cells:**
1. **Antiadhesive surface coating**:
   - PLL-g-PEG is easiest but doesn't provide best passivation
   - Proteins binding to the substrate may be necessary in some cases
2. **Protein binding to the substrate**:
   - Adsorption of proteins on irradiated substrate is often enough
   - In some cases, covalent binding of proteins is required for optimal results

**Options for Protein Binding:**
- Simple techniques: direct patterning on bare glass without backfilling with repellent molecule
- Complex methods: silanization, electrostatic interactions, hydrophobic/hydrophilic interactions
- Various options open, but ease, reproducibility, and quality of patterning must be considered
- Some cases may require production by specialists in surface chemistry and microfabrication

**Alternative Methods for Passivation:**
- Short-term confinement on glass: use PLL-g-PEG as in this article.
- Longer term on glass: covalent binding of PLL-g-PEG or other methods (PS coating, silanization)

**Protein Adsorption and Binding:**
- Covalent binding of proteins using EDC/NHS method
- Sequential protein binding with deep UVs

**Deep UVs for Micropatterning on Silicon Elastomer:**
1. Wash and dry PDMS substrate
2. Activate the PDMS with deep UVs for 5 minutes
3. Prepare fresh EDC/sulfo-NHS solution
4. Follow specific protocol for protein binding or backfilling with passivation molecule (PLL-g-PEG)

---

#### Micropatterned Cell Adhesion Protocol and Literature Review

**PDMS Micropatterning Protocol**

**Preparation of PDMS**:
- Dissolve in buffer: 0.05 M MES, 0.5 M NaCl, pH 6.0
- Can't be stored, must be made freshly each time
- Wash with H2O and incubate for 15 min at RT with EDC/Sulfo-NHS solution
- Wash with PBS and H2O
- Incubate for 3 hours at RT (or O/N) with a solution of 0.5 mg/ml PLL-g-PEG in HEPES 10 mM, pH 8.6
- Rinse with PBS and then H2O, can be stored at 4C up to 1 week

**Coating PDMS**:
- Dry the PDMS well, no water left between PDMS and photomask
- Place in close contact with photomask
- Illuminate with deep UV through the photomask for 5 minutes
- Add H2O and remove gently from mask
- Incubate the PDMS with a solution of 25 g/ml fibronectin in NaHCO3 100 mM, pH 8.6 for 1 hour
- Rinse with H2O and PBS

**Micropatterning Techniques**:
- Optimizing micropatterning based on cell adhesion and long-term confinement is difficult
- Compromises needed to minimize specialized devices and techniques while maintaining good micropattern quality

**Materials Used**:
- PDMS: can be made from scratch or bought in ready-to-use form (Gel Pak)
- EDC, Sulfo-NHS, MES: purchased from Sigma

---

### Chapter 9: New and Old Reagents for Fluorescent Protein Tagging of Microtubules in Fission Yeast: Experimental and Critical Evaluation

**I. Introduction**
- Discussing reagents to image GFP-labeled microtubules in fission yeast, with focus on time-lapse applications
- Introducing new tagging cassettes for RFPs and new RFP-tubulin strains

**II. Which GFP-Tubulin Should I Use?**
- Description of GFP's properties: 26.9 kD protein, b-barrel with a coaxial a-helix, chromophore contained within the a-helix
- Improvements through mutagenesis: brighter fluorescence (S65T), shifted excitation maximum, minimal impact on protein function

**III. Searching for the GFP of RFPs**
- Overview of challenges in developing RFPs for microtubule labeling in fission yeast

**IV. Generation and Evaluation of New RFPs in Fission Yeast**
- Description of recent progress in the development of robust monomeric and tandem dimer RFPs (mCherry, TagRFP-T, mOrange2, mKate, tdTomato)
- Data assessing their suitability as tags in S. pombe

**V. The Hunt for Red Tubulin**
- Discussion of challenges in labeling microtubules with RFPs due to the presence of two a-tubulin isoforms

---

#### Comparison of GFP-Tubulin Expression Methods in Fission Yeast

**Criteria for a Good GFP-Tubulin**
- Does not strongly alter total amount of tubulin in the cell
- Does not significantly perturb microtubule nucleation, dynamics, or function
- Is sufficiently high to allow useful imaging
- Is uniform in cells wherever possible

**Plasmid Expression vs. Integrated Forms**
- Initial experiments used plasmid expression under the repressed nmt1 promoter
- However, episomal expression is far from ideal due to cell-to-cell variation in plasmid copy number and effects on microtubule dynamics
- Two approaches for generating integrated GFP-Atb2 strains:
  - PCR-based gene targeting to introduce GFP-Atb2 at the endogenous atb2 locus, creating a strain with all Atb2 in the cell being GFP-Atb2
    - Early imaging experiments used repressed nmt1 or induced nmt41 promoters
    - Current imaging systems sufficient for imaging microtubules using weakest nmt81 promoter
  - Plasmid constructs containing GFP-Atb2 driven by apromoter at the nontargeted leu1 or ars1 loci, preserving expression of endogenous untagged Atb2
    - Examples: integration at the ars1 locus using the nmt81 or weakened nmt1 promoter, and integration at the leu1 locus using the SV40 early promoter

**Reasons to Prefer One GFP-Atb2 Strain Over Another**
- Coding sequences of different versions of GFP-Atb2 are essentially identical, so main features distinguishing strains are expression of GFP-Atb2 relative to Nda2 and presence of untagged Atb2
- Quantitative fluorescence-based immunoblotting was used to measure levels of GFP- or mCherry-Atb2, untagged Atb2, and Nda2 as a percentage of total a-tubulin in several commonly used strains
  - At 25C in YE5S medium, SV40:GFP-Atb2 at the leu1 locus was 1.3% of total cellular a-tubulin
    - Levels increased fourfold when grown at 36C, demonstrating temperature-dependent activity of the SV40 promoter
  - nmt81:GFP-Atb2 and nmt41:GFP-Atb2 at the atb2 locus were approximately 20% and 64% of total a-tubulin, respectively
- Amount of GFP/RFP-Atb2 relative to Atb2 and Nda2 in EMM2 medium is shown in the table below.

---

#### Fluorescent Microtubules Comparison in Fission Yeast Strains

**Expressing Different GFP-Atb2 and RFP-Atb2 Strains in Fission Yeast**

**Expression Levels of Different Strains**:
- Wild-type cells (KS515)
- Strains expressing:
  - GFP-Atb2 at the leu1 locus (SV40: GFP-Atb2, KS4956) or the atb2 locus (nmt81: GFP-Atb2, KS1235; nmt41: GFP-Atb2, KS1231; nmt1: GFP-Atb2, KS261; nmt81: mCherry-Atb2, KS2789; nmt41: mCherry-Atb2, KS2790)
  - RFP-Atb2 at the atb2 locus (nmt81: GFP-Atb2, KS2789; nmt41: mCherry-Atb2, KS2790)
- Grown in YE5S (rich medium) or EMM2 (minimal medium) at 25C for 48 hours or 44 hours followed by a temperature shift to 36C for 4 hours
- Total protein extracts prepared by boiling cell pellets and vortexing with glass beads
- Samples separated by SDS-PAGE, and -tubulin (Nda2 and Atb2) levels detected by a mouse -TAT1 immunoblot
- Signals quantitated using the Odyssey Infrared Imaging System and software

**Proportion of GFP- or RFP-Atb2, Untagged Atb2, and Nda2 in Each Strain**:
- Proportion of GFP-Atb2, untagged Atb2, and Nda2 present in each strain as a percentage of total -tubulin
- Asterisks indicate samples with approximately twofold increased overall levels of -tubulin compared to wild type
- The presence or absence of untagged Atb2 affects usability

**Differences in Expression and Untagged Atb2 Retention**:
- Differences between nmt41: GFP-Atb2 and nmt81: GFP-Atb2 suggest that too much GFP-Atb2 adversely affects microtubule behavior even when not lethal to cells
- Astral microtubules in mitosis are not very common with nmt41: GFP-Atb2 but are readily observed with nmt81: GFP-Atb2
- Similar differences in interphase microtubules have been observed with mutants mto1D and mto2D, both of which have defects in cytoplasmic microtubule nucleation
- The overexpression of GFP-Atb2 from the repressed nmt1 promotor or induced nmt41 promoter resulted in approximately twofold increased overall -tubulin levels and a decrease in Nda2 as cells attempted to maintain -tubulin homeostasis
- The same down-regulation of Nda2 was also observed when mCherry-Atb2 was expressed at the atb2 locus

**Effects on Usability**:
- Too much GFP-Atb2 adversely affects microtubule behavior, even when not lethal to cells
- The retention of untagged Atb2 is important, as it may have unique biological functions not shared by Nda2
- The ratio of GFP-Atb2 to total untagged -tubulin or a combination of the two may also contribute to these effects.

---

#### Evaluation of Red Fluorescent Proteins for Fission Yeast Microtubule Imaging

**GFP and RFPs for Microtubule Imaging in Fission Yeast**

**Background:**
- Previous difficulties identifying suitable red fluorescent proteins (RFPs) for microtubules similar to GFP.
- Several new RFPs developed: mCherry, tdTomato, TagRFP, mKate, and mOrange2.

**Evaluation of New RFPs:**
1. Generated tagging cassettes for each RFP using standard pFA6a plasmids.
2. Attempted fusions to three cytoskeletal proteins: Tea1, Alp4, and TagRFP-T.
3. Tested expression level, function, brightness, and photostability of each RFP.

**Plasmid Templates for PCR Amplification and Integration Cassettes:** (Table I)
- Plasmids allow integration at gene-specific locus.

**Evaluation Results:**
1. tdTomato and mCherry: Strong expression, brightness, and photostability with NMT1 promoter.
2. TagRFP-T: Similar results as tdTomato and mCherry but stronger than both using the NMT1 promoter.
3. mOrange2: Stronger than mCherry but weaker than TagRFP-T or tdTomato with the NMT1 promoter.
4. mKate: Extremely photostable and longer emission wavelength than other RFPs, but weaker than tdTomato, mCherry, and TagRFP-T using the NMT1 promoter.
5. Comparison with SV40 :GFP-Atb2 expression at leu1 locus is important for validation in some cases.
6. nmt81 :GFP-Atb2 expression at ars1 locus leaves endogenous untagged Atb2 undisturbed and produces higher levels of GFP-Atb2 than SV40 :GFP-Atb2 but may not be suitable for all applications due to genetic markers.

---

#### Protein Stability and Function Analysis of RFP Fusions in Fission Yeast

**Plasmid Availability and Protein Functionality with RFPs in Fission Yeast**

**NatMX6 Cassette for Resistance**:
- Plasmids available with NatMX6 cassette to confer resistance to nourseothricin

**Proteins Studied**:
- Tea1 (200 kD), Mto1 (170 kD), and Alp4 (90 kD) proteins
- RFPs used: GFP, mCh, TRT, mO2, tdTomato, TagRFP-T, mOrange2, and mKate

**Effects of Different RFPs on Protein Functionality**:
- **mCherry**, **tdTomato**, **TagRFP-T**, and **mOrange2** fusions to Tea1, Mto1, and Alp4 did not appear to have gross adverse effects on protein function
- However, **mKate** fusions to Alp4 had poor growth and could perturb function
- Proteins produced smaller cleavage products that were only marginally larger than the corresponding untagged proteins
- Stability of full-length tagged proteins was lower than untagged ones (30-189% of the wild type)
- **mOrange2** and **TagRFP-T** had the least negative effect on protein stability, with levels varying between 47 and 176% of the wild type
- Both **tdTomato** and **mCherry** had variable effects on protein stability (30-152% of the wild type)
- Function of fusions was assessed and varied depending on the protein to which they were tagged

---

#### Photostability Comparison of Red Fluorescent Proteins in Fission Yeast Cells

**Effect of RFP Tagging on Protein Stability and Function in Fission Yeast**

**Tea1, Mto1, and Alp4 Proteins**:
- Tea1-tdTomato and Tea1-mCherry levels decreased to approximately 10% of untagged proteins when tagged with tdTomato or mCherry
- Cells expressing Mto1-mCherry and Mto1-tdTomato displayed phenotypes characteristic of mto1D mutants, such as curved growth
- Alp4-RFP fusions were relatively stable with either tag

**Photostability of RFP-Tagged Proteins**:
- Tea1-tdTomato, Tea1-mCherry, Tea1-TagRFP-T, and Tea1-mKate displayed similar fluorescent properties independent of protein fused to them
- mKate was the most photostable RFP examined, exhibiting negligible photo-bleaching even under high intensity illumination
- mCherry also displayed good photo stability, with strong fluorescence even after prolonged illumination
- tdTomato appeared slightly less stable than mCherry, particularly under high intensity illumination
- TagRFP-T fusions exhibited lower photostability than either mCherry or tdTomato
- tdTomato was the brightest of all fluorophores, followed by mCherry, mKate, and TagRFP-T; mOrange2 was particularly dim when expressed in fission yeast

**Importance of Testing RFP Properties**:
- No single RFP has all positive attributes, as some can affect protein function and have poorer fluorescence properties
- It may be necessary to evaluate several different RFP-fusions to determine the optimal tag for a protein of interest

---

#### Fluorescent Protein Fusion for Tubulin Study in Fission Yeast

**Experience with Different Red Fluorescent Proteins (RFPs) for Tagging Cytoskeletal Proteins in Fission Yeast**

**General Rules Emerging from Experiments:**
- For many proteins, mCherry and tdTomato are the best options.
- tdTomato is very bright, has low levels of photobleaching, and minimal effects on functionality. Its brighter signal will be useful for proteins with low expression levels.
- mCherry is a satisfactory alternative as it is monomeric, reasonably bright, and displays robust photostability. However, fusion with both mCherry and tdTomato can reduce the stability of some proteins. An alternative tag like TagRFP-T could be considered or a heterologous promoter used to boost expression back to wild-type levels.
- mOrange2 is too faint to be practical for in vivo imaging in fission yeast.
- mKate is extremely photostable, making it a valuable tool in experiments requiring high-intensity or prolonged sample illumination. However, it is the most functionally perturbing of all RFPs tested and should be used with care. A new mKate2 protein has been developed, which may be another useful RFP to add to the armory.

**Hunt for Red Tubulin:**
- Plasmids expressing nmt1: mRFP1-Atb2, nmt1: mCherry-Atb2, or nmt81: mCherry-Atb2 have been described and used primarily to image mitotic or meiotic spindles.
- However, episomal expression of RFP-tubulin is subject to copy number variation. Therefore, cells expressing integrated versions of new RFPs fused to Atb2 were examined.
- RFP-Atb2 fusions were expressed under the control of either the medium-strength nmt41 promoter or weak nmt81 promoter and integrated at either the atb2 locus (replacing the endogenous protein) or leu1 locus (leaving the endogenous atb2 gene intact).
- Plasmids were created for RFP-Atb2 integration at the leu1 locus under the control of the nmt41 or nmt81 promoters. The SphI/XhoI fragment from pHFmK1c/41c/81c and pHFtdT1c/41c/81c was cloned into pDUAL, generating pDUAL-pHFmK1c/41c/81c and pDUAL-pHFtdT1c/41c/81c.

**Useful pDUAL Gateway-Compatible GFP and RFP Plasmids:**
| Plasmida | Lab reference | Tag | Tag position  | Promoter  | Promoter strength |
|: |: |: |: |: |: |
| pDUAL-GFH1cb |  | GFP-FLAG-6xHis | C | nmt1 | Strong |
| pDUAL-GFH41cb |  | GFP-FLAG-6xHis | C | nmt41 | Medium |
| pDUAL-GFH81cb |  | GFP-FLAG-6xHis | C | nmt81 | Weak |
| pDUAL-HFG1cb |  | 6xHis-FLAG-GFP | N | nmt1 | Strong |
| pDUAL-HFG41cb |  | 6xHis-FLAG-GFP | N | nmt41 | Medium |
| pDUAL-HFG81cb |  | 6xHis-FLAG-GFP | N | nmt81 | Weak |
| pDUAL-GFH31cc |  | GFP-FLAG-6xHis | C | cam1 | Weak |
| pDUAL-GFH51cc |  | GFP-FLAG-6xHis | C | tif51 | Strong |
| pDUAL-HFG31cc |  | 6xHis-FLAG-GFP | N | cam1 | Weak |
| pDUAL-HFG51cc |  | 6xHis-FLAG-GFP | N | tif51 | Strong |
| pDUAL-GFH31cc |  | GFP-FLAG-6xHis | C | cam1 | Weak |
| pDUAL-GFH51cc |  | GFP-FLAG-6xHis | C | tif51 | Strong |
| pDUAL-HFtdT 1cd |  | 6xHis-FLAG-tdTomato | N | nmt1 | Strong |
| pDUAL-HFtdT 41cd |  | 6xHis-FLAG-tdTomato | N | nmt41 | Medium |
| pDUAL-HFtdT 81cd |  | 6xHis-FLAG-tdTomato | N | nmt81 | Weak |
| pDUAL-HFmK 1cd |  | 6xHis-FLAG-mKate | N | nmt1 | Strong |
| pDUAL-HFmK 41cd |  | 6xHis-FLAG-mKate | N | nmt41 | Medium |
| pDUAL-HFmK 81cd |  | 6xHis-FLAG-mKate | N | nmt81 | Weak |

---

#### Fission Yeast Microtubule Expression Analysis in Various Constructs

**Study Findings and Comparison of Microtubules in Fission Yeast:**
- Matsuyama et al. (2004, 2008) studied the effects of expressing different fluorescent proteins fused to Atb2 on microtubule structure in Fission yeast.
- **nmt81: mCherry-Atb2** at the atb2 locus resulted in abnormally shaped cells with short microtubules compared to those expressing nmt81: GFP-Atb2. However, nmt81: mCherry-Atb2 expression at leu1 locus yielded wild-type shape and normal microtubule distribution (Fig. 6A, B & E).
- **nmt41: tdTomato-Atb2** and **nmt41: mKate-Atb2** at the leu1 locus displayed apparently wild-type microtubules (Fig. 6EG). However, tdTomato-Atb2 expression was uneven, producing speckled microtubules which may be useful for speckle microscopy applications.
- **nmt81:tdTomato-Atb2**, **nmt41:tdTomato-Atb2**, and **nmt41:mKate-Atb2** at the leu1 locus allowed unperturbed expression of endogenous untagged Atb2 at the atb2 locus, resulting in wild-type microtubules (Fig. 6EG).
- The level of tagged tubulin in the strain expressing nmt41: mKate-Atb2 was lower than that with mKate-Atb2 expressed under SV40 promoter at nmt81 locus.
- **nmt81:GFP-Atb2**, **nmt81:mCherry-Atb2**, and **nmt41:mCherry-Atb2** displayed similar expression levels when using different promoters and integration sites (Fig. 6I & J).

---

#### Imaging Fission Yeast Microtubules and Associated Proteins

**GFP-Atb2 vs RFP-Atb2 Constructs**

**Range of Expression**:
- GFP-Atb2 can be used over a greater range of expression levels than RFP-Atb2
- FLAG tags on the leu1-integrated tubulins could affect protein stability

**Evidence for GFP-Atb2 as Construct of Choice**:
- Produces wild-type microtubule arrays suitable for imaging over a broader range than RFP-Atb2
- Nmt81:mCherry-Atb2 integrated at the atb2 locus produces fluorescently robust and wild-type microtubules

**Simultaneous Imaging with MAPs**:
- If microtubules are focus, use GFP-Atb2 with MAP-RFP
- If MAP is more important, use MAP-GFP with nmt81:mCherry-Atb2

**Long-Term Imaging and Other Considerations**:
- mKate-Atb2 expressed under the nmt41 promoter at leu1 can be used for highly photostable microtubules
- Development of SV40:mCherry-Atb2 constructs and pDUAL plasmids would be valuable tools

**Imaging Conditions**:
- **Emission filters**: Matched to fluorophores to collect maximum signal
- **Linker sequences**: Added between the C-terminus of the tagged protein and the downstream GFP or RFP tag can affect behavior of the fusion protein
- **Media choice**: Rich media has autofluorescence that can mask specific fluorescence

---

#### Preparation of Microtubule Imaging in Fission Yeast

**Fluorescent Microtubules in Fission Yeast: Imaging Guidelines**

**Avoiding Unwanted Coloration**:
- Use growth medium without nitrogen source and supplements until after autoclaving
- This can help minimize yellow coloration from caramelization of glucose during autoclaving

**Growing Cells**:
- Grow cells near the final imaging temperature, such as 25C instead of 30-32C
- This reduces the need for complex temperature-controlled equipment and minimizes temperature variations during transfer

**Examining Physiologically Active Cells**:
- Obtain data from early to mid-log phase cells
- Use agarose pads or tissue culture dishes with nutrient sources to allow cells to divide several times

**Agarose Pads**:
- Allow cells to be mounted in high-density monolayers
- Useful for examining the effects of drug treatment, as drugs can be added directly before slide preparation

**Preparing Agarose Pads**:
- Dissolve 2% agarose in growth medium and keep at 70C
- Place 3M Scotch adhesive tape on either end of a microscope slide to act as spacers
- Gently slide the top slide away from the bottom, then pipette 1 ml of cell suspension onto one side of the pad
- Seal with a 1:1:1 mixture of vaseline, lanolin, and paraffin (VALAP)
- Use minimal VALAP sealing for RFP-tagged proteins

**Avoiding GFP Photoconversion**:
- A compromise on sample oxygenation is needed to minimize photoconversion
- Imaging cells toward the edge of the sample, well-oxygenated but also oxygen depleted, can be effective

**Culture Dishes**:
- Allow easier manipulation of growth medium for experiments requiring drug treatment followed by washout
- Do not achieve high cell densities, which may underrepresent the event or cell cycle stage of interest

**Preparing Culture Dishes**:
- Prepare 0.2 mg/ml solution of soybean lectin in water
- Assemble imaging chamber with a clean, untreated 25 mm round glass coverslip
- Spin down the cells and resuspend in fresh media, then mix with the lectin solution
- Incubate the cell/lectin mixture on the coverslip to allow adhesion, then wash off non-adhered cells
- Immediately cover cells with fresh media and image

**Acknowledgments**:
- D. Kelly for help with image processing
- C. Bicho and E. Lynch for help with strain construction
- F. Chang and Y. Watanabe for strains
- K.E.S. is a Wellcome Trust Senior Research Fellow in Basic Biomedical Sciences
- This work was supported by a grant from the Wellcome Trust

---

### Chapter 10: Optical Trapping and Laser Ablation in Fission Yeast

**I. Introduction:**
- Manipulation as a powerful investigation technique since early biology history
- Invention of laser in 1960 led to optical manipulation
- Optical manipulation uses light to interact with matter
- Two main techniques: optical trapping and laser ablation
- Focus on applications in fission yeast for studying organelle positioning and microtubule cytoskeleton force balance

**II. Optical Manipulation:**
*A. In Vivo Optical Manipulation*
- Light carries momentum and energy, used to modify sample structure
- Advantages: easily integrable with various microscopy setups, higher spatial and temporal resolution, contact-free interaction
- Difficulties in vivo: risks of optical damage, cytoplasm is not optically homogeneous medium, challenging to inject particles with known optical properties for reliable force measurement

**II. Optical Manipulation (Cont'd):**
*A. In Vivo Optical Manipulation* (cont.)
- Forces difficult to measure but still large enough to study biologically relevant phenomena
- Examples: single cell or particle trapping with suitable mean optical properties

*B. Integration with Microscopy Setups*
- Optical manipulation easily integrates with confocal or multiphoton microscopes

**III. Optical Tweezers:**
- Use momentum exchange between laser photons and sample to apply forces
- Consists of an infrared, continuous wave (CW) laser focused using high numerical aperture objective
- Traps micrometer-sized homogeneous microspheres with forces ranging from pN to tens of pNs depending on optical properties
- Difficulties working in vivo: risk of inducing optical damage, cytoplasm is not optically homogeneous medium, challenging to inject particles for reliable force measurement but still possible with suitable mean optical properties and studying biologically relevant phenomena.

**IV. Laser Ablation:**
- Exploits confined deposition of energy induced by highly focused laser beam to locally modify sample
- Advantages: high spatial resolution, precise control over beam shape and focusing
- Difficulties: requires careful control of beam shape and use of highly corrected optics to focus on smallest possible area.

**V. Methods:**
- Cell culture and sample preparation not covered in provided text.

---

#### Optical Tweezing and Manipulation of Fission Yeast Nuclei

**Optical Tweezers and Laser Ablation in Microscopy Setups**
* Combining optical tweezers and laser ablation with microscopy requires basic knowledge of optics
* Key aspects for optical tweezers: beam quality, quality of optical components, power control method
* Desirable for laser ablation: accurate control of exposure time
* Fluorescently labeled samples enhance potential applications, especially in vivo
* Additional optical components necessary for visualizing fluorescence signal

**Optical Tweezing in Fission Yeast**
* Optical forces can be exploited to displace the nucleus in fission yeast
* Cannot directly apply optical forces to the nucleus due to similar refractive indexes of cytoplasm and nucleoplasm
* Need to trap a suitable particle and use it as a handle to apply forces on the nucleus
* Microinjecting particles is cumbersome due to cell wall in fungi
* Trapped lipid granules present in the cytoplasm can be moved inside the cell and used to displace the nucleus

**Experiment Setup**
* Demonstrated optical tweezers' ability to perturb intracellular arrangement using a Schizosaccharomyces pombe strain with GFP-labeled nuclear envelope and spindle pole body
* Cells fixed to glass bottom Petri dish treated with microtubule poison drug (MBC) to depolymerize microtubules
* Optical trap focused inside the cell to trap lipid granules in cytoplasm
* Trapped granule moved against nucleus while acquiring two-photon images
* Nuclear envelope deformed and relaxed after switching off optical trap
* Repeatedly applied forces using trapped lipid granule over several minutes displaced whole nucleus
* Nucleus relaxed back to original position after washing out MBC

**Discussion**
* Optical tweezers used to deform and displace the nucleus in a living cell
* Displacing nucleus in fission yeast achieved by other methods, but single-cell level advantages:
1. Allows following displacement and relaxation processes
2. Permits comparison of same cell before and after manipulation
3. Enables changing position of nucleus without affecting other organelles or molecular gradients
* Care taken to avoid inducing damage during lipid granule trapping using CW, near-infrared laser at 970 nm; results suggest minimal damage to sample.

---

#### Laser Ablation of Microtubules in Fission Yeast

**Optical Trapping and Laser Ablation of Microtubules**

**Background:**
- Laser ablation can be used to perturb internal force balance in a cell
- Does not require particles inside the cell but can target cytoskeletal elements or organelles
- Provides information about cellular processes complementary to genetic approaches
- Can be implemented in any optical microscopy setup for higher spatial and temporal resolution than optical tweezers

**Laser Ablation Experiments:**
- Minimize unspecific damage by controlling laser power at sample and exposure time during ablation
- Optimal parameters ensure high ablation efficiency with minimal unspecific damage

**Experiment:**
1. **Ablation of Interphase Microtubules**:
   - Ablation cuts bundle, creating new plus and minus ends
   - Newly created minus end is unstable, resulting in depolymerization mainly by shrinking from its end
   - Nonablated microtubules remain unaffected
2. **Ablation of Mitotic Spindle**:
   - Ablation near one pole induces asymmetric division and nuclear inheritance
   - Abnormal mitosis occurs as the ablated spindle continues to elongate, displacing the nucleus asymmetrically during cell division

---

#### Laser Ablation of Microtubules in Fission Yeast Mechanisms of Nuclear Movement During Meiosis

**Laser Ablation and Optical Trapping in Fission Yeast**

**Background:**
- Laser ablation used to study cell mechanics during different phases of the cell cycle
- Ablations perturb mechanical equilibrium or geometrical arrangement of cytoskeleton
- Information inferred about forces acting on cells by observing reactions to modifications

**Experiments:**
1. **Mitosis:** Perturbed force balance, exploiting internal forces for asymmetric nuclear segregation
2. **Meiosis:** Studied dynein's role in nuclear movement and self-organization of force generators

**Methodology:**
- Laser ablation: pulsed laser tuned to 895 nm, ~5 mW imaging power, ~100 mW ablation power
- Optical trapping: near-infrared CW laser, custom-built two-photon setup with LabView software and Igor Pro or Matlab analysis

**Advantages:**
- Insight into intracellular forces leading to asymmetric segregation
- No external forces used, spatial arrangement of other organelles not perturbed

**Controls:**
- Calibrate ablation efficiency to avoid artifacts

---

### Chapter 11: Microfluidic Temperature Control Device for Studying Microtubule Dynamics in Fission Yeast

**I. Introduction**:
- Recent developments in soft lithography and microfluidics enable controlling the cellular microenvironment
- Fast temperature control is crucial for studying microtubule dynamics, which respond to changes in temperature
- Genetic model organism like fission yeast has been used to study the microtubule cytoskeleton

**II. Device and Setup Presentation**:
- Bilayer PDMS device bonded onto a 150 m thick glass coverslip
    - Bottom channel for cells in contact with the glass surface
    - Top channel for temperature control, separated by a thin PDMS membrane to avoid direct fluid contact
- Temperature control setup consists of two Peltier modules, a syringe pump, and a microscope
    - Peltier modules plugged upstream (inlet) and downstream (outlet) of the device

**III. Mold and Device Fabrication**:
1. Microfluidic mold fabrication:
   - Preliminary step to create PDMS channels
2. Steps for PDMS layer fabrication:
    A. PDMS preparation
    B. Fabrication of temperature control channels
    C. Fabrication of cell channel layer
    D. Plasma treatment and bonding of both PDMS layers (temperature control and cell microchannels)
    E. Plasma bonding of the bilayer PDMS assembly onto a glass coverslip
3. Plasma bonding of the bilayer PDMS assembly onto a glass coverslip

**IV. Setup Installation**:
1. Steps for setting up the temperature control system:
    A. Connection of Peltier module to microfluidic device
         * Microfluidic channel is cooled when connected to downstream Peltier module
         * Microfluidic channel is heated when connected to upstream Peltier module
    B. Connection of peristaltic pump to Peltier module
        * Water flow reversal changes which Peltier module heats or cools the microchannel
2. Temperature control setup diagram and top view of bilayer PDMS device

**V. Biological Experiments**:
1. Steps for performing experiments:
    A. Device preparation and cell injection
    B. Installing the PDMS device on the temperature control setup
    C. Performing temperature changes
2. Applications:
    - Depolymerizing microtubules at low temperatures
    - Deactivating proteins in temperature-sensitive mutants

**VI. Conclusion**:
- Detailed protocol for fabricating and using a microfluidic temperature control device
- Can be adapted for other types of cells or organisms, and combined with other microfluidic functionalities

**VII. Materials**:
1. Mold Fabrication:
   - Soft lithography techniques (Belanger et al., 2001; Charati and Stern, 1998; Duffy et al., 1998)
2. Device Fabrication:
    - PDMS materials and fabrication techniques
3. Temperature Control Setup:
   - Peltier modules, syringe pump, and microscope
4. Cell Injection:
   - Micropipettes or other cell injection methods

---

#### Microfluidic Device Fabrication Using PDMS

**Microfluidic Device Fabrication using PDMS**

**Advantages of PDMS for Microfluidic Devices:**
- Transparent, biocompatible, and permeable to gas
- Cheap, easy to mold, low Young's modulus
- Can be easily covalently bonded to itself or glass using plasma ionization treatment
- Small Young's modulus beneficial for fluidic valves

**Microfluidic Mold Fabrication:**
1. **Preliminary Step**: Microfluidic molds fabricated using photolithography of SU8 onto silicon substrates
   - Two different types of SU8 used: 100m thick for temperature control channels, 5m thick for cell channels
   - Mold coated with an anti-adhesive treatment to prevent photoresist patterns from being removed during replicaition
2. **Step 1: PDMS Preparation**
   - Homogenize PDMS and curing agent mixture without air bubbles
   - Degas the mixture in a vacuum chamber to remove bubbles
3. **Step 2a: Fabrication of Temperature Control Channels**
   - Pour cured PDMS onto temperature control mold
   - Remove air bubbles and cure PDMS block
4. **Step 2b: Fabrication of Cell Channels**
   - Repeat steps for cell channel mold
5. **Step 3: Plasma Bonding**
   - Bond the two layers of PDMS together using plasma treatment
6. **Step 4: Assembly**
   - Release the PDMS parts from molds and drill inlets
   - Bond the bilayer assembly to a glass coverslip using plasma treatment
7. **Fabrication Process Diagram**: (Figure 2)

---

#### Fabrication and Assembly of Microfluidic Device for Studying Cell Microtubules

**PDMS Device Fabrication: Bilayer PDMS Block**

**Step 2b: Fabrication of Cell Channel Layer**
- Place cell microchannel mold in spin coater
- Pour degassed PDMS mixture on mold, covering about 30% of surface
- Spin coat at 500 rpm for 10 seconds and 6000 rpm for 30 seconds to spread even layer approximately 15 m thick
- Cure on hotplate at 95C for 30 minutes
- Store mold with PDMS membrane in closed Petri dish, membrane side up

**Remarks:**
- Thinness of membrane critical for heat transfer between temperature control and cell channels
- PDMS mixture should be freshly made and degassed before spin coating to maintain viscosity
- Handle PDMS surface containing microchannels carefully during fabrication process

**Step 3: Plasma Treatment and Bonding of Both PDMS Layers (Temperature Control and Cell Microchannels)**
- Place both top PDMS block (microchannel side up) and bottom PDMS mold into plasma chamber
- Vacuum on to stabilize pressure between 500 mTorr and 1000 mTorr
- Turn RF power on high for 30 seconds to ionize surfaces, observe purple glow
- Release vacuum and immediately place top PDMS block (microchannel side down) on bottom PDMS mold
- Heat assembly on hotplate at 95C for 30 minutes to cure bond
- Cut out and peel up complete bilayer PDMS block
- Drill inlet and outlet holes using 20-gauge needle, store device in closed Petri dish with microchannel side up

**Remarks:**
- Eliminate dust on surfaces before plasma treatment by blowing or using Scotch tape
- Proper plasma color indicates efficient plasma treatment for bonding
- Long waiting time after plasma treatment decreases bond efficiency
- Position bottom cell channels under center of top temperature control channels for optimal temperature uniformity.

---

#### Microfluidic Device Setup and Connection for Studying Microtubule Dynamics in Fission Yeast

**Experimental Setup and Procedure for Using Peltier Modules in Microfluidic Devices**

**Preparation of Peltier Modules**:
- Connect Peltier outlet to PDMS device using a 2 cm PE tubing and a 4 cm Microline tube
- Terminate the tubing assembly by a stainless steel adaptor that fits into the inlet hole of the PDMS device
- Repeat for the second Peltier module
- Connect Peltier inlets to water source using the same tubing assembly as above
- Tape tubings at strategic points on or around the microscope stage to prevent accidental lifting and leakage

**Connection of Peristaltic Pump to Peltier Module**:
- Use a closed-loop 2 L water reservoir bottle connected to Tygon R-1000 silicon tubing driven by peristaltic pumps
- Cool the Peltier modules using the peristaltic pump system to maintain proper function
- Increase pump flow rate or decrease reservoir temperature for low temperature experiments
- Take care to avoid leakage due to high water flow rates and ensure secure connections

**Device Preparation and Cell Injection**:
- Use a small syringe with a 24-gauge needle connected to a Microline tube and stainless steel adaptor for cell handling
- Fill the syringe with cells without air bubbles
- Plug the PDMS device inlet with cells and inject gently, avoiding air bubbles
- For experiments longer than 23 hours, fill outlet tubing with media and renew as needed to prevent nutrient depletion
- Visualize air bubbles on a black background for easier detection.

---

#### Device Temperature Control and Characterization for Microtubule Studies

**Installing PDMS Device (PDMS Device Installation)**
- **Step 1: Installing the PDMS Device on the Peltier Setup**
  1. Install a large 200-ml syringe filled with water onto the syringe pump.
  2. Connect both Peltier modules to the PDMS device, syringe pump, and peristaltic pump cooling system.
  3. Start syringe pump until all tubings connected to temperature channels are filled with water (important for fast temperature change).
  4. Peristaltic pumps start at 100 ml/min rate.
  5. Set Peltier modules at desired temperatures.
- **Remarks**
  * No leakage indicates readiness to put PDMS device on microscope for cell search.

**Performing Temperature Changes (Temperature Changes)**
- **Step 2: Performing Temperature Changes**
  1. Syringe pump pushes water through upstream Peltier module at 2.5 ml/min flow rate to thermalize PDMS microfluidic device and initiate temperature change with a delay of 1015 seconds and precision <1C.
  2. For cooling, syringe pump pulls (reverse direction) water through downstream Peltier module at 2.5 ml/min flow rate to thermalize PDMS microfluidic device.
- **Remarks**
  * Temperature control critical: heat dissipation and objective position impact temperature measurement.
  * Oil immersion objectives act as a strong heat sink, leading to increased temperatures.
  * Focus drift can be corrected during image acquisition due to predictable nature of temperature changes.

**Device Characterization (Device Characterization)**
- **A) Schematic detailing the temperature control procedure**: when syringe pump is OFF, device remains at ambient temperature; when pushing or pulling, temperature change depends on upstream Peltier setting. Changing downstream Peltier does not affect device temperature.
- **B-C) Device temperature versus syringe pump flow rate (cold and hot Peltier settings)**.
- **D) Calculation of device temperature as a function of Peltier module temperature with ambient temperature of 25C**: Tdevice = Tpeltier  (ATambient/300) + (1 - ATambient/300)  Tpeltier when objective is in contact, or Tdevice = Tpeltier  (2.21  ATambient/300) + (1 - 2.21  ATambient/300)  Tpeltier when not in contact.
- **E) Time lapse montage of microtubule dynamics in fission yeast responding to temperature changes**: at 6C, microtubules depolymerized; at ambient room temperature (23C), microtubules repolymerized.

---

#### Fabrication and Use of Micro-Fluidic Temperature Control Device for Studying Fission Yeast Microtubule Dynamics

**Protocol for Fabrication and Use of Fast Micro-Fluidic Temperature Control Device in Fission Yeast S. pombe**

**I. Introduction:**
- Cooling and heating microtubules using fast micro-fluidic temperature control system
- Fine control over microtubule polymerization dynamics
- System can be used with temperature-sensitive mutant strains
- Opportunities for new cell biological experiments

**II. Materials:**

**A. Mold Fabrication:**
- Spincoater, Laurell CZ-650 series
- Hotplate, Barnstead HP131720-33
- UV lamp, OAI 30 with intensity controller model 2105C2
- Photoresist: Microchem SU8 2005, 2050, and developer
- Isopropanol
- SU8 photoresist omnicoat

**B. Device Fabrication:**
- Hotplate, Barnstead HP131720-33
- Oven, MEMMERT 14L UNB100
- Plasma cleaner, Harrick plasma Extended plasma cleaner with pressure controller
- Inlet and outlet drilling: 20-gauge needle smoothed with sandpaper
- PDMS, Sylgard 184
- Coverglass, Dow Corning 24 /C2 40 mm ref 2940-244

**C. Temperature Control Setup:**
- Peltier, Warner SC-20 Dual In-line Solution Heater/Cooler
- Peltier controller, CL-100 Bipolar Temperature Controller
- Syringe pump: Harvard Apparatus Remote Infuse/Withdraw PHD 4400 Hpsi
- Peristaltic pump, Harvard Apparatus Peristaltic Pump 66
- Peristaltic pump tubing: Tygon R-1000 1/8 in. ID * 1/4 in. OD
- Peltier metal tube/Microline tubing interface, Warner Polyethylene tubing 1.57OD * 1.14ID (furnished with Peltier module)
- Microfluidic device/Microline tubing interface, Harvard Apparatus Stainless steel tubing coupler, 23-gauge, 8 mm
- Syringe for water injection: Monoject 140cc Syringe with Luer Lock Tip

**D. Cell Injection:**
- 2 ml syringe
- 24-gauge needle
- Microline tubing 0.5 mm ID * 1.5 mm OD, Harvard Apparatus
- Microfluidic device/Stainless steel tubing coupler, 23-gauge, 8 mm

---

### Chapter 12: Microtubule-Dependent Spatial Organization of Mitochondria in Fission Yeast

**I. Introduction:**
- Cytoskeleton controls mitochondrial distribution, dynamics, and inheritance in eukaryotic cells
- Defects in axonal mitochondrial transport linked to neurodegenerative diseases like Charcot-Marie-Tooth (CMT 2A) disease and Huntington's disease
- Fission yeast Schizosaccharomyces pombe is a powerful genetic model system for studying microtubule-dependent mitochondrial movement, dynamics, and inheritance

**II. Visualization of Mitochondria in Fission Yeast:**
A. **Growth of Fission Yeast Cells**:
- Mitochondrial visualization using vital dyes
- Expression of mitochondria-targeted fluorescent fusion proteins
- Immunostaining for MTs and mitochondria
- Electron tomography analysis of MT and mitochondrial organization

**III. Functional Analysis of MTMitochondria Interaction in Live Cells**:
A. **Pharmacological Disruption of MT Organization**:
- Identification of mutants that disrupt mitochondrial distribution

**IV. Purification and Subfractionation of Fission Yeast Mitochondria**:
A. Growth of fission yeast cells
B. Isolation of mitochondria
C. Mitochondrial compartments and protein localization

---

#### Visualization Techniques in Fission Yeast Mitochondria  Microtubules

**Mitochondrial Positioning in Fission Yeast**

**Findings**:
- Mitochondrial spatial organization and dynamics are cell type/tissue specific in higher eukaryotes
- Long-distance mitochondrial transport is crucial for neuronal function
- In fission yeast, the kinesin motor Klp3 does not seem to have a role in mitochondrial distribution

**Mitochondrial Transport**:
- In neurons, long-distance mitochondrial transport is mediated by **kinesins (e.g., kinesins 1-3) and dyneins**
- In fission yeast, the **Klp3 kinesin homologue** does not appear to have a role in mitochondrial distribution
- The function of the **Miro1/Miro2 protein homologue** is currently unknown

**Visualization Methods**:
- Mitochondria can be visualized using immunostaining, vital dyes, or fluorescent proteins targeted to mitochondria
- MTs can be visualized using immunostaining and ectopic expression of fluorescent alpha tubulin fusion protein
- Electron tomography can be used for fine ultrastructural details and 3D reconstruction

---

#### Visualization of Mitochondria and Microtubules in Fission Yeast using Dyes Protein Fusions and Immunostaining

**Mitochondrial Visualization in Fission Yeast**

**A. Minimal Media and Supplements**:
- Defined media used for experimental reproducibility and plasmid selection
- Supplements added according to auxotrophic markers and plasmid selection

**B. Visualization of Mitochondria using Vital Dyes**
1. **MitoTracker Red CMXRos**:
   - 5 mM in DMSO (stock solution)
   - Steps:
      * Grow cells in suitable media with aeration for 8 generations
      * Add dye, shake for 20 minutes at 32C
      * Centrifuge and resuspend cells in media
      * Mount on slide and observe under fluorescent microscope
   - Can use other MitoTracker dyes of various wavelengths

**C. Expression of Mitochondria-Targeted Fluorescent Fusion Proteins**:
1. **COX4-RFP**:
   - COX4 gene fused to RFP, under thiamine-inducible nmt1 promoter
   - Integrated at the leu1 locus in S. pombe genome using pJK-148 vector
2. **Other Mitochondrial Fluorescent Fusion Proteins**:
   - Sdh2-GFP, Aco1-GFP, mCherry-Arg11, Bot1-GFP allow visualization without disturbing mitochondrial function or morphology

**D. Immunostaining Visualization of MTs and Mitochondria**:
1. **Protocol**:
   * Collect cells by centrifugation
   * Resuspend in methanol, then PEM buffer
   * Pellet and wash cells
   * Incubate with primary antibodies (anti-HSP60, anti-F1-ATPase, anti-TAT-1)
   * Incubate with secondary antibodies (Texas Red anti-mouse, fluorescein anti-rabbit)
2. **Reagents**:
   - Methanol at 20C
   - PEM buffer: 100 mM Pipes, 1 mM EGTA, 1 mM MgSO4 (pH 6.9)
   - PEMS: PEM with 1.2 M sorbitol and 1% BSA
   - Other: SDS, Zymolyase T20, Novozyme, triton X-100, lysine hydrochloride

---

#### Mitochondria and Microtubule Interaction Analysis

**Microscopic Analysis of MT and Mitochondrial Dynamics**

**Procedure**:
1. **Incubation and Digestion:**
   a. Incubate cells for 510 minutes at 37C to obtain 80% cell wall digestion.
   b. Add 20% SDS to 9.5 l of cells and look for percentage of ghost cells by light microscopy to determine extent of digestion. Do not over-digest.
2. **Subsequent Washes:**
   a. Resuspend in 1 ml PEMBAL and incubate for 1 h at room temperature on a wheel.
   b. Pellet cells, resuspend in 100 l PEMBAL, and repeat steps (a) to (c) two more times:
      i. **Wash 1/C2 PEM**
      ii. **Wash 2/C2 PEMS**
      iii. **Wash 1/C2 PEMS with 1% TritonX-100**
      iv. **Final Wash in 100 l PEM**
3. **Immunofluorescence Staining:**
   a. Resuspend cells in 1 ml PEMBAL and incubate overnight at room temperature on a wheel with primary antibodies.
   b. Wash cells three times with PEMBAL.
   c. Resuspend cells in 100 l PEMBAL, incubate with secondary antibodies for 12 hours at room temperature on a rotating wheel (cover the microfuge tube with foil).
   d. Wash cells three times with PEMBAL.
4. **Cell Storage:**
   Cells can be kept at 4C for days; leaving cells in PEMBAL for 24-48 hours will reduce background.
5. **Microscopic Analysis:**
   A. Fluorescently tagged tubulin (Atb1-GFP) and Cox4-RFP can be visualized to understand MT-dependent mitochondrial dynamics.
   B. Time-lapse imaging of these proteins can visualize the movement of cellular structures in the cell.
6. **Live Cell Microscopy**:
   a. Strain expressing transgenes COX4-RFP and atb1-GFP under nmt1 thiamine repressible promoter is used for live cell microscopy.
   b. Cells are grown in minimal media without thiamine for 48 hours, then shifted to minimal media with 15 mM thiamine for 16-24 hours.
   c. Cells are collected and seeded on a pad (YE, with supplements, and gelatine) on a slide; apply coverslip and seal with valap.
   d. Cells are viable for 48 hours without mitochondrial morphology defects, allowing time-lapse imaging of mitochondria and MT dynamics.
7. **Imaging Technologies**:
   An Axiovert 200M microscope with a spinning disk confocal head and argon/krypton laser can be used to visualize mitochondrial distribution regulated by CLASP.

---

#### Purification and Subfractionation of Fission Yeast Mitochondria for Protein Analysis

**Mitochondrial Distribution in Fission Yeast: Techniques and Approaches**

**Identification of Mutants Disrupting Mitochondrial Distribution:**
- Classical mutagenesis using ethylmethanesulfonate (EMS)
  - Grow cells on YE agar medium at 25C and screen for lack of growth at 36C
  - Temperature-sensitive strains identified by fluorescence microscopy for abnormal mitochondrial morphology or distribution

**Genetic Dissection of MT-Dependent Mechanisms:**
- Recent advances: whole genome sequencing and haploid deletion library creation
  - Easier deletion of genes of interest using PCR-mediated approaches
  - Systematically analyze deletion mutants for mitochondrial distribution and morphology

**Purification and Subfractionation of Fission Yeast Mitochondria:**
- Useful for assaying mitochondrial localization of proteins involved in MT-mitochondrial interaction and testing their association with inner membrane or matrix.
- Extensive description of respiratory physiology, mitochondrial genome structure, and methods for mitochondrial purification and subfractionation published previously (Chiron et al., 2007; Gouget et al., 2008).

---

#### Isolating and Localizing Mitochondrial Proteins

**Mitochondrial Isolation Procedure for Fission Yeast**

**Spatial Organization of Mitochondria in Fission Yeast**

1. **Protoplast Lysis**: Resuspend pellet in 1520 ml lysis buffer, incubate for 15 minutes on ice, centrifuge at 2500/C2g for 15 minutes at 4C. Transfer the supernatant to a fresh tube and discard the pellet. Repeat the process if necessary.
2. **Mitochondrial Collection**: Collect mitochondria from the supernatant by centrifugation at 12,000/C2g for 15 minutes at 4C. Resuspend in 2 ml lysis buffer with 0.5% BSA and spin down again. Transfer the supernatant to a fresh tube and remove the pellet. Repeat this step to obtain more purified mitochondria.
3. **Protein Measurement**: Measure protein concentration by taking 10 ml of mitochondrial prep, mixing with 990 ml of 0.6% SDS, measuring OD at 280 nm. Absorbance of 0.21 corresponds to a protein concentration of 10 mg/ml.
4. **Mitochondrial Components and Protein Localization**: Analyze the mitochondrial localization of proteins influencing mitochondrial organization and dynamics by testing for the presence of the protein of interest in different subfractions of mitochondria using western blot analysis.
5. **Subfractionation of Mitochondria**: Subfractionation of fission yeast mitochondria has been described previously (Chiron et al., 2007). The protocol below is used to establish the integrity of purified mitochondria and determine if the protein of interest associates with the outer membrane or is situated inside the mitochondria.

**Protocol for Proteinase K Treatment**
1. **Buffers and Reagents**: Sonication buffer: 0.6 M sorbitol-10 mM imidazole-HCl, pH 6.4, 2 mM EDTA; proteinase K (50 g/ml); PMSF (2 mM); Laemmli buffer (1X): 1% sodium dodecyl sulfate, 50 mM Tris HCl (pH 6.8), 4% glycerol, 0.4% b-mercaptoethanol; antibodies for western blot analysis: rabbit polyclonal anti-F1-ATPase (1:5000) and rabbit polyclonal anti-Tom70 (1:5000).
2. **Protocol Steps**:
   a. Resuspend mitochondria at a protein concentration of 8 mg/ml in sonication buffer. Divide the preparation into four fractions.
   b. Fraction 1 will not be treated; leave it on ice.
   c. Disrupt mitochondria in fractions 3 and 4 by sonic irradiation using a VirSonic 100 sonicator at intensity 4 for 5 seconds. Place fraction 3 on ice and proceed with fractions 2 and 4.
   d. Add proteinase K to fractions 2 and 4 at a final concentration of 50 g/ml, incubate on ice for 60 minutes. Stop the reaction with PMSF at a final concentration of 2 mM.
   e. Recover mitochondria from all four fractions by centrifugation at 100,000/C2g.
   f. Resuspend the pellet in Laemmli buffer and separate different protein fractions by SDS-polyacrylamide gel electrophoresis on a 12% polyacrylamide gel.
3. **Western Blot Analysis**: Perform western blot analysis with antibodies against subunit b of the membrane-associated F1 portion of the F1F0 ATPase, Tom70, and the protein or tagged fusion protein under study.
4. **Protein Localization**: Proteins localized inside mitochondria (e.g., F1-ATPase) are not digested by proteinase K in the absence of sonication, while proteins localized on the outer membrane (e.g., Tom70) are digested even without sonication. If the mitochondrial membrane is disrupted during isolation, the F1-ATPase will also disappear in fraction 2 treated with proteinase K in the absence of sonication. Note that matrix soluble proteins remain in the supernatant after centrifugation and will not be detected without proteinase K treatment.

---

### Chapter 13: Microscopy Methods for the Study of Centriole Biogenesis and Function in Drosophila

**Centrioles in Drosophila: Methods for Studying Centriole Biogenesis and Function**

**I. Introduction:**
- Regulate cell motility, adhesion, polarity during interphase and mitosis
- Composed of two centrioles and a proteinaceous matrix called pericentriolar material (PCM)
- Essential for axoneme formation in cilia and flagella
- Centrosome abnormalities linked to genomic instability, stem cell homeostasis issues, and some cancers
- Two main components: mature or mother centriole and daughter centriole
- Mother centriole orthogonally configured with the daughter one

**II. Centrioles in Drosophila Early Embryogenesis:**
A) **Immunofluorescence of Embryos/Eggs:**
- Used to study centriole assembly and function as a centrosome organizer during mitotic cell divisions
- Visualize specific proteins through antibodies labeled with fluorescent dyes

B) **Transmission Electron Microscopy of Embryos:**
- Reveals ultrastructure details, such as the presence of radial symmetry and microtubule doublets

C) **Immunoelectron Microscopy of Embryos:**
- Combines advantages from both immunofluorescence and transmission electron microscopy techniques to visualize specific proteins in ultrastructural contexts

**III. Centrioles in Drosophila Spermatogenesis:**
A) **Phase Contrast and Immunofluorescence of Testes:**
- Visualize basal bodies, axonemes, and their microtubule structures

B) **Transmission Electron Microscopy of Testes:**
- Determine morphology and dimensions of centrioles and axonemes
- Investigate centriole components, such as radial symmetry, microtubule triplets, and spoke tips

C) **Immunoelectron Microscopy of Testes:**
- Study specific proteins involved in centriole biogenesis or function

---

#### Drosophila Early Embryogenesis Centriole Biogenesis and Function

**Drosophila Melanogaster Life Cycle and Centrioles:**
- Drosophila life cycle includes egg, larva, pupa, and adult stages
- Larval development occurs over three instars, each lasting one day
- Pupation leads to eclosion of adults in approximately 10 days at 25C

**Centrioles in Drosophila:**
- Centrioles studied during various developmental stages: early embryos, neurogenesis, spermatogenesis
- Early embryogenesis offers fast cell cycles and easy study techniques like immunofluorescence, TEM, biochemical fractionation, injection of proteins/drugs, live imaging (Foe et al., 1993)
- Neurogenesis provides insights into centrosome behavior in asymmetric stem cell divisions and ciliated mechanosensory cells formation (Gogendeau & Basto, 2009; Januschke & Gonzalez, 2008)
- Spermatogenesis offers a great example of centrosome behavior during asymmetric stem cell division and differentiation into flagella basal bodies (Yamashita, 2009; Yamashita & Fuller, 2008)
- Most somatic cells can form normal spindles without centrioles, but mitosis in early embryogenesis and meiosis in spermatogenesis require centrosomes for accurate division (Rodrigues-Martins et al., 2008)

**Centrosome Formation:**
- De novo centrosome formation studied during unfertilized egg stages without centrioles (Peel et al., 2007; Rodrigues-Martins et al., 2007b)

**Centriole Characteristics and Separation:**
- Drosophila centrioles are shorter than mammalian counterparts (approximately 200 nm vs. 500 nm)
- Centrioles lose orthogonal arrangement in metaphase to anaphase transition, move apart during anaphase, and become widely separated at telophase.

---

#### Centriole Formation and Immunofluorescence Analysis in Drosophila Embryos

**Concomitantly with PCM expansion, the centrosome splits into two units during late telophase:**
- The PCM consists of components like gTubulin and DPLP (Drosophila Pericentrin Like Protein) that are present at the centrosome
- Other centrosomal components like Polo and CP190 are only recruited during centrosome maturation
- De novo centrosome formation has been studied using Drosophila embryos and unfertilized eggs

**De novo centrosome formation:**
- In Drosophila oogenesis, centrioles are lost from the oocyte, so no centrioles are present in the unfertilized egg
- Upon overexpression of certain centriolar proteins like SAK/PLK4, centrioles can be formed, helping to understand intermediate steps in centriole formation

**Embryo/Egg Collection:**
1. **Canonical Centriole Cycle**:
   - Collect embryos at 10-minute intervals
   - Replace collection plates every 15 minutes before starting the experiment
   - Embryos can be collected at different time points for experimental needs
2. **De Novo Centrosome Formation**:
   - Collect unfertilized eggs from virgin females
   - Dechorionate the embryos/eggs by immersing them in a 50% bleach solution
   - After dechoronation, remove the vitelline membrane for proper antibody penetration
3. **Immunofluorescence Analysis**:
   - Wash fixed embryos/eggs with PBST to remove methanol fixative
   - Blocking is done by incubating in PBSTB for 30 minutes
   - Primary antibodies are diluted and incubated for 2 hours at room temperature or overnight at 4C
   - Wash embryos/eggs with PBSTB before adding secondary antibodies
   - Finally, wash with PBS before transferring to glass slides containing Vectashield mounting media for fluorescence.

**Table I:** Commonly used centrosomal-related primary antibodies and their working dilutions.

---

#### Immunofluorescence and Electron Microscopy Protocols for Drosophila Centrioles Analysis

**Immunofluorescence Protocol for Drosophila Embryos and Testes**

**Procedure**:
- Collect embryos/eggs at 1.5 hours after fertilization
- Observation of centrosomes using gTubulin antibody
- Glutaraldehyde fixation, rinsing, and washing steps
- Postfix in osmium tetroxide
- Dehydration and embedding in resin
- Sectioning and staining for microscopy

**List of Centrosomal-Related Primary Antibodies**:
- Rat anti--Tubulin (YL1/2)
- Mouse anti--Tubulin (GTU88)
- Rabbit anti-centrosome (CNN)
- Chicken anti-D-PLP and rabbit anti-D-PLP
- Rabbit anti-CP190
- Rabbit anti-DSAS-4
- Mouse anti-acetylated -tubulin (6-11B-1)
- Mouse anti-glutamylated tubulin (GT335)

**Transmission Electron Microscopy of Embryos/Eggs**:
- Collection and dechorionation of embryos/eggs
- Removal of vitelline membrane using glutaraldehyde, heptane, and double-sided scotch tape
- Fixation overnight in 2.5% glutaraldehyde
- Rinsing and postfixing in 1% osmium tetroxide
- Dehydration using a graded series of alcohols
- Embedding in resin and sectioning for microscopy

**Immunoelectron Microscopy of Embryos**:
- Useful to understand the ultrastructural aspects of centrioles, but does not provide spatial localization of proteins.

---

#### Immunoelectron Microscopy of Drosophila Embryos Pre- and Postembedding Methods for Antigen Localization in Centrioles

**Immunoelectron Microscopy for Antigen Localization**
- **Powerful tool** due to high resolution, not achievable with conventional immunofluorescence
- **Important considerations:**
  * Critical fixation step: aldehyde fixatives can reduce tissue immunoreactivity
  * Secondary antibodies used for immunoelectron microscopy are conjugated with gold particles (5-10 nm diameter)
    * Requires best possible membrane permeabilization and cytological integrity
- **Two approaches:** preembedding or postembedding method

**Preembedding Immunoelectron Microscopy of Embryos**
1. Collection and dechorionation:
   - Embryo transfer to a glass vial with formaldehyde, heptane, and PBS
   - Devitellinization using tungsten needles
   - Staining DNA with Hoechst 33258 for selected stages under fluorescence microscopy
   - Cutting embryos longitudinally into thin strips for better penetration of antibodies
   - Incubating in a blocking solution (PBSB) and diluted primary antibodies overnight or longer on a wheel rotator at 4C
2. Post-processing:
   * Washing with PBSB
   * Incubating with secondary antibodies conjugated with 5 nm colloidal gold for better penetration
   * Fixing overnight in Karnovsky solution (glutaraldehyde and paraformaldehyde)
   * Postfixation with osmium tetroxide, dehydrating, and embedding as described above
3. Detection:
   - Grazing sections adequate to detect antibodies interacting with nuclei-associated centrioles
   - Thin sections counterstained with uranyl acetate and lead citrate as usual

**Postembedding Immunoelectron Microscopy of Embryos**
1. Collection and dechorionation: same as preembedding method
2. Fixation and embedding: fix in 4% formaldehyde, avoid or use lower concentration of osmium tetroxide, dehydrate and embed in a hydrophilic resin (Lowicryl K4M, L.R. White, or L.R. Gold)
3. Sectioning: collect thin sections on nickel or gold grids due to challenges with hydrophilic resins
4. Immunostaining and post-processing: same as preembedding method
5. Detection: same as preembedding method. Centrioles in Drosophila Spermatogenesis: a variety of cell divisions characterize spermatogenesis; centrioles become basal bodies and elongate from 0.5 to 2.3 meters during this process.

---

#### Drosophila Spermatogenesis and Microtubule Formation in Testes

**Drosophila Spermatogenesis**

**Phases:**
- **Asymmetric division**: germ line stem cell divides to produce primary spermatogonial cell and another stem cell
- **Mitosis (4 rounds)**: 16 primary spermatocytes generated per cyst, interconnected by intracellular bridges
  * Extended G2 phase: cells grow 25 times in volume, transcribe gene products required for meiosis
  * Longest phase of growth and development
- **Meiosis I**: primary spermatocytes enter with two centrosomes (each composed of two V-shaped centrioles)
  * Short period between divisions, no duplication of centrosomes in Meiosis II cells
  * Each centriole contains only one centriole
- **Meiosis II**: cyst containing 64 mature haploid spermatids formed
  * Cells remain interconnected by cytoplasmic bridges, ring canals seen in the cytoplasm

**Haploid Spermatids:**
- Enter extensive differentiation program with morphological changes
- Long flagellar axonemes form, most cytoplasmic material discarded, nuclei transformed into needle-shaped sperm heads
- Axoneme nucleation from basal body begins in the cytoplasm
  * Proximal centriole-like structure present at end of differentiation (Blachon et al., 2009)

**Centrioles:**
- Biogenesis and axoneme formation studied using centrosome function
- Centrioles/basal bodies composed of nine triplets of microtubules
- Axonemes have nine doublets of microtubules, central pair required for sperm motility

**Microscopy Methods:**
- Live imaging and immunofluorescence used to study centrioles and axoneme formation
  * Shorter centrioles observed in SAS-6 mutants (Peel et al., 2007; Rodrigues-Martins et al., 2007a)
  * D-PLP essential for integrity of centrioles/basal bodies, often fragmented in D-PLP mutants (Martinez-Campos et al., 2004)

**Phase Contrast and Immunofluorescence:**
- Testes dissected from pharate adults for higher proportion of G2-phase cells and primary spermatocytes
  * Identify male pharate adults by black sex combs in their legs
  * Carefully dissect testes from lower part of abdomen, attached to hub where stem cells remain
- Testes contain a spatial-temporal array of spermatogenic stages from apical to basal localization.

---

#### Drosophila Spermatogenesis Imaging via Phase Contrast and Immunofluorescence Microscopy

**Drosophila Spermatogenesis Imaging: Microscopy Methods for Centrioles**

**Phase Contrast Imaging**:
- Wipe off excess liquid under dissection scope, stop wiping when sperm tails become visible
- Start imaging right away before sample dries
- Figure 7A shows examples of cells at the Nebenkern stage (1:1 ratio of similar sized nuclei and Nebenkern)

**Immunofluorescence**:
- Perform testes dissection in TB buffer (183 mm KCl, 47 mm NaCl, 1 mm EDTA, 10 mm TrisHCl, pH 6.8) under a dissection scope
- Use three pairs of testes per slide and three slides per antibody
- After dissection, transfer testes to 4L TB buffer drop on poly-L-lysine-coated glass slide treated with siliconized coverslips
- Open the testes twice with forceps for antibody penetration
- Freeze the slide in liquid nitrogen (do not leave slides in liquid nitrogen for more than 1 h)
- Fix slides in dry ice-cold methanol for 8 min
- Transfer slides to acetone and incubate for 10 min
- Wash slides three times with PBS at room temperature
- Blocking is done in upright slide box in PBSB (1% BSA in PBS) for 1 h
- Incubate primary antibodies for 2 h at room temperature or overnight at 4C
- Wash slides three times, 15 min each, with PBSB
- Dilute secondary antibodies 1:100 (or according to manufacturer's instructions) in PBSB and incubate for 2 h at room temperature and in the dark
- Wash slides three times, 15 min each, with PBS
- Perform a fourth wash with PBS
- DNA staining can be achieved by incubating testes with Toto-3-Iodide (Molecular Probes) for 10 min at room temperature

**Transmission Electron Microscopy**:
- Dissection of testes can be done in PBS
- Transfer dissected testes to glass vials, fix by immersion in 2.5% glutaraldehyde in PBS for 2 h on a wheel rotator
- Rinse three times, 30 min each, in PBS to remove all traces of fixative
- Wash in distilled water three times, 10 min each
- Postfix in 1% aqueous osmium tetroxide for 1 h at 4C on a wheel rotator (longer exposures may result in extraction of nucleus and cytoplasm)
- Wash in distilled water three times, 10 min each
- Dehydrate in a graded series of alcohol (70%, 90%, absolute) to properly infiltrate embedding media

---

#### Electron Microscopy of Drosophila Testes Centrioles Pre- and Post-Embedding Immuno-Electron Microscopy Methods

**Drosophila Testes Preparation for Electron Microscopy**

**Dehydration Steps:**
- Take at least 10 minutes per step
- Repeat dehydration in absolute alcohol at least three times

**Intermediate Solvent:**
- Use propylene oxide for electron microscopy purposes
- Incubate testes in 1 ml of propylene oxide three times for 10 minutes each
- Be careful not to let the testes dry as this solution is very volatile

**Embedding Resin:**
- Use graded mixture of propylene oxide and embedding resin
  - Propylene oxide:2:1 resin
  - Propylene oxide:1:1 resin
  - Propylene oxide:1:2 resin
- Incubate for a minimum of 1 hour in 2 ml of pure embedding resin (EMS Embed 812) on a wheel rotator at slow speed
- Transfer each testis to a flat embedding mold for EM

**Positioning Testes:**
- Position the testes in the resin according to experimental needs
  - Orient perpendicularly to the cutting face for good cross sections of cysts

**Trimming and Cutting:**
- Allow the resin to polymerize at 60C for 48 hours
- Trim the block following standard technique
- Cut thin sections (6080 nm thick) of uniform thickness and as free of compression, scratches, vibrations, and wrinkles as possible
- Collect sections on grids (200 300 mesh)

**Staining:**
- Transfer grids into a drop of 2 percent uranyl acetate in 70 percent methanol for 34 minutes
- Methanol enhances the contrast given by uranyl acetate
- Wash the grid in two drops of 70 percent methanol followed by five drops of distilled water
- Transfer to a drop of Reynolds lead citrate for 12 minutes using clean tweezers
- Staining duration should be optimized, normally between 3 and 5 minutes for uranyl acetate and 1 and 5 minutes for lead citrate
- Wash in five drops of water and let it dry at room temperature
- Grids can be stored at room temperature in gelatin capsules or inside grid boxes.

---

### Chapter 14: Drosophila S2 Cells as a Model System to Investigate Mitotic Spindle Dynamics, Architecture, and Function_243

**Mitotic Spindle Dynamics in Drosophila S2 Cells**

**Introduction:**
- Mitotic spindles essential for maintaining genetic content and cell division
- Highly conserved, redundant process involving multiple parallel pathways
- Centrosome-driven search-and-capture model proposed by Kirschner and Mitchison (1986)
  * Astral microtubules grow and shrink, randomly searching for chromosomes after nuclear envelope breakdown* Increased CDK1 activity results in phosphorylation of regulatory MAPs
- Cannot explain mitosis in cells lacking centrosomes like higher plants and some oocytes (Gadde and Heald, 2004; Wadsworth and Khodjakov, 2004)
- Random search-and-capture model not sufficiently efficient to capture all kinetochores in animal cells (McEwen et al., 1997; Wollman et al., 2005)
- Centrosome-independent search-and-capture events may be present (Lloyd and Chan, 2006)

**Alternative Mechanisms for Spindle Assembly:**
- Anastral spindles assembly in the absence of centrosomes
  * Drosophila cell line lacking centrioles maintained in culture for several years (Debec et al., 1995)
  * Centrosomin (Cnn) or Dsas-4 mutants develop into adult flies (Basto et al., 2006; Megraw et al., 2001)
- Self-organization of microtubules in the vicinity of chromosomes responsible for spindle assembly
  * Kinetochores form their own K-fibers and ensure bipolarity through microtubule motors and cross-linking proteins (Karsenti and Vernos, 2001; Rieder, 2005)

**Microtubule Propagation within Spindle:**
- Microtubule propagation within spindle region a potential mechanism for spindle morphogenesis
- Discovery of augmin complex and its interaction with g-tubulin and associated factors in the spindle region (Goshima et al., 2007, 2008; Uehara et al., 2009; Zhu et al., 2008)

**Methods:**
- Live cell microscopy analysis of mitotic spindle assembly
- Pharmacological inhibition and RNA interference of proteins impairing microtubule dynamics
- Fluorescent speckle microscopy investigation of poleward flux in spindle microtubules
- Laser microsurgery to study specific spindle structures (e.g., centrosomes, microtubules, and kinetochores)

**Conclusion:**
- Both centrosomes and kinetochores contribute to spindle assembly; acentrosomal mechanisms may be present even in those systems relying on centrosomes.

---

#### Live Imaging of Mitotic Spindle Assembly in Drosophila S2 Cells with Fluorescently Tagged Components

**Methodologies for Studying Mitotic Spindle Dynamics in Live Drosophila Culture Cells**

**Live Cell Microscopy Analysis of Mitotic Spindle Assembly:**
- Use of fluorescently tagged components: GFP-a-tubulin and Centromere Identifier (CID) fused to mCherry
- Create stable cell line by transfecting with plasmids containing resistance genes for selection, such as blasticidin or hygromycin
- Use of copper-inducible metallothionein promoter for desired expression levels

**Materials:**
- Drosophila S2 cell lines expressing various fluorescently tagged components of the mitotic apparatus
- Gateway Cloning System (Invitrogen) for creating stable cell lines
- Cellfectin reagent (Invitrogen) for transfection
- Concanavalin A-coated coverslips and modified Rose chambers for live cell analysis

**Methods:**
1. Live imaging studies using available fluorescently tagged components
2. Use of RNAi for high spatiotemporal resolution in a living dividing cell
3. Monitor microtubule organization during spindle assembly with GFP-a-tubulin and CID-mCherry-expressing cells
4. Generate stable cell lines using Gateway Cloning System or Cellfectin reagent and optimized protocols
5. Use copper-inducible metallothionein promoter for desired expression levels.

---

#### Live Cell Imaging of Mitotic Spindle Assembly in Drosophila S2 Cells

**Mitotic Spindle Assembly in Drosophila S2 Cells:**
* Two types of mitotic spindle assembly: dominant centrosomal and chromatin/kinetochore-mediated
+ Dominant centrosomal: control cells, microtubules assembled around centrosomes
+ Chromatin/kinetochore-mediated: Cnn-depleted cells, spindle built through chromatin and kinetochores
* Live cell imaging reveals undisclosed aspects with an agar overlay or different microscopes
* Mitotic poisons disrupt/alter microtubule properties for studying dynamics
**Mitotic Poisons:**
* Colchicine, colcemid, nocodazole, vinca alkaloids: prevent new polymer formation by binding soluble tubulin
* Taxanes: stabilize GDP-bound tubulin and cause hyperstabilization of microtubules
**Impact on Mitotic Spindle:**
* Colchicine disrupts microtubule assembly, leading to cell blockage in prometaphase
* Taxol causes hyperstabilization, forming large asters while blocking cells in mitosis or allowing entry/exit with lower doses
* Roscovitine inhibits CDK1, leading to mitotic spindle disassembly and late mitotic events
* CLASP and KLP10A RNAi affect microtubule dynamics during mitosis.

---

#### Investigating Spindle Microtubule Poleward Flux in Drosophila S2 Cells via FSM

**Spindle Microtubule Dynamics in Drosophila S2 Cells**

**Altering Microtubule Dynamics**:
- Spindle poisons (colchicine, taxol) can be used to alter spindle dynamics in S2 cells
  - Taxol at low doses (nM) allows cells to enter anaphase, while higher doses arrest the cell in metaphase
- MG132 treatment causes microtubules to elongate and become stabilized, reminiscent of cytoskeleton remodeling during anaphase/telophase

**Interfering with Microtubule Stabilizing/Destabilizing Molecules**:
- RNAi knockdown of KLP10A, a kinesin 13 protein, causes microtubules to elongate due to reduced depolymerization activity at the poles
- Perturbation of CLASP leads to new tubulin molecules not being incorporated into kinetochore microtubules, while microtubule depolymerization still occurs at the poles, leading to spindle shortening and collapse

**Fluorescent Speckle Microscopy (FSM)**:
- Different approaches have been used to quantitatively investigate mitotic spindle properties, including:
  - Birefringence analysis using an ultraviolet microbeam
  - Tracking a fiducial mark within a fluorescent-labeled spindle (photo-bleaching or photoactivation)
  - FSM, which uses low levels of fluorescently labeled tubulin to track individual speckles along spindle microtubules
- The use of FSM has allowed for many important discoveries, especially with the help of computational tools for automatic speckle analysis

---

#### High-Resolution Imaging and Laser Microsurgery in Drosophila S2 Cells Investigating Mitosis Mechanisms

**Laser Microsurgery in Mitosis Investigation**

**Background:**
- Important tool for understanding mitosis mechanisms
- Used to investigate roles of discrete structures like spindle assembly checkpoint, centrosomes, and kinetochore microtubules

**Applications:**
1. Kinetochore Microtubule Dynamics:
   - Ablation of K-fibers generates reproducible assay for studying mechanisms of kinetochore microtubule dynamics
2. Centrosome Ablation:
   - Investigating molecular basis of acentrosomal spindle formation
3. Simultaneous Monitoring of Microtubules and Centrosomes:
   - Combining laser microsurgery with powerful live cell imaging tools
4. Chromatid Separation:
   - Studying mechanisms of force production during mitosis

**Advantages:**
- Reveals mechanistic basis for various mitotic phenomena
- Compatible with molecular tools like RNAi
- Useful applications in Drosophila culture cells.

**Setup:**
- Sensitive imaging system required (Nikon 253, Coolsnap HQ2 camera)
- Temperature controlled Perspex case for consistent results at physiological temperature (25C)
- AutoDeblur X2 software used for improving signal-to-noise ratio and eliminating out-of-focus blur.

**Laser Microsurgery Techniques:**
1. Kymograph Analysis:
   - Reveals velocity of speckle movement in mitotic apparatus
2. Centrosome Ablation:
   - Laser ablation of individual centrosomes after spindle formation
3. Chromatid Separation:
   - Inducing premature separations to investigate mechanisms of force production.

**Acknowledgments:**
- Gohta Goshima and Monica Bettencourt-Dias for cell lines and constructs
- Sara Moutinho-Pereira, Irina Matos: Postdoctoral and doctoral fellowships from FCT
- Laboratory work supported by grants from FCT, Gulbenkian Programme, and Human Frontier Science Program.

---

### Chapter 15: Assessment of Mitotic Spindle Phenotypes in Drosophila S2 Cells

**I. Introduction**
- Discussing identification of bona fide mitotic phenotypes associated with RNAi in Drosophila S2 cells
- Importance of proper controls and objective imaging/analysis
- The Drosophila S2 cell line is popular for studying mitosis due to:
  - Similar structure to mammalian spindle
  - Conserved genes involved in spindle formation/function
  - Easy culturing and manipulation
  - Efficient RNA interference (RNAi)
- High-resolution observations through fluorescence microscopy and live cell imaging using tagged mitotic components
- Difficulty: Variability in mitosis even without RNAi, with >2 centrosomes and non-textbook mitosis

**II. Rationale**
- Bona fide mitotic phenotypes should be identified to avoid false positives in RNAi studies
- All deviations from controls are considered phenotypes
- Variability in control population makes drawing conclusions challenging compared to other model organisms

**III. Materials and Methods**

**A. Checking Your S2 Cell Line:**
1. Grasping Your S2 Cell Line:
   - Understanding the characteristics and limitations of your cell line
2. Checking Your Culture Medium:
   - Ensuring proper growth conditions for S2 cells
3. RNAi Toxicity:
   - Identifying off-target effects or toxicity from RNAi

**IV. RNAi and Cell Imaging:**

**A. RNAi with Appropriate Controls:**
1. Properly designing your experiment:
   - Using appropriate controls (e.g., untreated cells, mock transfection, negative control dsRNA)
2. Immunostaining of Microtubules and Mitotic Proteins:
   - Labeling key components of the mitotic spindle for visualization
3. Phenotype Observation and Imaging:
   - Objectively assessing phenotypes using image analysis software

**V. Typical Phenotypes:**
1. Monopolar Spindle:
2. Multipolar Spindle:
3. Anastral Spindle:
4. Monastral Bipolar Spindle:
5. Pole Detachment:
6. Pole Unfocusing:
7. Longer Spindle:
8. Shorter Spindle:
9. Dim Microtubules:
10. Dim g-Tubulin:
11. Chromosome Misalignment:
12. Chromosome Condensation

**VI. How to Avoid Recording False Positives:**
1. Basis of False Positives:
   - Understanding potential sources of false positives in RNAi studies
2. Metaphase Arrest to Reduce Effects of Over-duplicated Centrosomes:
   - Techniques for minimizing the impact of over-duplicated centrosomes on phenotype assessment
3. Rescue Experiment:
   - Reverting phenotypes through rescue experiments with wild-type RNA or proteins
4. Live Cell Imaging:
   - Visualizing mitotic events in real-time to confirm phenotypes

**VII. Summary:**
- Discussing current procedure for identifying bona fide mitotic phenotypes after RNAi in Drosophila S2 cells
- Importance of proper controls and objective imaging/analysis

---

#### Identifying Mitosis in Drosophila S2 Cells Quality Control for RNAi Studies

**Mitosis in Drosophila S2 Cells: Correctly Identifying Mitotic Phenotypes**

**S2 Cell Line**:
- Isolated nearly 40 years ago (Schneider, 1972)
- Over time, cell lines have diverged in aspects like morphology, spreading efficiency, RNAi efficiency, and aging
- **S2-I**: Adheres well to plates but is less tolerant of passages
- **S2-U**: Less adherent to plates but more tolerant of passages
- Description below mostly applies to S2-U cells

**Culture Medium and Serum**:
- Use of inappropriate medium/serum batches can cause difficulties maintaining healthy S2 cells during passaging
- Check cell growth and RNAi efficiency using new medium batches before widespread use
- Store verified batches for long periods (e.g., 1 year)

**RNAi Toxicity**:
- Occasionally, RNAi treatment can lead to complete cell death regardless of target genes
- The combination of dsRNA, medium, and cell lines plays a critical role in this toxicity
- Increasing cell density during RNAi treatment may help reduce cell death

---

#### RNAi and Cell Imaging Protocol and Considerations for Drosophila S2 Cells

**RNAi with Appropriate Controls**

**RNAi Procedures**:
- Treated S2 cells with serum-free medium supplemented with dsRNA for ~1 hour, then added serum
- Performed on a scale of 96-well plates, which are used in the lab due to sufficient mitotic cells and saving on dsRNA
- Larger scales (24-well or 6-well plates) can be used when necessary
- Toxicity effects of RNAi toxicity are less frequent at larger scales

**Importance of Proper Plate Sealing**:
- It is critical to tightly seal the lid of the plate after RNAi treatment to avoid evaporation and concentration changes in the medium
- If not, wells at the edge of the plate have more evaporation than those at the center, leading to cell density and mitotic index alterations

**Control Samples**:
- Every RNAi experiment needs negative controls
- In S2 cells, control RNAi sequences that do not exist in Drosophila have been chosen (e.g., pBluescript or GFP)
- For multiple samples, it is recommended to prepare the control in multiple wells within the same plate for comparison purposes

**Immunostaining of Microtubules and Mitotic Proteins**:
- The protocol is described in [Bettencourt-Dias and Goshima (2009)]
- Use of a multiwell plate enables identical conditions during the entire procedure, especially when using an 8-channel Pipetman

**Transferring Samples for Immunofluorescence Microscopy**:
- Cells are transferred to a 96-well glass-bottom plate after RNAi, using a 12-channel pipette to reduce well-to-well variation
- Use of multiple rows is essential when screening transient mitotic processes, as not many such cells can be found in a single well

**Preparing Cells for Immunostaining**:
- After RNAi treatment, cells are transferred to a multiwell glass-bottom plate for imaging
- Plates are pre-coated with either poly-lysine or Con-A, which enables cell spreading and detection of both poles of the spindle
- However, Con-A inhibits cytokinesis completion and increases multinucleated cells over time
- Cell density affects spreading efficiency; spreading is not robust when too many or too few cells are plated

---

#### Microtubule Staining and Spindle Phenotypes in Drosophila S2 Cells

**Spindle Phenotypes in S2 Cells**

**A. Phenotype Observation and Imaging**:
- Number of cells to observe for spindle phenotype:
  - In large RNAi screen using C. elegans embryos, 5 time-lapse movies of mitosis were sufficient
  - For most genes, more than 5 are necessary in S2 cells (due to ~30% nontextbook spindles)
  - Typically, ~200 spindle images were acquired per RNAi treatment
- Manual inspection can improve the number of cells evaluated and focus on specific phenotypes

**B. Phenotype Classification**:
- 12 major metaphase spindle phenotypes identified through genome-wide RNAi screening (Fig. 4A)
- Multiple phenotypes may be observed in a single spindle, e.g., chromosome misalignment with long spindles
- Centrosome and spindle pole are distinct (Fig. 4B), with gaps often visible in S2 spindles

**C. Typical Phenotypes**:
1. **Monopolar Spindle**: Clustered centrosomes, chromosomes scattered or metaphase-like configuration
   - Observed in control cells (~5%) and can be converted to bipolar types
2. **Multipolar Spindle**: More than two centrosomes, locations random relative to spindle center
   - Caused by failure in centrosome clustering/fusion, involved factors include Ncd and actin-related proteins
3. **Anastral Spindle**: No centrosomes, unique to genes required for centriole duplication or maturation (e.g., Sak, Sas-4, Cnn)

---

#### Mitosis Phenotypes and False Positives in Drosophila S2 Cells

**Mitosis in Drosophila S2 Cells**

**Bipolar Spindles**:
- Occur due to excessive centrosome clustering or failure in centriole duplication
- Commonly seen in S2 cells, less frequently in wild-type flies
- Monopolar spindles can be converted to bipolar spindles, allowing for proper chromosome segregation
- RNAi of centriole duplication genes exhibit this phenotype prior to acentrosomal spindle formation in the next cell cycle

**Centrosome Detachment**:
- Centrosomes detach from the main body of the spindle
- Most obvious after RNAi of dynein dynactin or AspCaM complex
- Also detectable in untreated cells, so quantification is necessary to conclude a mutant phenotype

**Pole Unfocusing**:
- Minus ends of microtubules are unfocused, as seen after Ncd or Asp CaM complex depletion
- Quantitative difference, width of spindle pole should be measured and compared to control spindles

**Longer Spindle**:
- Usually accompanies chromosome misalignment due to disruption of force balance between microtubule sliding and opposing chromatid tension
- Centrosome distance is not always a good marker for spindle length, so measuring pole-to-pole distance is also valuable

**Shorter Spindle**:
- Observed after RNAi of EB1, TOG (Msps), ribosomes, etc.
- Measuring pole-to-pole distance rather than centrosome-to-centrosome distance is more accurate

**Dim Microtubules**:
- Microtubule signals become dim after RNAi of a/b-tubulin or tubulin cofactors
- False positives can be recognized by repeating the experiment

**Dim g-Tubulin**:
- Decreased g-tubulin on centrosomes, spindles, or both
- g-tubulin is important for spindle function and its depletion affects different parts of the microtubule structure in distinct ways

**Chromosome Misalignment**:
- Chromosomes are not congressed to the metaphase plate
- Dramatic misalignment usually accompanies metaphase spindle expansion due to force imbalance
- Difficult to assign in S2 cells, but can be assessed through increased quantification or time-lapse imaging of chromosomes or kinetochores in living cells

**Chromosome Condensation**:
- Chromosome structure defect seen after knockdown of condensin and topoisomerase II

---

#### Mitotic Variation and Experimental Approaches in Drosophila S2 Cells

**S2 Cells and Mitosis in Drosophila**
- **S2 cells**: have mature centrosomes only during mitosis, but centrosome number is highly variable with nearly 50% having more than two at nuclear envelope breakdown
- This results in half of the cells forming multipolar spindles during prometaphase, which then cluster and fuse to form monopolar or monastral bipolar spindles
- **Cell size**: critical determinant of metaphase spindle length; larger cells have longer spindles
- Efficiency of cell spreading alters spindle length measurement
- Alternatively, cells can be fixed and stained on poly-lysine-coated glass to maintain uniform round shape
- Some phenotypes are rarely seen in control population: anastral spindle, dim microtubule or g-tubulin staining (not caused by staining errors)

**Metaphase Arrest**
- Centrosomes cluster and fuse during prometaphase/metaphase in S2 cells
- Most cells arrested in metaphase have two centrosomes due to:
  - RNAi knockdown of APC/C subunits required for anaphase inhibitor destruction
  - Inhibition of proteasome by MG132 treatment
- This increases number of metaphase cells and facilitates detection of mitotic events under the microscope
- Precautions: later mitotic events rarely seen, chromosome alignment often impaired through prolonged arrest

**Rescue Experiment**
- Powerful approach to ensure observed phenotype is derived from targeted RNAi
- Endogenous protein depleted by UTR RNAi while exogenous, RNAi-insensitive protein expressed (tagged with GFP or other epitope)
- Exogenous gene expression not universal across cells, so internal control exists to verify phenotype in GFP-expressing cells
- Rescue experiment useful for quantifying total amount of Klp61F in a cell by measuring GFP intensity after endogenous depletion

**Live Cell Imaging**
- Informative to trace mitotic process through time-lapse microscopy, but requires more sample numbers than yeast or C. elegans
- Manual search for cells of interest followed by targeted analysis; centrosome number variation allows selection of only cells with two centrosomes for phenotype evaluation

