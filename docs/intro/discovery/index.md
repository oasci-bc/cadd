# Drug discovery

Drug discovery is critical in the drug development pipeline, laying the foundation for creating safe and effective medicines.
This phase involves identifying potential drug candidates that can interact with specific biological targets associated with a disease or condition.
The drug discovery process has evolved significantly over the years, with the integration of computational methods playing a crucial role in streamlining and accelerating the identification of promising lead compounds.

## Definition and importance

Drug discovery identifies and validates new drug candidates to potentially treat or prevent a specific disease or condition.
This phase is the first step in the drug development pipeline and is followed by preclinical studies, clinical trials, and regulatory approval.
The success of the entire drug development process heavily relies on the efficiency and effectiveness of the drug discovery phase.

The main objectives of drug discovery are to:

-   Identify and validate biological targets associated with a disease or condition
-   Discover compounds that can interact with these targets to produce the desired therapeutic effect
-   Optimize the properties of these compounds to enhance their efficacy, safety, and drug-like characteristics

## Traditional drug discovery

Traditional drug discovery approaches have been the foundation of the pharmaceutical industry for decades.
These methods have led to the development of numerous life-saving medications and have significantly improved human health.
However, traditional drug discovery is often a time-consuming, expensive, and challenging process with a high attrition rate.
Each approach has unique advantages and challenges, and understanding them is crucial for appreciating the evolution and current state of drug discovery.

### Serendipitous discovery

Serendipitous discovery, also known as accidental discovery, is a process by which a drug or a potential therapeutic effect is discovered by chance, often while researching something else entirely.
Some of the most well-known drugs, such as penicillin, aspirin, and sildenafil, were discovered serendipitously.
While serendipitous discoveries have led to significant breakthroughs in medicine, they are, by nature, unpredictable and not a systematic approach to drug discovery.
Nevertheless, some methodologies and practices can help foster an environment conducive to serendipitous discoveries:

-   Serendipitous discoveries often arise from a researcher's keen observation of unexpected results or phenomena.
    Curiosity and a willingness to investigate these observations further can lead to identifying novel therapeutic effects.
-   Many serendipitous discoveries have emerged from observing unexpected side effects of existing drugs.
    Investigating these side effects can lead to identifying new therapeutic applications for the drug.
-   Natural products, such as plants, fungi, and marine organisms, have been a rich source of serendipitous drug discoveries.
    Screening these products for biological activity can lead to identifying novel compounds with therapeutic potential.
-   Serendipitous discoveries often arise from the cross-pollination of ideas and expertise from different scientific disciplines.
    Collaborative research and open communication between researchers from various fields can increase the chances of stumbling upon unexpected findings.

While serendipitous discoveries have played a significant role in drug discovery, relying solely on chance is not a sustainable or efficient approach. Modern drug discovery efforts typically involve rational design, high-throughput screening, and other systematic methodologies, with serendipity playing a less prominent role. Nevertheless, fostering an environment that encourages curiosity, collaboration, and exploration can help increase the chances of serendipitous breakthroughs while pursuing more structured approaches to drug discovery.

### Phenotypic screening

Phenotypic screening is a drug discovery approach that involves testing compounds in cell-based or animal models to identify those that produce a desired change in the phenotype (observable characteristics) of the disease model without necessarily knowing the specific molecular target of the compound.
This approach has the advantage of identifying compounds that modulate disease-relevant pathways and can potentially lead to the discovery of novel drug targets. Here are some common methodologies used in phenotypic screening:

-   Pathway-specific reporter assays use genetically engineered cell lines that express a reporter gene (e.g., luciferase or fluorescent protein) under the control of a promoter that is responsive to the activity of a specific signaling pathway.
    Compounds that modulate the pathway will alter the expression of the reporter gene, providing a measurable readout.
Phenotypic profiling involves treating cells with compounds and measuring changes in a wide range of cellular phenotypes using techniques such as gene expression analysis, proteomics, or metabolomics. By comparing the phenotypic profiles of compounds to those of known drugs or genetic perturbations, researchers can gain insights into the compounds' mechanism of action and identify potential drug targets.
-   Organoids are three-dimensional, self-organized structures derived from stem cells that recapitulate key features of the organ they represent. Organoid-based screening allows for the testing of compounds in a more physiologically relevant context than traditional 2D cell culture.
-   Spheroids are multicellular aggregates that can be generated from tumor cells or other cell types. Spheroid-based screening can be used to identify compounds that inhibit tumor growth, invasion, or other cancer-related phenotypes.
-   In vivo screening involves testing compounds in animal models of disease to identify those that produce a desired phenotypic change, such as a reduction in tumor growth, improvement in motor function, or increased survival. In vivo screening provides a more complex and physiologically relevant environment for testing compounds but is also more time-consuming and expensive than in vitro assays.
-   Zebrafish have emerged as a powerful model organism for phenotypic screening due to their small size, rapid development, and transparency, which allows for easy visualization of internal organs. Zebrafish can be used to model a wide range of human diseases and can be screened in high-throughput formats to identify compounds that alter disease-related phenotypes.

Phenotypic screening has several advantages over target-based screening, including the ability to identify compounds that act through novel mechanisms and the potential to discover new drug targets.
However, phenotypic screening also has limitations, such as the difficulty in determining the specific molecular target of hit compounds and the potential for identifying compounds that produce the desired phenotype through off-target or non-specific effects.

