# 2.2.1 Thermodynamics

Protein-ligand binding is a fundamental process that underlies virtually all biological processes, from enzyme catalysis and signal transduction to the action of drugs.
A deep understanding of the thermodynamics that govern the recognition and association of proteins with their ligands is therefore critical for fields such as biochemistry, cell biology, and especially drug discovery.
In this chapter, we will delve into the energetic basis of molecular recognition, exploring the kinetics and thermodynamic forces that drive binding equilibria.
We will learn how to quantify binding through parameters like the dissociation constant ($K_d$) and binding free energy ($\Delta G$), and see how these relate to kinetic constants like on- and off-rates.

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

A negative $\Delta G_{bind}$ implies that the binding process is spontaneous and favored, as the products (the bound complex) have a lower free energy than the reactants (the unbound molecules).
The more negative the $\Delta G_{bind}$ value, the greater the driving force for binding, and thus the higher the binding affinity between the two molecules.
A very negative $\Delta G_{bind}$ corresponds to a very tight or high-affinity binding interaction.
Conversely, a positive $\Delta G_{bind}$ would indicate that the binding is non-spontaneous and unfavorable from a thermodynamic standpoint (although it may still occur under certain kinetic conditions).

### Partitioning

While $\Delta G_{bind}$ provides a overall thermodynamic picture, it is often useful to partition this free energy change into its constituent enthalphic ($\Delta H$) and entropic ($-T \Delta S$) components:

$$
\Delta G_{bind} = \Delta H_{bind} - T\Delta S_{bind}
$$

This partitioning can provide deeper insights into the forces driving or opposing the binding interaction.

### Enthalpic contributions

The enthalphic term ($\Delta H_{bind}$) accounts for energetic factors like hydrogen bonding, van der Waals interactions, and desolvation effects that stabilize the bound complex.
Only a brief overview is provided here; we will go into more detail later.

#### Hydrogen bonding

Hydrogen bonds are formed when a hydrogen atom bonded to an electronegative atom (such as oxygen or nitrogen) interacts with another electronegative atom.
In protein-ligand binding, hydrogen bonds can form between suitable donor and acceptor groups on the ligand and the protein.
The strength of a hydrogen bond typically ranges from 2 to 10 kcal/mol, making it one of the strongest non-covalent interactions.
The formation of hydrogen bonds between the ligand and the protein can significantly stabilize the complex and contribute favorably to the binding enthalpy.
The number, strength, and geometry of hydrogen bonds can vary depending on the specific ligand and protein involved.

#### van der Waals interactions

Van der Waals interactions are weak, short-range attractive forces that arise from transient dipoles induced by fluctuations in the electron clouds of atoms.
These interactions include London dispersion forces and dipole-induced dipole interactions.
Although the strength of individual van der Waals interactions is small (typically less than 1 kcal/mol), the cumulative effect of many such interactions can be significant in protein-ligand binding.
The shape complementarity between the ligand and the protein's binding site can maximize these interactions, leading to a favorable contribution to the binding enthalpy.

#### Electrostatic interactions

Electrostatic interactions involve the attraction or repulsion between charged or partially charged atoms.
In proteins, charged amino acid side chains (such as lysine, arginine, aspartate, and glutamate) can interact with charged or polar groups on the ligand.
These interactions can include salt bridges (between oppositely charged groups), charge-dipole, and dipole-dipole interactions.
The strength of electrostatic interactions depends on the distance between the interacting atoms and the dielectric constant of the medium.
In an aqueous environment, the dielectric constant is high, which can attenuate the strength of electrostatic interactions.
However, in the hydrophobic core of a protein, the dielectric constant is lower, making electrostatic interactions more significant.
The formation of favorable electrostatic interactions can contribute to the binding enthalpy.

#### Desolvation

Desolvation refers to the process of removing water molecules from the binding interface of the protein and the ligand.
Water molecules form hydrogen bonds with polar and charged groups on the protein and the ligand.
When a ligand binds to a protein, some of these water molecules are displaced, breaking the hydrogen bonds.
Breaking hydrogen bonds is an enthalpically unfavorable process, as it requires energy.
The magnitude of the desolvation penalty depends on the number and strength of the hydrogen bonds that are broken.
However, the release of water molecules into the bulk solvent can also lead to a favorable entropic contribution, as the water molecules gain translational and rotational freedom.

#### Conformational changes

