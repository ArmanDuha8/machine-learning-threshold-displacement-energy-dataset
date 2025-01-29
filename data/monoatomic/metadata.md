# Dataset Metadata: Threshold Displacement Energy Data

## General Information
- **Title**: Threshold Displacement Energy Dataset with Material Properties
- **Filename**: eds_all_methods.pdf
- **Version**: 1.0.0
- **License**: CC BY 4.0
- **Authors**: Arman Duha, Rosty B. Martinez Duque, Mario F. Borunda
- **Description**: 
  This dataset contains threshold displacement energy (Ed) values for various monoatomic and polyatomic materials, along with physical and thermal properties such as atomic number, cohesive energy, density, melting temperature, and bond length. The data supports research into radiation damage prediction using analytical and computational methods.

## Data Description
- **File Format**: PDF (Portable Document Format)
- **Size**: Approximate file size in MB (e.g., 1 MB)
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

## Data Collection & Processing
- **Source**: 
  The dataset is compiled from theoretical and experimental studies.
- **Processing Steps**:
  - Data was collected for monoatomic and polyatomic materials.
  - Units were standardized across all data entries.
  - Missing values were imputed using averages or related calculations.
  - Outliers were checked against published values for validation.

## How to Use the Data
1. **Access**:
   - Open the `eds_all_methods.pdf` file for full data details.
   - Convert to a tabular format (e.g., CSV) if needed for programmatic analysis.
2. **Suggested Analysis**:
   - Explore correlations between Ed and other properties such as density (`rho`) and cohesive energy (`E_coh`).
   - Use machine learning models to predict Ed from the provided properties.

## Limitations
- The dataset does not account for directional dependencies of threshold displacement energy (anisotropy).
- Some materials have approximate values due to limited available data.

## Citation
If you use this dataset, please cite:
@article{Duha2025, title={Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials}, author={Rosty B. Martinez Duque, Arman Duha, and Mario F. Borunda}, journal={Journal Name}, year={2025}, doi={10.XXXX/XXXXXX} }
