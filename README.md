# Li-Al_MLIP_datasets
Eight datasets (including two training datasets, two validation datasets, and four testing datasets) for the publication "Assessing the accuracy of MLIPs in predicting the elemental ordering: a case study on Li-Al alloys"

# Data architecture
Each directory contains:
1.  The compressed structural data (in VASP POSCAR format with .zip file, i.e., poscars.zip)
2.  The corresponding energies and forces data  (Data.json)

Data.json architecture:  
|  
|-- Forces (DFT K4)  
|  
|-- Energies (DFT K4)  
|  
|-- Labels: necessary information to categorize each configuration  
|  
|-- Index: [index].POSCAR.vasp  

# Citation
If you use the datasets extensively, you may want to cite the following publication:  
Y. Liu, Y. Mo, Assessing the accuracy of machine learning interatomic potentials in predicting the elemental orderings: A case study of Li-Al alloys, Acta Mater. 268 (2024) 119742.  
https://doi.org/10.1016/j.actamat.2024.119742.