Protein-ligand binding can induce conformational changes in the protein, the ligand, or both.
These conformational changes can involve the breaking or forming of intramolecular interactions, such as hydrogen bonds, van der Waals interactions, or electrostatic interactions.
The breaking of intramolecular interactions is enthalpically unfavorable, while the formation of new interactions is favorable.
The net enthalpic contribution of conformational changes depends on the balance between the broken and formed interactions.
Additionally, conformational changes can also lead to entropic effects, as the system may lose or gain conformational flexibility.

#### π-π stacking

π-π stacking interactions occur between aromatic rings, such as those found in phenylalanine, tyrosine, and tryptophan side chains in proteins, and aromatic groups in ligands.
These interactions arise from the attraction between the delocalized π electrons of the aromatic rings.
The strength of π-π stacking interactions depends on the distance and relative orientation of the rings, with the most favorable orientation being a parallel displaced or T-shaped arrangement.
The formation of π-π stacking interactions can contribute favorably to the binding enthalpy, with a typical strength of 1-2 kcal/mol per interaction.

#### Metal coordination

Some proteins contain metal ions, such as zinc, calcium, or magnesium, in their binding sites.
Ligands with suitable donor atoms (e.g., oxygen, nitrogen, or sulfur) can coordinate with these metal ions, forming metal-ligand bonds.
The strength of metal-ligand bonds depends on the nature of the metal ion and the ligand donor atom, but they can be quite strong (10-30 kcal/mol).
The formation of metal-ligand bonds can contribute significantly to the binding enthalpy, as well as provide specificity and orientational constraints to the ligand binding.

### Entropic contributions

The entropic term ($-T\Delta S_{bind}$) captures the opposing effect of reducing configurational freedom upon binding.

#### Conformational entropy

Conformational entropy refers to the number of accessible conformational states of the protein and the ligand.
Upon binding, both the protein and the ligand may lose conformational flexibility, leading to a decrease in conformational entropy.
This loss of entropy is unfavorable and opposes binding.
However, in some cases, binding may stabilize a particular conformation of the protein or the ligand, reducing the entropic penalty.
The magnitude of the conformational entropic change depends on the flexibility of the protein and the ligand, as well as the specific conformational constraints imposed by binding.

#### Desolvation entropy

As mentioned earlier, the desolvation of the binding interface involves the displacement of water molecules from the protein and the ligand surfaces.
While the breaking of water-protein and water-ligand hydrogen bonds is enthalpically unfavorable, the release of these water molecules into the bulk solvent leads to a favorable entropic contribution.
The released water molecules gain translational and rotational freedom, increasing the overall entropy of the system.
The magnitude of the desolvation entropic gain depends on the number of water molecules released and their degree of ordering in the bound state.

#### Translational and rotational entropy

Upon binding, the protein and the ligand lose translational and rotational degrees of freedom, as they become constrained in the bound complex.
This loss of translational and rotational entropy opposes binding and is often the most significant entropic penalty.
The magnitude of this entropic cost depends on the size and shape of the ligand and the protein binding site.
Larger and more flexible ligands tend to have a higher entropic penalty upon binding.

#### Solvent entropy

In addition to the desolvation of the binding interface, protein-ligand binding can also affect the entropy of the surrounding solvent.
If the ligand is hydrophobic, its binding to a hydrophobic pocket in the protein can lead to the release of ordered water molecules from the pocket, resulting in a favorable entropic contribution.
On the other hand, if the ligand is charged or polar, its binding may disrupt the local water structure, leading to an unfavorable entropic effect.

#### Vibrational entropy

Vibrational entropy arises from the vibrational modes of the protein and the ligand.
Upon binding, the vibrational modes of the protein and the ligand may be altered, leading to changes in vibrational entropy.
However, the contribution of vibrational entropy to the overall binding entropy is usually small compared to the other factors.

<!-- REFERENCES -->

[^stromgaard2017textbook]: Chapter 2 of Strømgaard, K., Krogsgaard-Larsen, P., Madsen, U. (2017). *Textbook of drug design and discovery*. CRC Press.
[^anslyn2006modern]: Chapters 4 of Anslyn, E. V., & Dougherty, D. A. (2006). *Modern physical organic chemistry*. University science books.
[^zuckerman2010statistical]: Chapter 9 of Zuckerman, D. M. (2010). *Statistical physics of biomolecules: An introduction*. CRC press.
[^gilson1997statistical]: Gilson, M. K., Given, J. A., Bush, B. L., & McCammon, J. A. (1997). The statistical-thermodynamic basis for computation of binding affinities: a critical review. *Biophysical journal, 72*(3), 1047-1069.
