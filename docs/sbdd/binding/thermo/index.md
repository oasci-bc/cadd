# 2.2.1 Thermodynamics

Protein-ligand binding is a fundamental process that underlies virtually all biological processes, from enzyme catalysis and signal transduction to the action of drugs.
Therefore, a deep understanding of the thermodynamics that governs the recognition and association of proteins with their ligands is critical for fields such as biochemistry, cell biology, and especially drug discovery.

## Binding free energy

The affinity of a protein-ligand interaction is ultimately determined by the change in free energy upon binding, denoted as $\Delta G_{bind}$.
This is the key thermodynamic quantity that dictates the equilibrium populations of free and bound species.
For the general noncovalent binding reaction $P + L \rightleftharpoons PL$, we can write:

$$
\Delta G_{bind} = - R T \ln \left( K_{eq} \right)
$$

where $R$ is the [universal gas constant](../../../appendices/r/), $T$ is the absolute temperature in Kelvin, and $K_{eq}$ is the equilibrium constant.

??? note "Derivation"

    See the literature for a derivation of this expression [^gilson1997statistical].

A negative $\Delta G_{bind}$ implies that the binding process is spontaneous and favored, as the products (the bound complex) have lower free energy than the reactants (the unbound molecules).
The more negative the $\Delta G_{bind}$ value, the greater the driving force for binding, and thus the higher the binding affinity between the two molecules.
A very negative $\Delta G_{bind}$ corresponds to a tight or high-affinity binding interaction.
Conversely, a positive $\Delta G_{bind}$ would indicate that the binding is non-spontaneous and unfavorable from a thermodynamic standpoint (although it may still occur under certain kinetic conditions).

## Energy partitioning

While $\Delta G_{bind}$ provides an overall thermodynamic picture, it is often valuable for partition this free energy change into its constituent enthalpic ($\Delta H$) and entropic ($-T \Delta S$) components:

$$
\Delta G_{bind} = \Delta H_{bind} - T\Delta S_{bind}
$$

This partitioning can provide deeper insights into the forces driving or opposing the binding interaction.

## Enthalpic contributions

The enthalpic term ($\Delta H_{bind}$) accounts for energetic factors like hydrogen bonding, van der Waals interactions, and desolvation effects that stabilize the bound complex.
Only a brief overview is provided here; we will go into more detail later.

### Hydrogen bonding

Hydrogen bonds are formed when a hydrogen atom bonded to an electronegative atom (such as oxygen or nitrogen) interacts with another electronegative atom.
In protein-ligand binding, hydrogen bonds can form between suitable donor and acceptor groups on the ligand and the protein.
The strength of a hydrogen bond typically ranges from 2 to 10 kcal/mol, making it one of the strongest non-covalent interactions.
The formation of hydrogen bonds between the ligand and the protein can significantly stabilize the complex and contribute favorably to the binding enthalpy.
The number, strength, and geometry of hydrogen bonds can vary depending on the specific ligand and protein involved.

### van der Waals interactions

Van der Waals interactions are weak, short-range attractive forces that arise from transient dipoles induced by fluctuations in the electron clouds of atoms.
These interactions include London dispersion forces and dipole-induced dipole interactions.
Although the strength of individual van der Waals interactions is small (typically less than 1 kcal/mol), the cumulative effect of many such interactions can be significant in protein-ligand binding.
The shape complementarity between the ligand and the protein's binding site can maximize these interactions, making a favorable contribution to the binding enthalpy.

### Electrostatic interactions

Electrostatic interactions involve the attraction or repulsion between charged or partially charged atoms.
In proteins, charged amino acid side chains (such as lysine, arginine, aspartate, and glutamate) can interact with charged or polar groups on the ligand.
These interactions can include salt bridges (between oppositely charged groups), charge-dipole, and dipole-dipole interactions.
The strength of electrostatic interactions depends on the distance between the interacting atoms and the medium's dielectric constant.
In an aqueous environment, the dielectric constant is high, which can attenuate the strength of electrostatic interactions.
However, in a protein's hydrophobic core, the dielectric constant is lower, making electrostatic interactions more significant.
The formation of favorable electrostatic interactions can contribute to the binding enthalpy.

### Desolvation

Desolvation refers to removing water molecules from the binding interface of the protein and the ligand.
Water molecules form hydrogen bonds with polar and charged groups on the protein and the ligand.
When a ligand binds to a protein, some water molecules are displaced, breaking the hydrogen bonds.
Breaking hydrogen bonds is an enthalpically unfavorable process, as it requires energy.
The magnitude of the desolvation penalty depends on the number and strength of the broken hydrogen bonds.
However, releasing water molecules into the bulk solvent can also lead to a favorable entropic contribution, as the water molecules gain translational and rotational freedom.

### Conformational changes

Protein-ligand binding can induce conformational changes in the protein, the ligand, or both.
These conformational changes can involve breaking or forming intramolecular interactions, such as hydrogen bonds, van der Waals, or electrostatic interactions.
The breaking of intramolecular interactions is enthalpically unfavorable, while the formation of new interactions is favorable.
The net enthalpic contribution of conformational changes depends on the balance between the broken and formed interactions.
Conformational changes can also lead to entropic effects, as the system may lose or gain conformational flexibility.

