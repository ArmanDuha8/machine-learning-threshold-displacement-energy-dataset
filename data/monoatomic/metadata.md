# Dataset Metadata: Threshold Displacement Energy Data

## General Information
- **Title**: Threshold Displacement Energy Dataset with Material Properties
- **Filename**: monoatomic_avg_Ed.csv
- **Version**: 1.0.0
- **License**: CC BY 4.0
- **Authors**: Rosty B. Martinez Duque, Arman Duha, Mario F. Borunda
- **Description**: 
  This dataset contains threshold displacement energy (Ed) values averaged over different literature sources (raw data with separate literature values are in the file "Monoatomic.csv") for various monoatomic materials, along with fundamental physical and chemical properties such as atomic number, cohesive energy, density, melting temperature, etc.

## Data Description
- **File Format**: CSV
- **Number of Entries**: 33 rows (materials)
- **Number of Features**: 17 columns (properties)

### **Variables Included**
| Column Name           | Description                                        | Units        |
|-----------------------|----------------------------------------------------|--------------|
| `material_name`       | Name of the material                               | String       |
| `Ed (eV)`             | Average threshold displacement energy              | eV           |
| `Z`                   | Atomic number                                      | Integer      |
| `m (u)`               | Atomic mass                                        | Atomic mass  |
| `r (pm)`              | Atomic radius                                      | Picometers   |
| `rho (g/cm³)`         | Density of the material                            | g/cm³        |
| `E_coh (eV/atom)`     | Cohesive energy                                    | eV/atom      |
| `E_ioniz (eV)`        | Ionization energy                                  | eV           |
| `alpha (1/K)`         | Thermal expansion coefficient                      | 1/K          |
| `R (Ohm*m)`           | Electrical resistivity                             | Ohm*m        |
| `T_melt (K)`          | Melting temperature                                | Kelvin       |
| `E (GPa)`             | Elastic modulus                                    | GPa          |
| `CN`                  | Coordination number                                | Integer      |
| `l_bond (Å)`          | Bond length                                        | Ångstrom     |



## Citation
If you use this dataset, please cite:
[Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials](https://arxiv.org/abs/2502.01813)
