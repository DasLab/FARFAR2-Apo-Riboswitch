# FARFAR2-Apo-Riboswitch
Models of apo riboswitches generated by FARFAR2

# How is this repository organized?
We've provided one directory per positive control apo state riboswitch we simulated. Each simulation's subdirectory contains a pymol session (the exact session used for figure rendering) and a number of PDB files. These PDB files include all the cluster centers from the FARFAR2 clustering protocol, as well as up to 50 additional members of each cluster center. The cluster centers are numbered c.1.1.pdb through c.10.1.pdb, while the best-energy cluster's associated models are numbered c.1.1.pdb to c.1.50.pdb (if all 50 models are present).

We include pocket predictions from fpocket for the model sets here in the pocket_predictions folder. The pockets are represented in each PDB file by clusters of atoms with residue name STP and the residue number identifies the pocket to which these atoms belong.

# How can I use this repository?
However you want! Of course, our most urgent hope is that these models will be useful to calibrate drug design protocols with clear positive controls so that the models we also deposited for [SARS-CoV-2](https://github.com/DasLab/FARFAR2-SARS-CoV-2) will be maximally useful.
