
# 🧪 Research Direction: DFT-Based Grain Boundary (GB) Corrosion

Grain boundaries are high-energy, defect-rich regions that act as preferential sites for corrosion due to atomic-level disorder. This project leverages Density Functional Theory (DFT) to map the electronic and chemical reactivity of these interfaces.



---

## 🏗️ The Structure-Property-Reactivity Workflow

To model corrosion at the atomistic scale, we follow this systematic approach:

1.  **Construct GB Models:** Build bicrystal supercells (e.g., $\Sigma 3$ or $\Sigma 5$ tilt boundaries) using periodic boundary conditions to mimic the interfacial structure.
2.  **Quantify GB Energy ($\gamma_{GB}$):** Calculate the excess energy of the boundary compared to the bulk to assess the inherent defect density.
3.  **Segregation Analysis:** Model the interaction of corrosive impurities (O, Cl, S, H) with the GB.
    * **Segregation Energy ($E_{seg}$):** Defined as $E_{seg} = E_{GB+impurity} - E_{GB+bulk}$. A negative value indicates spontaneous segregation.
4.  **Electronic Reactivity:** Analyze the **Work Function** and **Density of States (DOS)**. A lower local work function typically identifies anodic sites prone to oxidation.
5.  **Reaction Modeling:** Utilize Nudged Elastic Band (NEB) methods to calculate energy barriers for reactions like water dissociation ($H_2O \to OH^- + H^+$).

---

## 💡 Potential Research Avenues

### 1. Impurity-Induced Embrittlement
* **Objective:** Investigate how non-metallic impurities (C, P, S) compete with Hydrogen (H) for segregation sites.
* **DFT Application:** Calculate the reduction in cleavage energy across the GB to determine if these impurities exacerbate stress corrosion cracking.



### 2. Alloying Elements & Passivation Stability
* **Objective:** Model how Cr or other solutes affect the stability of passive oxide layers at the GB.
* **DFT Application:** Compare the adsorption energy of oxygen on "pure" vs. "doped" GB interfaces to predict film stability.

### 3. Corrosive Ion Diffusion Barriers
* **Objective:** Map the migration pathways of ions (e.g., $Cl^-$) through high-angle boundaries.
* **DFT Application:** Use NEB to identify "fast-diffusion channels" to inform grain-orientation engineering strategies.

---

## 🛠 Practical Implementation Checklist

- [ ] **System Selection:** Start with a simple $\Sigma 5$ tilt boundary in a transition metal (e.g., Ni or Cr).
- [ ] **Convergence:** Rigorously converge `KPOINTS` and `ENCUT` for the bicrystal supercell.
- [ ] **Visualization:** Use **VESTA** to inspect atomic coordination and distortion at the interface.
- [ ] **Validation:** Compare calculated segregation energies with experimental Atom Probe Tomography (APT) data.

---

*“Everything is theoretically impossible, until it is done.”*