### π-π stacking

In proteins and aromatic groups in ligands, π-π stacking interactions occur between aromatic rings, such as those found in phenylalanine, tyrosine, and tryptophan side chains.
These interactions arise from the attraction between the delocalized π electrons of the aromatic rings.
The strength ofπ-π stacking interactions depends on the distance and relative orientation of the rings, with a parallel displaced or T-shaped arrangement being the most favorable orientation.
The formation of π-π stacking interactions can contribute favorably to the binding enthalpy, with a typical strength of 1-2 kcal/mol per interaction.

### Metal coordination

Some proteins, such as zinc, calcium, or magnesium, contain metal ions in their binding sites.
Ligands with suitable donor atoms (e.g., oxygen, nitrogen, or sulfur) can coordinate with these metal ions, forming metal-ligand bonds.
The strength of metal-ligand bonds depends on the nature of the metal ion and the ligand donor atom, but they can be quite strong (10-30 kcal/mol).
The formation of metal-ligand bonds can significantly contribute to the binding enthalpy and provide specificity and orientational constraints on ligand binding.

## Entropic contributions

The entropic term ($-T\Delta S_{bind}$) captures the opposing effect of reducing configurational freedom upon binding.

### Conformational entropy

Conformational entropy refers to the number of accessible conformational states of the protein and the ligand.
Upon binding, the protein and the ligand may lose conformational flexibility, leading to a decrease in conformational entropy.
This loss of entropy is unfavorable and opposes binding.
However, in some cases, binding may stabilize a particular protein or ligand conformation, reducing the entropic penalty.
The magnitude of the conformational entropic change depends on the flexibility of the protein and the ligand, as well as the specific conformational constraints imposed by binding.

### Desolvation entropy

As mentioned earlier, the desolvation of the binding interface involves the displacement of water molecules from the protein and the ligand surfaces.
While breaking water-protein and water-ligand hydrogen bonds is enthalpically unfavorable, releasing these water molecules into the bulk solvent leads to a favorable entropic contribution.
The released water molecules gain translational and rotational freedom, increasing the system's overall entropy.
The magnitude of the desolvation entropic gain depends on the number of water molecules released and their degree of order in the bound state.

### Translational and rotational entropy

Upon binding, the protein and the ligand lose translational and rotational degrees of freedom as they become constrained in the bound complex.
This translational and rotational entropy loss opposes binding and is often the most significant entropic penalty.
The magnitude of this entropic cost depends on the ligand's size and shape and the protein binding site.
Larger and more flexible ligands tend to have a higher entropic penalty upon binding.

### Solvent entropy

In addition to desolvating the binding interface, protein-ligand binding can also affect the entropy of the surrounding solvent.
If the ligand is hydrophobic, binding to a hydrophobic pocket in the protein can release ordered water molecules from the pocket, resulting in a favorable entropic contribution.
On the other hand, if the ligand is charged or polar, its binding may disrupt the local water structure, leading to an unfavorable entropic effect.

### Vibrational entropy

Vibrational entropy arises from the vibrational modes of the protein and the ligand.
Upon binding, the vibrational modes of the protein and the ligand may be altered, leading to changes in vibrational entropy.
However, the contribution of vibrational entropy to the overall binding entropy is usually tiny compared to the other factors.

## Conclusions

After discussing the thermodynamic basis of protein-ligand binding, including the key contributions to the binding free energy, enthalpy, and entropy, a natural next step is to consider how we can calculate or estimate these energetic quantities.
While experimental techniques can measure overall binding affinities, computational methods are invaluable for dissecting binding thermodynamics in atomic detail.

One of the most widely used computational approaches is molecular mechanics.
Molecular mechanics methods use classical physics to model the potential energy of a molecular system as a function of its conformation.
The potential energy is calculated using a force field, essentially a set of parameterized equations and atom types that approximate the quantum mechanical energy surface.

With a molecular mechanics force field, one can calculate the enthalpic contributions to binding, such as van der Waals interactions, hydrogen bonding, electrostatics, and so on, based on the molecules' 3D structures.
Conformational entropy can also be estimated by sampling an ensemble of low-energy conformations.
Molecular mechanics is thus a powerful tool for understanding the driving forces of molecular recognition.
Its simplicity makes it indispensable for computationally intensive tasks like molecular dynamics simulations and docking.
More broadly, it lays the foundation for various computational approaches in computer-aided drug design.

<!-- REFERENCES -->

[^stromgaard2017textbook]: Chapter 2 of Strømgaard, K., Krogsgaard-Larsen, P., Madsen, U. (2017). *Textbook of drug design and discovery*. CRC Press.
[^anslyn2006modern]: Chapters 4 of Anslyn, E. V., & Dougherty, D. A. (2006). *Modern physical organic chemistry*. University science books.
[^zuckerman2010statistical]: Chapter 9 of Zuckerman, D. M. (2010). *Statistical physics of biomolecules: An introduction*. CRC press.
[^gilson1997statistical]: Gilson, M. K., Given, J. A., Bush, B. L., & McCammon, J. A. (1997). The statistical-thermodynamic basis for computation of binding affinities: a critical review. *Biophysical journal, 72*(3), 1047-1069.
