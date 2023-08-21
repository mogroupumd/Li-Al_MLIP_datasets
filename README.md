# Li-Al_MLIP_datasets
Training, validation, and testing datasets for the publication "Assessing the accuracy of MLIPs in predicting the elemental ordering: a case study on Li-Al alloys"

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
