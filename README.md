# IFAC2026
CIF benchmark models used in the IFAC 2026 paper

Compatible with Eclipse ESCET v9.0, downloaded from: https://eclipse.dev/escet/

Specific tooling for automatic clustering and generating all supervisors for MLDES are not yet publicly available.

The folder benchmark_models contains the original models of the production cell and production line.

The folder section3_production_cell contains the resulted MLDES models of the production cell that is used as a running example in Section 3 of the paper. Additionally, all required input is available in the subfolder production_cell, including the most refined group components mapping, DMM, clustered DSMs without bus, with the global bus and local buses, and clustering parameters for the local bus detection. 

The folder section5_production_line contains the MLDES models of the production line that is used as a case study in Section 5 of the paper. Additionally, all required input is available in the subfolder festo, including the most refined group components mapping, DMM, clustered DSMs without bus and with local buses, and clustering parameters for the local bus detection. 

For any questions related to the code please contact: m.baubekova@tue.nl.