In practice, phenotypic screening is often used with target-based screening and other drug discovery approaches to maximize the chances of identifying new and effective therapies.
The choice of screening strategy depends on factors such as the available disease models, the stage of the drug discovery process, and the project's specific goals.

### Target-based screening

Target-based screening assays are designed to identify compounds that interact with a specific molecular target, such as a protein or enzyme, that is known to play a role in a particular disease.
Several methodologies are used in target-based screening assays, each with advantages and limitations.

-   Enzyme inhibition assays measure compounds' ability to inhibit a target enzyme's activity.
    Compounds are incubated with the enzyme and a substrate, and the enzyme's activity is measured using colorimetric, fluorometric, or radioactive readouts.
-   Binding assays assess the direct interaction between a compound and the target protein.
    Standard techniques include fluorescence polarization, surface plasmon resonance (SPR), and isothermal titration calorimetry (ITC).
-   Reporter gene assays use genetically engineered cells that express a reporter gene (e.g., luciferase or green fluorescent protein) under the control of a promoter responsive to the target protein's activity.
    Compounds that modulate the target's activity will alter the expression of the reporter gene, providing a measurable readout.
-   High-content screening (HCS) combines automated microscopy with image analysis software to measure multiple cellular parameters simultaneously.
    This approach can provide information on a compound's effect on cell morphology, protein localization, and other cellular processes related to the target's function.
-   Nuclear magnetic resonance (NMR) spectroscopy can probe the interaction between a compound and a target protein by measuring changes in the protein's chemical shift upon ligand binding.
    This approach can provide information on the binding site and affinity of the compound.
-   X-ray crystallography involves co-crystallizing the target protein with a bound ligand and determining the structure of the complex using X-ray diffraction.
    This approach can provide detailed information on the binding mode of the compound and guide structure-based drug design efforts.

In practice, target-based screening often involves a combination of these methodologies, with hits identified from one assay being validated and further characterized using additional techniques.
The choice of assay depends on factors such as the nature of the target, the available resources, and the stage of the drug discovery process.

It's important to note that while target-based screening has successfully identified new drugs, it also has limitations.
For example, compounds that show promising activity in a target-based assay may have a different effect in more complex biological systems, such as cells or animals.
Additionally, focusing on a single target may miss compounds that act through novel mechanisms or may not account for the complex interplay between targets in a disease setting.

## Role of computer-aided drug design

Despite the successes of traditional drug discovery approaches, the process remains challenging, with high attrition rates and long timelines.
The development of a new drug can take more than a decade and cost billions of dollars, and many compounds fail at various stages of the discovery and development process.
The pharmaceutical industry has increasingly turned to innovative approaches, such as computer-aided drug design (CADD).
CADD techniques offer the potential to streamline the drug discovery process, reduce costs, and increase the likelihood of success by integrating computational methods with traditional approaches.
CADD techniques can be broadly categorized into structure-based drug design (SBDD) and ligand-based drug design (LBDD), depending on the availability of structural information about the target or known ligands.

The main advantages of CADD in drug discovery include:

-   CADD can rapidly screen vast libraries of compounds and prioritize the most promising candidates for experimental validation, reducing the time and cost associated with traditional screening methods.
-   Computational methods can provide valuable insights into the molecular mechanisms underlying drug-target interactions, guiding the optimization of lead compounds.
-   CADD enables the rational design of compounds with desired properties, such as enhanced potency, selectivity, and drug-like characteristics.

## Overview

The drug discovery phase can be divided into three main stages: target identification, lead identification, and lead optimization.

-   Target identification involves identifying and validating biological targets (e.g., proteins, enzymes, receptors, or genes) that play a critical role in the disease or condition of interest.
    Computational methods, such as bioinformatics and systems biology, can aid in the identification and prioritization of potential targets.
-   Once a target has been found, lead identification is used to discover compounds that can interact with the target to produce the desired therapeutic effect.
    This stage involves screening large libraries of compounds using high-throughput screening (HTS) or virtual screening methods to identify hits that show promising activity against the target.
-   The lead optimization stage focuses on improving the properties of the identified hits to enhance their efficacy, selectivity, and drug-like characteristics.
    This stage involves iterative cycles of chemical modification, biological testing, and computational modeling to guide the optimization process.
    The ultimate goal is to select one or more optimized lead compounds that can progress to preclinical studies.

In the following sections, we will delve deeper into each stage, exploring the computational methods and strategies employed in modern drug discovery.

<!-- REFERENCES -->

[^kumar2022drug]: Chapter 4 of Kumar, T. D. A. (2022). *Drug design: A conceptual overview*. CRC Press. DOI: [10.1201/9781003298755](https://doi.org/10.1201/9781003298755)
[^rudrapal2022computer]: Chapter 1 of Rudrapal, M., & Egbuna, C. (Eds.). (2022). *Computer aided drug design (CADD): From ligand-based methods to structure-based approaches*. Elsevier.
[^stromgaard2017textbook]: Chapter 1 of Strømgaard, K., Krogsgaard-Larsen, P., Madsen, U. (2017). *Textbook of drug design and discovery*. CRC Press.
