# 2.2.5 Kinetics

At its core, the binding of a protein ($P$) and ligand ($L$) to form a complex ($PL$) is a dynamic process involving repeated association and dissociation events:

$$
P + L \rightleftharpoons PL
$$

The double arrow ($\rightleftharpoons$) indicates reversibility: the complex $PL$ can dissociate back into free protein $P$ and ligand $L$.

## Rates of reactions

Reaction rates are the speed at which a chemical&mdash;or binding&mdash;reaction proceeds; in other words, the rate of "conversion" or "binding".
This conversion must be a function of concentration, because the frequency of collisions between reactant molecules, which is necessary for a reaction to occur, depends on the concentrations of the reactants.
This can be understood through the collision theory of chemical reactions.

According to collision theory, for a reaction to happen, the reactant molecules must:

-   Collide with each other;
-   Have sufficient energy to overcome the activation energy barrier;
-   Have the proper orientation during the collision.

The concentration of reactants directly affects the first factor, the frequency of collisions.
Here's why:

-   Imagine a fixed volume containing reactant molecules. As the concentration of reactants increases, more molecules are present in the same volume.
-   With more molecules in the same space, the average distance between them decreases, making collisions more likely.
-   A higher frequency of collisions means that there are more opportunities for reactant molecules to collide with sufficient energy and proper orientation, thus increasing the reaction rate.

Mathematically, the relationship between concentration and collision frequency can be derived using the kinetic theory of gases.
The collision frequency ($Z$) between two types of molecules ($A$ and $B$) is proportional to the product of their concentrations:

$$
Z \; \propto \; [A][B]
$$

We can define the rate of the forward (binding) reaction as $k_{on}[P][L]$, where $k_{on}$ is the association rate constant (units of $s^{-2}$) and $[P]$ and $[L]$ are the concentrations of free protein and ligand, respectively.
Similarly, the rate of the reverse (dissociation) reaction is $k_{off}[PL]$, with $k_{off}$ being the dissociation rate constant (units of $s^{-1}$) and $[PL]$ the concentration of the protein-ligand complex.

## Equilibrium constants

In binding reactions, there are two main types of equilibrium constants: the association constant ($K_a$) and the dissociation constant ($K_d$).
These constants provide information about the strength and reversibility of the binding interaction between a protein ($P$) and a ligand ($L$).
In both cases, we can we can write a differential equation expressing the rate of change of $[PL]$ as the difference between its formation and breakdown at any point in time.

$$
\frac{d[PL]}{dt} = k_{on}[P][L] - k_{off}[PL]
$$

This is an important equation that allows us to model the kinetics of binding.

If $[PL]$ is changing (i.e., nonzero), this means that our system is not in equilibrium; thus, the forward and reverse conversions become equal giving $d[PL]/dt = 0$.
We can then rearrange our expression and get the following.

$$
k_{on}[P]_{eq}[L]_{eq} = k_{off}[PL]_{eq}
$$

where the subscript $eq$ denotes equilibrium concentrations.

### Dissociation

A dissociation constant ($K_d$) is a type of equilibrium constant that measures the tendency of a complex to separate into its constituent components.
This process is reversible, meaning that the components can also recombine to form the complex.
For our protein-ligand complex, $K_d$ is the ratio to our dissociation ($k_{off}$) to our association ($k_{on}$) rates.
We can rearrange our expression above to solve for $k_{off} / k_{on}$.

$$
K_d ≡ \frac{k_{off}}{k_{on}} = \frac{[P][L]}{[PL]} \Bigg\vert_{eq}
$$

!!! note

    This expression is only valid when we have one-to-one binding.
    Meaning one ligand binds to one protein.
    If we had any other stoichiometry such as two ligands binding to one protein, our expression would be invalid.

This shows the important relationship between the kinetic constants $k_{on}$ and $k_{off}$ and the equilibrium dissociation constant $K_d$.
A higher $k_{on}$ or lower $k_{off}$ will result in a lower $K_d$, indicating tighter binding at equilibrium.
Faster binding or slower unbinding will shift the equilibrium towards the bound complex $PL$.

A lower Kd value indicates a stronger binding affinity, as it means that a lower concentration of ligand is needed to achieve 50% occupancy of the protein binding sites.

Use $K_d$ when you want to:

-   Compare the binding affinities of different ligands for a given protein;
-   Determine the concentration of ligand needed to achieve a desired level of protein binding;
-   Estimate the fraction of protein bound to ligand at a given ligand concentration.

The dissociation constant $K_d$, as derived above, is a key parameter characterizing binding affinity at equilibrium.
It has units of concentration (typically M, mM, μM, nM, etc.), and corresponds to the concentration of free ligand at which half the protein is bound.
To see this, consider that the fraction of protein bound ($f_{bound}$) is given by:  

$$
f_{bound} = \frac{[PL]}{[P] + [PL]} = \frac{[L]}{K_d + [L]}
$$

Setting $f_{bound} = 0.5$ and solving for $[L]$ gives $[L]_{50} = K_d$.
Thus, a lower $K_d$ implies that less free ligand is needed to achieve 50% binding, indicating a higher affinity interaction.

Measuring $K_d$ experimentally is a key goal in characterizing protein-ligand interactions.
One common approach is to perform a titration experiment, measuring some signal that reports on the fraction of protein bound (e.g. fluorescence, radioactivity, etc.) as a function of increasing $[L]$.
Fitting the resulting binding curve to the equation above yields $K_d$.
More sophisticated methods like isothermal titration calorimetry (ITC) can provide $K_d$ as well as enthalpy and entropy of binding from a single experiment by measuring heat evolved.
Finally, $K_d$ can also be obtained from separate measurements of $k_{on}$ and $k_{off}$ using techniques like surface plasmon resonance (SPR).

### Association

The association constant ($K_a$) is the reciprocal of the dissociation constant and is defined as:

$$
K_a = \frac{1}{K_d} = \frac{[PL]}{[P][L]} \Bigg\vert_{eq}
$$

$K_a$ has units of inverse concentration (typically M<sup>-1</sup>) and represents the tendency of the protein and ligand to form the protein-ligand complex.
A higher Ka value indicates a stronger binding affinity.

Use $K_a$ when you want to:

-   Express the binding affinity in terms of complex formation rather than dissociation;
-   Compare the binding affinities of different protein-ligand pairs;
-   Calculate the Gibbs free energy change ($\Delta G$) of the binding reaction using the relationship $\Delta G = -R T \ln(K_a)$.

<!-- REFERENCES -->
