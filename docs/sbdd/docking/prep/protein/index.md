# Protein

TODO:

## Conformation

When selecting a protein structure for molecular docking, the choice between an *apo* (unbound) or *holo* (bound) structure is an important consideration.
The conformation of the protein can significantly influence the docking results and the predicted binding modes of the ligands.

Ligand-bound structures usually outperform ligand-free structures, as the geometries of the binding pocket are better defined in the bound state than in the unbound state.
When a ligand is bound to the protein, it induces conformational changes in the binding site, optimizing the pocket for favorable interactions.
These induced-fit effects are captured in the holo structure, providing a more realistic template for docking simulations.
In contrast, apo structures may have a less defined or altered binding pocket geometry, as the absence of a ligand can allow for more flexibility or different conformational states.

If a holo structure is not available, computational tools such as SphGen, SiteMap, fpocket, and FTMap can be used to identify potential ligand binding sites.
These tools employ various algorithms to predict and characterize binding pockets based on the protein's surface properties, such as shape, electrostatic potential, and hydrophobicity.

However, there are situations where apo structures can still be valuable.
For example, if the goal is to identify novel binding sites or explore the protein's conformational flexibility, using an apo structure may be advantageous.
Additionally, if the available holo structures have ligands that are significantly different from the ligands of interest, using an apo structure might be more appropriate to avoid bias towards a specific ligand class.

It is also important to consider the quality and resolution of the protein structure. High-resolution structures (e.g., those determined by X-ray crystallography) are preferred for docking studies, as they provide more accurate atomic coordinates. However, if high-resolution structures are not available, homology models or structures derived from other experimental techniques (e.g., cryo-electron microscopy) can be used, albeit with caution.

## Mutations

## Water molecules

## Buffers

## Cofactors

## Protonation states

<!-- REFERENCES -->

[^bender2021practical]: Bender, B. J., Gahbauer, S., Luttens, A., Lyu, J., Webb, C. M., Stein, R. M., ... & Shoichet, B. K. (2021). A practical guide to large-scale docking. *Nature protocols, 16*(10), 4799-4832. DOI: [10.1038/s41596-021-00597-z](https://doi.org/10.1038/s41596-021-00597-z)
