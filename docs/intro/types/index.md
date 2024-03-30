# Types of CADD

Computer-aided drug design (CADD) is an interdisciplinary field that leverages computational methods to facilitate and accelerate the drug discovery and development process.
CADD techniques can be broadly classified into two main categories: structure-based drug design (SBDD) and ligand-based drug design (LBDD).
These approaches are often used in combination to provide a more comprehensive understanding of drug-target interactions and to guide the design of new drug candidates.

## Structure-Based Drug Design

Structure-based drug design relies on the knowledge of the three-dimensional structure of the target protein or nucleic acid.
The main objective of SBDD is to design compounds that can interact with the target's binding site, typically by forming favorable intermolecular interactions such as hydrogen bonds, van der Waals forces, and electrostatic interactions.

The main techniques used in SBDD include:

-   **Molecular docking** involves predicting the orientation and conformation of a ligand within the target's binding site.
    Docking algorithms evaluate the interactions between the ligand and the target, and rank the ligands based on their predicted binding affinities.
-   **Molecular dynamics simulations** are used to study the dynamic behavior of proteins and protein-ligand complexes.
    These simulations can provide insights into the stability, flexibility, and conformational changes of the target, as well as the binding mode and residence time of the ligand.
-   **Structure-based virtual screening** involves docking large libraries of compounds into the target's binding site to identify potential hit compounds.
    The top-ranked compounds are then selected for experimental validation.
-   **De novo drug design** involves designing novel compounds that are complementary to the target's binding site.
    De novo drug design algorithms generate new molecular structures based on the properties of the binding site, such as its shape, size, and chemical features.

## Ligand-Based Drug Design

Ligand-based drug design is used when the three-dimensional structure of the target is not available, but there is information about known ligands that bind to the target.
LBDD methods rely on the assumption that structurally similar compounds are likely to have similar biological activities.

The main techniques used in LBDD include:

-   **Quantitative structure-activity relationship (QSAR)** models establish a mathematical relationship between the structural features of a set of compounds and their biological activities. These models can be used to predict the activity of new compounds and guide the design of more potent and selective ligands.
-   A pharmacophore is an abstract representation of the essential features of a ligand that are responsible for its biological activity.
    **Pharmacophore models** can be used to identify new compounds that share these features and are likely to have similar activity.
-   **Similarity searching** for compounds in chemical databases that are structurally similar to a known active ligand.
    The underlying assumption is that these similar compounds may also share similar biological activity.

## Integrated Approaches and Emerging Techniques

In practice, SBDD and LBDD approaches are often used in combination to provide a more comprehensive understanding of drug-target interactions.
For example, pharmacophore models derived from LBDD can be used to guide the docking process in SBDD, while the results of molecular docking can be used to refine QSAR models.

In addition to these established techniques, several emerging approaches in CADD are gaining attention:

-   **Artificial intelligence (AI)** and **machine learning (ML)** methods, such as deep learning and neural networks, are being increasingly applied to various aspects of drug discovery, including virtual screening, de novo drug design, and ADMET prediction.
-   **Fragment-based drug design (FBDD)** involves identifying small molecular fragments that bind to the target protein and then linking or growing these fragments to create larger, more potent compounds.
-   **Protein-protein interaction (PPI)** inhibitors play a crucial role in many biological processes and are emerging as attractive targets for drug discovery.
    CADD techniques, such as molecular docking and MD simulations, are being adapted to design small molecules that can disrupt specific PPIs.

In the following chapters, we will delve deeper into each of these CADD techniques, exploring their underlying principles, practical applications, and limitations.
We will also discuss how these methods can be integrated into the drug discovery and development pipeline to accelerate the identification of novel therapeutics.

<!-- REFERENCES -->

[^rudrapal2022computer]: Chapter 2 of Rudrapal, M., & Egbuna, C. (Eds.). (2022). *Computer aided drug design (CADD): From ligand-based methods to structure-based approaches*. Elsevier.
[^stromgaard2017textbook]: Chapters 3 and 4 of Strømgaard, K., Krogsgaard-Larsen, P., Madsen, U. (2017). *Textbook of drug design and discovery*. CRC Press.
