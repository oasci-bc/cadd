# Point charges

These forces arise from the presence of point charges within molecules; for example, ions or partial atomic charges.
The interaction between point charges is described by Coulomb's law, which forms the basis for understanding electrostatic forces in molecular systems.
Coulomb's law states that the electrostatic force between two point charges ($q_1$ and $q_2$) is directly proportional to the product of their charges and inversely proportional to the square of the distance between them, $r_{12}$.

$$
F_{el} = \frac{q_1 q_2}{4 \pi \varepsilon_0 r_{12}^2}
$$

The electrostatic potential energy ($U_{el}$) is given by:

$$
U_{el} = \frac{q_1 q_2}{4 \pi \varepsilon r_{12}}
$$

where $\varepsilon$ is the dielectric constant of the medium.

## What is a dielectric constant?

In this context, the dielectric constant ($\varepsilon$) is a measure of a material's ability to reduce the strength of an electric field.
In a vacuum, the dielectric constant is equal to 1, while in other media, such as solvents, it is greater than 1.
The higher the dielectric constant, the more the medium screens or attenuates the electrostatic interactions between charged particles.
When considering electrostatic interactions in molecular simulations, the surrounding environment, such as solvent molecules, can significantly impact the strength of these interactions.

### In a vacuum

Imagine two charged particles, let's say two ions, in a vacuum.
The electrostatic force between them is given by Coulomb's law, and it depends on their charges and the distance between them.
In a vacuum, there is nothing to interfere with this interaction, so the force is relatively strong and long-ranged.

### In water

Things are a little different when we consider other media like water.

When an ion is placed in water, the water molecules nearby will reorient themselves due to the ion's electric field.
The water molecules are polar, with the oxygen atom having a partial negative charge and the hydrogen atoms having a partial positive charge.
If the ion is positively charged (a cation), the oxygen atoms of the water molecules will be attracted to it, pointing their negative ends towards the ion.
If the ion is negatively charged (an anion), the hydrogen atoms of the water molecules will be attracted to it, pointing their positive ends towards the ion.

This arrangement of water molecules around the ion creates a hydration shell or solvation shell.
The oriented water molecules in this shell generate their own electric field that opposes the electric field of the ion.
In other words, the water molecules' dipoles align in a way that partially cancels out the ion's electric field.

Now, let's consider two ions in water.
Each ion will have its own hydration shell, with water molecules oriented around it. When the two ions come close to each other, their hydration shells will start to overlap.
The water molecules in the overlapping region will be influenced by both ions' electric fields, and their orientation will be a compromise between the two.

This overlapping of hydration shells effectively reduces the direct electrostatic interaction between the two ions.
The water molecules in the overlapping region act as a barrier, preventing the ions from feeling the full strength of each other's electric fields.
The more water molecules that can fit between the ions (i.e., the greater the distance between the ions), the more effective this screening becomes.

In essence, the water molecules in the hydration shells act as tiny dipoles that can rearrange themselves to counteract the ions' electric fields.
This rearrangement of water molecules reduces the strength of the electrostatic interaction between the ions, effectively "screening" or "shielding" the interaction.

It's important to note that this screening effect is not perfect – the ions can still interact with each other through the water molecules, but the interaction is much weaker than it would be in a vacuum.
The extent of screening depends on the polarity of the solvent (i.e., its dielectric constant) and the distance between the ions.

## Partial atomic charges

In molecules, the distribution of electrons creates regions of positive and negative charge, which can be represented by partial charges assigned to each atom.
These partial charges can be determined using quantum mechanical calculations or by fitting to the molecular electrostatic potential (ESP).
The ESP is typically sampled at a large number of points around the molecule, and the partial charges are assigned by minimizing the difference between the calculated and fitted potentials.

<!-- REFERENCES -->

[^jensen2017introduction]: Chapter 2 of Jensen, F. (2017). *Introduction to computational chemistry*. John wiley & sons.
[^cooksy2014quantum]: Chapter 10 of Cooksy, A. (2014). *Physical Chemistry: Quantum chemistry and molecular interactions*. Pearson.
