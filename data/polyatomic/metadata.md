# Dataset Metadata: Threshold Displacement Energy Data

## General Information
- **Title**: Threshold Displacement Energy Dataset with Material Properties
- **Filename**: polyatomic_avg_Ed.csv
- **Version**: 1.0.0
- **License**: CC BY 4.0
- **Authors**: Rosty B. Martinez Duque, Arman Duha, Mario F. Borunda
- **Description**: 
  This dataset contains threshold displacement energy (Ed) values averaged over different literature sources (raw data with separate literature values are in the
  file "Polyatomic.csv") for various polyatomic materials, along with fundamental physical and chemical properties of the primary knocked atom (PKA).
## Data Description
- **File Format**: CSV
- **Number of Entries**: 235 rows (materials)
- **Number of Features**: 8 columns (properties)

### **Variables Included**
| Column Name           | Description                                        | Units        |
|-----------------------|----------------------------------------------------|--------------|
| `material_name`       | Name of the material                               | String       |
| `Ed (eV)`             | Average threshold displacement energy              | eV           |
| `PKA_Z`               | Atomic number of primary knocked atom              | Integer      |
| `PKA_CN`              | Coordination number of primary knocked atom        | Integer      |
| `PKA_Stochiometry`    | Stochiometry of primary knocked atom               | Fraction     |
| `PKA_I (Å)`           | Bond length of primary knocked atom                | Ångstrom     |
| `rho (g/cm³)`         | Density of the material                            | g/cm³        |
| `PKA_m (u)`           | Atomic mass of primary knocked atom                | Atomic mass  |
| `PKA_r (pm)`          | Atomic radius of primary knocked atom              | Picometers   |




## Citation
If you use this dataset, please cite:
[Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials](https://arxiv.org/abs/2502.01813)
