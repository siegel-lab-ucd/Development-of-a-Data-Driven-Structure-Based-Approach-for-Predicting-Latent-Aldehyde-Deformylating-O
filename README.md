# Additional supplemental files for the paper "Discovery, Design, and Structural Characterization of Alkane Producing Enzymes across the Ferritin-like Superfamily"

The contents of each folders are as follows:

### Supplementary data 4:

This folder contains all sample files necessary to perform a Rosetta docking run performed in this work, as well as the scripts and code for building the machine learning model. 

"WT_1.pdb" is a representative ferritin-like protein with an octanal intermediate placed next to the di-iron binding site.

"X00.conf.pdb"	is the conformers library for the octanal ligand.

"X00.fullvirt.enzdes.cst"	describes the constraints used in the docking run.

"X00.params" contains the molecular parameters of the di-iron ligand

"Y00.params" contains the molecular parameters of the octanal ligand

"design_off.xml"	contains the rosetta-script instructions for the docking run

"options"	includes additional flags for the docking run.

"submit.sh" contains the submission command to perform the docking run.

### Supplementary data 6:

The folder "Full_ligand_models" includes the top 25 models (sorted by total system energy) of each protein with octanal ligand docked.

The folder "Di-iron-only-models	" includes the top 25 models (sorted by total system energy) of each protein with only the di-iron center docked.

### Supplemental methods for machine learning analysis:

This folder contains the code for generating the results and figures related to the machine learning section in this paper.

