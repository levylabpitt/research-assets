---
marp: true
theme: default
paginate: false
size: 16:9
style: |
  section {
    background: #ffffff;
    font-family: 'Helvetica Neue', Arial, sans-serif;
    padding: 20px 60px 25px 60px;
    display: flex;
    flex-direction: column;
  }
  h3 {
    color: #1a1a2e;
    font-size: 1.5em;
    font-weight: bold;
    font-style: italic;
    margin: 1.5em 0 0.4em 0;
    flex-shrink: 0;
  }
  .columns {
    display: flex;
    gap: 40px;
    flex-grow: 1;
    align-items: center;
  }
  .column-left {
    flex: 1.2;
  }
  .column-right {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .column-right img {
    width: 100%;
    border-radius: 4px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  p {
    font-size: 0.58em;
    line-height: 1.4;
    color: #333;
    text-align: justify;
    margin: 0;
  }
  .references {
    font-size: 0.40em;
    line-height: 1.5;
    color: #555;
    margin-top: 0.4em;
  }
  .references a {
    color: #1a5fb4;
    text-decoration: none;
  }
---

### Correlated Nanoelectronics and the Second Quantum Revolution

<div class="columns">
<div class="column-left">

Strongly correlated electronic materials and quantum transport of nanoelectronic systems are areas of research that have traditionally followed non-intersecting paths. With the development of complex-oxide heterostructures and nanostructures, a nascent field of Correlated Nanoelectronics has emerged. The Levylab research program makes extensive use of nanoscale reconfigurability of a complex-oxide heterostructure formed from a thin layer of LaAlO₃ grown on SrTiO₃. Like an Etch-a-Sketch toy, the LaAlO₃/SrTiO₃ interface can be drawn (and erased) with 2 nm resolution to create a remarkable range of quantum devices. These nanoscale devices can be "aimed" back at the materials themselves to provide insight into their inner workings. This platform has already produced two novel phases of electronic matter: one in which electrons form bound pairs without becoming superconducting, and a family of one-dimensional degenerate quantum liquids formed from n-tuples of bound electrons. A rich and growing palette of quantum building blocks are currently being explored for applications in quantum computing, quantum simulation, and quantum sensing, major goals of the Second Quantum Revolution.

<div class="references">

1. Levy, J., 2022. APL Materials 10, 110901. [doi:10.1063/5.0111221](https://doi.org/10.1063/5.0111221)
2. Cheng et al., Nat. Nanotechnol. 6, 343 (2011). [doi:10.1038/nnano.2011.56](https://doi.org/10.1038/nnano.2011.56)
3. Annadi et al., Nano Lett. 18, 4473 (2018). [doi:10.1021/acs.nanolett.8b01614](https://doi.org/10.1021/acs.nanolett.8b01614)
4. Briggeman et al., Sci. Adv. 6, eaba6337 (2020). [doi:10.1126/sciadv.aba6337](https://doi.org/10.1126/sciadv.aba6337)
5. Briggeman et al., Science 367, 769 (2020). [doi:10.1126/science.aat6467](https://doi.org/10.1126/science.aat6467)

</div>

</div>
<div class="column-right">

![Correlated Nanoelectronics](https://raw.githubusercontent.com/levylabpitt/research-assets/main/Correlated_Nanoelectronics.png)

</div>
</div>

---

### Extreme Nanoscale Control

<div class="columns">
<div class="column-left">

We can locally and reversibly control the metal-insulator transition of complex-oxide heterostructures using two techniques: conductive atomic force microscope (c-AFM) lithography and ultra-low-voltage electron beam lithography (ULV-EBL). Beginning with an insulating interface, a positive voltage applied to the c-AFM tip (or electron beam dose) can switch the interface to metallic. Conducting regions can be made with wires or dots having widths as small as 3 nm. Combining these elementary components using c-AFM or ULV-EBL enables us to create various nanostructures such as single-electron transistors (SETs), broadband THz emitters, and ballistic electron waveguides. A negatively-biased AFM probe can be used to engineer energy barriers in the conducting regions or can be used to erase the entire device altogether without affecting the reusability of the heterostructure.

<div class="references">

1. Cen et al., Nat. Mater. 7, 298–302 (2008). [doi:10.1038/nmat2136](https://doi.org/10.1038/nmat2136)
2. Cen et al., Science 323, 1026–1030 (2009). [doi:10.1126/science.1168294](https://doi.org/10.1126/science.1168294)
3. Levy et al., J. Vis. Exp. 89, e51886 (2014). [doi:10.3791/51886](https://doi.org/10.3791/51886)

</div>

</div>
<div class="column-right">

![Extreme Nanoscale Control](https://raw.githubusercontent.com/levylabpitt/research-assets/main/Extreme_Nanoscale_Control.png)

</div>
</div>

---

### Analog Quantum Simulation

<div class="columns">
<div class="column-left">

In the LevyLab, we exploit our ability to control, at the extreme nanoscale, the heterostructure LaAlO₃/SrTiO₃ (LAO/STO), and, because it demonstrates nearly all properties found in the solid state, we use it as a platform to perform analog quantum simulations. LAO/STO is programmed using a conductive atomic force microscopy (c-AFM) lithography technique in which the interfacial conductivity can be programmed with a precision of 2 nm, comparable to the mean separation between electrons. We have been able to engineer spin-orbit interaction in the LAO/STO by perturbing the path of a ballistic electron waveguide (1D) using a positively-biased c-AFM tip placed in contact with the LaAlO₃ surface, locally switching the interface to a conducting state. By doing so, we may have complemented the engineered properties of LAO/STO for it to be used as a building block for simulation of various complex 1D quantum systems. Additionally, motivated to develop novel quantum devices to learn about quantum materials, and vice versa, we have created Kronig–Penney-like 1D superlattice structures by spatially modulating the potential of a 1D electron waveguide using c-AFM lithography. The systems created here focus on low-dimensional confined structures, which are challenging to create using other methods. Consequently, we have opened new frontiers in the development of quantum matter.

<div class="references">

1. Yang et al., Appl. Phys. Lett. 117, 253103 (2020). [doi:10.1063/5.0027480](https://doi.org/10.1063/5.0027480)
2. Briggeman et al., Nat. Phys. 17, 782 (2021). [doi:10.1038/s41567-021-01217-z](https://doi.org/10.1038/s41567-021-01217-z)
3. Briggeman et al., Sci. Adv. 6, eaba6337 (2020). [doi:10.1126/sciadv.aba6337](https://doi.org/10.1126/sciadv.aba6337)

</div>

</div>
<div class="column-right">

![Analog Quantum Simulation](https://raw.githubusercontent.com/levylabpitt/research-assets/main/Analog_Quantum_Simulation.png)

</div>
</div>

---

### Nanoscale Ultrafast Spectroscopy

<div class="columns">
<div class="column-left">

LaAlO₃/SrTiO₃ (LAO/STO) nanojunctions enable a new type of molecular-scale spectroscopy which combines the high temporal resolution of ultrafast optical sources with electronic structures which can be programmed with extreme nanoscale precision. Our unique optical platform can harness the intrinsically large third-order nonlinear susceptibility of STO by converting it to a local second-order susceptibility at a nanoscale junction. This nanoscale nonlinearity can be used to generate broadband THz emission at 10 nm scales, and has been demonstrated to produce strong optical extinction features in graphene and graphene nanoribbons. This system is capable of interrogating a wide range of materials by placing them on the LAO/STO canvas, and "writing" a nanoscale junction centered around a single molecule.

<div class="references">

1. Irvin et al., Nat. Photonics 4, 849–852 (2010). [doi:10.1038/nphoton.2010.238](https://doi.org/10.1038/nphoton.2010.238)
2. Ma et al., Nano Lett. 13, 2884–2888 (2013). [doi:10.1021/nl401219v](https://doi.org/10.1021/nl401219v)
3. Chen et al., Light Sci. Appl. 8, 24 (2019). [doi:10.1038/s41377-019-0135-0](https://doi.org/10.1038/s41377-019-0135-0)
4. Jnawali et al., Appl. Phys. Lett. 106, 211101 (2015). [doi:10.1063/1.4921750](https://doi.org/10.1063/1.4921750)
5. Sheridan et al., Nano Lett. 20, 6966–6973 (2020). [doi:10.1021/acs.nanolett.0c01379](https://doi.org/10.1021/acs.nanolett.0c01379)

</div>

</div>
<div class="column-right">

![Nanoscale Ultrafast Spectroscopy](https://raw.githubusercontent.com/levylabpitt/research-assets/main/Nanoscale_Ultrafast_Spectroscopy.png)

</div>
</div>

---

### A New Superconducting Semiconductor

<div class="columns">
<div class="column-left">

Many of the properties of SrTiO₃ (STO), including superconductivity, are still mysterious more than a half-century after its discovery. One can gain new insights into superconducting semiconductors like STO by comparing it with a close relative, KTaO₃ (KTO). The recent discovery of superconductivity at KTO interfaces and surfaces offers the possibility of "stereoscopic" insight into superconductivity, and the possible role of incipient ferroelectricity, strong spin-orbit coupling, and structural phase transitions in mediating pairing interactions. Why do KTO(111) and KTO(110) heterostructures exhibit superconductivity while KTO(100) does not? Is KTO superconductivity associated with a near-surface structural phase transition? Does KTO exhibit signatures of electron pairing outside the superconducting regime? What is the role of spin-orbit coupling? The mesoscopic transport techniques developed for STO-based heterostructures provide a clear roadmap for experiments with KTO-based heterostructures.

<div class="references">

1. Kim et al., arXiv:2308.13180 (2023). [doi:10.48550/arXiv.2308.13180](https://doi.org/10.48550/arXiv.2308.13180)
2. Yu et al., Nano Lett. 22, 6062–6068 (2022). [doi:10.1021/acs.nanolett.2c00673](https://doi.org/10.1021/acs.nanolett.2c00673)

</div>

</div>
<div class="column-right">

![A New Superconducting Semiconductor](https://raw.githubusercontent.com/levylabpitt/research-assets/main/A_New_Superconducting_SemiConductor.png)

</div>
</div>

---

### Engineering New Qubits with Graphene Nanoribbons

<div class="columns">
<div class="column-left">

Graphene nanoribbons (GNRs) are a promising new material that may find use in future quantum computing applications. Derived from graphene lattices, these one-dimensional materials can be designed atom-by-atom using synthetic chemistry approaches. Our research program aims to address the question: can GNRs host a new type of spin qubit? These systems provide high isotopic purity and intrinsic spin-orbit coupling, similar to silicon-based spin qubits. When combined with the unique electrical gating and sensing capabilities from materials such as LaAlO₃/SrTiO₃ nanostructures, graphene, and silicon host materials.

<div class="references">

1. Sheridan et al., APL Materials 9, 071101 (2021). [doi:10.1063/5.0048795](https://doi.org/10.1063/5.0048795)
2. Li et al., Appl. Phys. Lett. 114, 123103 (2019). [doi:10.1063/1.5080251](https://doi.org/10.1063/1.5080251)
3. Jnawali et al., Adv. Mater. 29, 1603488 (2017). [doi:10.1002/adma.201603488](https://doi.org/10.1002/adma.201603488)

</div>

</div>
<div class="column-right">

![Engineering New Qubits](https://raw.githubusercontent.com/levylabpitt/research-assets/main/Engineering_New_Qubits.png)

</div>
</div>
