# Model System - NaCl in an Aqueous Solution

In this set of tutorials, we will use MD simulations to study some equilibrium properties of NaCl in an aqueous solution and the association/dissociation of the ions. We will model a system with 1 Na, 1 Cl, and 106 water molecules. The system is obtained from another [PLUMED tutorial](https://www.plumed.org/doc-v2.9/user-doc/html/ves-lugano2017-metad.html).

![Schematic representation of the model system](/nacl-106h2o.dat.tga)

The force fields used in this tutorial are also similar to the ones from PLUMED. The potentials for ion-ion and ion-water interactions were developed by Pettitt and Rossky [[1](https://doi.org/10.1063/1.449894)]. A TIP3P model with parameters corrected for long-range Coulomb interactions [[2](https://doi.org/10.1063/1.1808117)] will be used for water-water interactions.
