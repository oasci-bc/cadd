# 1.1 History

!!! danger "DRAFT"

    This page is a work in progress and is subject to change at any moment.

## Inception of Computational Techniques

### Quantum chemistry

- The application of quantum mechanics to theoretical chemistry in the late 1950s and 1960s, as discussed by Mulliken and Roothaan (1959), highlighted the potential of quantum mechanics for understanding molecular structures and interactions. This marked a critical advancement in the computational approach to drug discovery [(Mulliken & Roothaan, 1959)](https://consensus.app/papers/broken-bottlenecks-future-molecular-quantum-mechanics-mulliken/6faa09c069785dea9b1834c69ad90c40/).

"The calculation of small molecular interactions by the differences of separate total energies. Some procedures with reduced errors" by S. F. Boys and F. Bernardi (1970): This paper presents a new method for computing molecular interactions, focusing on reducing errors in interaction energy calculations. This advancement was crucial for accurately predicting molecular behaviors and interactions in various chemical and biological processes Boys & Bernardi, 1970.

### Molecular simulations

"Equation of state calculations by fast computing machines" by N. Metropolis, A. W. Rosenbluth, M. Rosenbluth, A. H. Teller (1953): This early work described a general method for investigating the properties of substances consisting of interacting molecules, using a modified Monte Carlo integration over configuration space. The method was suitable for fast computing machines of the time, marking a significant step towards modern computational chemistry Metropolis et al., 1953.

"Studies in Molecular Dynamics. I. General Method" by B. Alder and T. Wainwright (1959): This paper outlines a method for calculating the behavior of several hundred interacting classical particles, marking an early step towards the field of molecular dynamics. This technique allowed for the exact computational study of many-body problems, contributing significantly to the understanding of molecular interactions Alder & Wainwright, 1959.

"Liquid Structure and Self‐Diffusion" (1966) by A. Rahman:
This paper used the method of molecular dynamics to study the structure of a liquid and its relation to the process of self-diffusion, introducing a precise geometrical procedure to separate particles around a given particle into shells of primary, secondary, etc., neighbors (Rahman, 1966).

"Molecular Dynamics Studies of the Microscopic Properties of Dense Fluids" (1969) by P. L. Fehder:
This paper reported molecular dynamics calculations on a two-dimensional system of Lennard-Jones disks, providing equilibrium thermodynamics data for various temperature-density states and examining the presence of large vacancies in the spatial distribution of particles in the system (Fehder, 1969).

### Visualization

- The early 1970s saw the development of versatile and interactive graphics display systems for molecular modeling, as exemplified by the work of Feldman et al. (1973). These systems facilitated the study of macromolecules, marking a significant step forward in the field of CADD [(Feldman et al., 1973)](https://consensus.app/papers/versatile-interactive-graphics-display-system-molecular-feldman/5b66e19d5f815e0f8a69266ffa191847/).
- The late 1970s introduced systems like AIMS (Ames Interactive Molecular modeling System), which utilized 3-D dynamic computer display systems for constructing molecular models and were instrumental in the study of molecular interactions and conformational changes [(Coeckelenbergh et al., 1978)](https://consensus.app/papers/computer-display-manipulation-molecules-coeckelenbergh/eff956e80c165658a7b79540924b8be7/).

## Rise of Structure-Based Drug Design

- **Biophysical Applications of MD**: Berendsen's work emphasized the application of MD simulations to complex molecular systems, highlighting its capabilities in predicting the free energy of binding between inhibitors and enzymes. This was instrumental in the application of simulation methods in drug design, demonstrating the potential of MD to contribute significantly to the field [(Berendsen, 1987)](https://consensus.app/papers/biophysical-applications-moleculardynamics-berendsen/5e026c3040cc5e6a90c444a9b25a8fb6/).

- **Chemical and Biomolecular Systems Simulations**: Beveridge and Jorgensen's work addressed the simulation of chemical and biomolecular systems, encompassing areas such as free energy simulations and the study of DNA reactions. Their contributions provided a comprehensive overview of the application of computer simulations in understanding biomolecular systems [(Beveridge & Jorgensen, 1987)](https://consensus.app/papers/computer-simulation-chemical-biomolecular-systems-beveridge/7b9f40885da15b9c9efeae42a52f3af4/).

- **Molecular Dynamics of Proteins**: Karplus and colleagues' pioneering efforts in simulating the dynamics of proteins laid the groundwork for the application of MD in studying biomolecules. Their simulations of the bovine pancreatic trypsin inhibitor marked the beginning of molecular dynamics studies of biological macromolecules, setting the stage for future research in protein dynamics and function [(Karplus et al., 1987)](https://consensus.app/papers/dynamics-applications-proteins-karplus/773f99c889315e68819f456a0dd69799/).

- **Constant Pressure and Temperature Simulations**: Andersen's development of methods to perform MD simulations under conditions of constant temperature and/or pressure expanded the scope of MD simulations. This allowed for more realistic simulations of biological processes, facilitating the study of biomolecules under varied environmental conditions [(Andersen, 1980)](https://consensus.app/papers/dynamics-simulations-pressure-andor-temperature-andersen/0acc65b76cb55424a366a2f07e9d446e/).

- **Computer-aided Molecular Design**: The application of MD simulations in computer-aided molecular design was significantly advanced by Richards, who demonstrated the potential of combining computer graphics techniques with theoretical calculations. This approach was crucial for suggesting molecules with desired specific properties, aiding in the synthetic and chemical manipulation of therapeutic drugs [(Richards, 1985)](https://consensus.app/papers/computeraided-design-richards/8f5ab9804c44520eb86ecf8acf17f761/).

- Further developments in the 1970s, including more accurate molecular dynamics simulations, exemplified by Stillinger and Rahman's work on liquid water, underscored the increasing sophistication of computational models in studying molecular properties and interactions [(Stillinger & Rahman, 1974)](https://consensus.app/papers/improved-simulation-liquid-water-dynamics-stillinger/6c9dc9cd440c519a8942da6cba8445f4/).

- **Advances in X-ray Crystallography**: The use of high-flux X-ray and neutron solution scattering became instrumental for structural studies of proteins, offering a complement to crystallographic investigations with low-resolution structural methods. This period marked an increase in the quantitative measurements of macromolecular structures and dynamics [(Perkins, 1988)](https://consensus.app/papers/studies-proteins-xray-neutron-solution-scattering-perkins/ecca07f54a835859810e880abf25b198/).

- **Biomolecular Dynamics and Crystallography**: Workshops and collaborative efforts underscored the emerging picture of biomolecular dynamics, supported by crystallographic data. This led to a better understanding of enzyme catalysis, nucleic acid functions, and membrane transport, revealing the time dimension in biomolecular interactions [(Edholm et al., 1984)](https://consensus.app/papers/biomolecular-dynamics-report-workshop-gysinge-sweden-edholm/eb3c29200f7e5872b426e05cc47c8f49/).

- **Refinement Techniques and Structural Determination**: The development of molecular dynamics for the refinement of macromolecular structures demonstrated the feasibility of achieving high-resolution data, critical for understanding biotin-avidin interactions and other complex biomolecular mechanisms [(Hendrickson et al., 1989)](https://consensus.app/papers/structure-core-streptavidin-determined-multiwavelength-hendricksont/ec441ec1479f5c6f99e3582e6a9cd686/).

- **Emergence of Biological Crystallogenesis**: The concept of purity and methodological principles in biological crystallogenesis gained attention, emphasizing the need for a more rational approach to the crystallization of biomacromolecules and their complexes. This was pivotal for the growth of crystals for structural analysis [(Giegé & Mikol, 1989)](https://consensus.app/papers/crystallogenesis-proteins-giegé/353051e804da502c924ba5a5895fe090/).

- **The Protein Data Bank (PDB)**: The establishment of the PDB as a computer-based archival file for macromolecular structures marked a significant milestone, facilitating the storage and public distribution of atomic coordinates and structural data for a wide array of biomolecules [(Bernstein et al., 1977)](https://consensus.app/papers/protein-data-bank-computerbased-file-macromolecular-bernstein/71dcad94e74a539c9f29b2b272179fb8/).

- **Fast Energy Estimation and Visualization of Protein-Ligand Interaction**: A new computational and graphical method was developed to aid ligand-protein docking studies, capable of estimating non-bonded and electrostatic interaction energy in real-time during interactive docking operations. This method also allowed for the visualization of the local environment inside the binding pocket, significantly aiding the drug design process [(Tomioka, Itai, & Iitaka, 1987)](https://consensus.app/papers/method-fast-energy-estimation-visualization-tomioka/75e1397020b150a9a4495c097faef311/).

- **Docking Software Development**: The late 1980s saw the implementation of docking software packages such as TOM, integrated into FRODO, for studying protein-ligand interactions with interactive energy-minimization procedures. This allowed for the creation of models of protein-ligand complexes, followed by energy minimization treating both ligand and receptor parts as flexible units [(Cambillau & Horjales, 1988)](https://consensus.app/papers/frodo-subpackage-proteinligand-fitting-energy-cambillau/8e3ad63f17825eb5b26fbae658ad8d20/).

- **Brownian Dynamics Simulation of Protein Association**: The application of Brownian Dynamics (BD) to study the diffusive dynamics and interaction of proteins marked an important advancement in understanding protein-protein and protein-ligand interactions. This method assessed the influence of individual charged amino acid residues on the docking process, facilitating the study of electrostatic charge distribution in protein docking [(Northrup, Luton, Boles, & Reynolds, 1988)](https://consensus.app/papers/dynamics-simulation-protein-association-northrup/b549f3b708d1522b865e235cbc689560/).

## Evolution of Ligand-Based Drug Design

- The 1980s and 1990s: Expansion of LBDD approaches, including quantitative structure-activity relationship (QSAR) models and pharmacophore modeling.
- Case studies illustrating the success of LBDD in identifying novel drug candidates.

## Integration of Virtual Screening and High-Throughput Screening (HTS)

- The 1990s to early 2000s: The synergy between computational virtual screening and experimental HTS.
- How CADD increased the efficiency of HTS by narrowing down potential candidates for testing.

## Advances in Molecular Dynamics Simulations

- Early 2000s: The role of molecular dynamics (MD) simulations in understanding the dynamic nature of biomolecular interactions.
- Application of MD simulations in predicting drug resistance and optimizing lead compounds.

## The Era of Big Data and Machine Learning

- The 2010s onwards: Incorporation of big data analytics and machine learning algorithms into CADD.
- Examples of how machine learning has been used to predict drug-likeness, bioactivity, and ADMET properties.

## Current Trends and Future Directions

- The growing importance of AI and deep learning in drug discovery, including generative models for novel molecule design.
- The integration of CADD with emerging biotechnologies and the potential for personalized medicine.

## Further Reading

- A list of seminal papers, books, and reviews for readers interested in a deeper dive into the history and methodology of CADD.

<!-- REFERENCES -->
