# B. Universal gas constant

The universal gas constant ($R$) emerges as a fundamental constant that relates the microscopic properties of a system (e.g., the motion and interactions of individual particles) to its macroscopic thermodynamic properties (e.g., temperature, pressure, and energy).

The universal gas constant is defined as the product of the Boltzmann constant ($k_B$) and the Avogadro constant ($N_A$):

$$
R = k_B × N_A
$$

where:

-   $k_B$ is the Boltzmann constant [^nist-kb], which relates the average kinetic energy of particles to the absolute temperature.
    Its value is $1.380649 \times 10^{-23}$ J/K.
-   $N_A$ is the Avogadro constant [^nist-na], which represents the number of particles (atoms or molecules) in one mole of a substance. Its value is $6.02214076 \times 10^{23}$ mol<sup>-1</sup>.

Thus, the value of $R$ is 8.31446261815324 J K <sup>-1</sup> mol<sup>-1</sup>.

The Boltzmann constant ($k_B$) is a fundamental constant in statistical mechanics, as it provides a link between the microscopic energy states of a system and its temperature.
It appears in the Boltzmann distribution, which describes the probability distribution of energy states in a system at thermal equilibrium:

$$
P(E) = \frac{1}{Z} \exp \left( - \frac{E}{k_B T} \right)
$$

where:

-   $P(E)$ is the probability of a system being in a state with energy $E$;
-   $Z$ is the partition function, which is a sum over all possible energy states;
-   $T$ is the absolute temperature in Kelvin.

The universal gas constant ($R$) inherits its fundamental role in statistical mechanics from the Boltzmann constant.
It appears in the ideal gas law, which can be derived using statistical mechanics principles:

$$
PV = nRT
$$

where:

-   $P$ is the pressure of the gas;
-   $V$ is the volume of the gas;
-   $n$ is the number of moles of the gas;
-   $T$ is the absolute temperature.

In the context of the free energy of binding, the universal gas constant plays a crucial role in connecting the microscopic details of ligand-protein interactions to the macroscopic thermodynamic description.
The equilibrium constant ($K_{eq}$) of a binding reaction can be related to the partition functions of the free and bound states of the ligand and protein, which in turn depend on the microscopic energy states accessible to the system.

The relationship between the Gibbs free energy of binding ($\Delta G$) and the equilibrium constant ($K_{eq}$) arises from the statistical mechanics treatment of the system, where the universal gas constant ($R$) acts as a scaling factor that relates the microscopic energy states to the macroscopic thermodynamic quantities.

<!-- REFERENCES -->

[^nist-kb]: https://physics.nist.gov/cgi-bin/cuu/Value?k
[^nist-na]: https://physics.nist.gov/cgi-bin/cuu/Value?na
