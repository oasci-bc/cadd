# 2.2.6 Kinetics

At its core, the binding of a protein ($P$) and ligand ($L$) to form a complex ($PL$) is a dynamic process involving repeated association and dissociation events:

$$
P + L \rightleftharpoons PL
$$

The double arrow ($\rightleftharpoons$) indicates reversibility: the complex $PL$ can dissociate back into free protein $P$ and ligand $L$.
We can define the rate of the forward (binding) reaction as $k_{on}[P][L]$, where $k_{on}$ is the association rate constant (units of $s^{-2}$) and $[P]$ and $[L]$ are the concentrations of free protein and ligand, respectively.
Similarly, the rate of the reverse (dissociation) reaction is $k_{off}[PL]$, with $k_{off}$ being the dissociation rate constant (units of $s^{-1}$) and $[PL]$ the concentration of the protein-ligand complex.

At any point in time, we can write a differential equation expressing the rate of change of $[PL]$ as the difference between its formation and breakdown:

$$
\frac{d[PL]}{dt} = k_{on}[P][L] - k_{off}[PL]
$$

This is an important equation that allows us to model the kinetics of binding.
At equilibrium, the forward and reverse rates become equal ($d[PL]/dt = 0$), giving:

$$
k_{on}[P]_{eq}[L]_{eq} = k_{off}[PL]_{eq}
$$

where the subscript $eq$ denotes equilibrium concentrations.
We can rearrange this to get the dissociation constant $K_d$:

$$
K_d ≡ \frac{k_{off}}{k_{on}} = \left(\frac{[P][L]}{[PL]}\right)_{eq}
$$

This shows the important relationship between the kinetic constants $k_{on}$ and $k_{off}$ and the equilibrium dissociation constant $K_d$.
A higher $k_{on}$ or lower $k_{off}$ will result in a lower $K_d$, indicating tighter binding at equilibrium.
Faster binding or slower unbinding will shift the equilibrium towards the bound complex $PL$.

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

<!-- REFERENCES -->
