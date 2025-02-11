# Machine Learning-Driven Threshold Displacement Energy Dataset

This repository contains the dataset, metadata, and analysis scripts associated with the manuscript:

**[Duque, Rosty B. Martinez, Arman Duha, and Mario F. Borunda. "Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials." arXiv preprint arXiv:2502.01813 (2025).](https://arxiv.org/abs/2502.01813)**

## Overview

Understanding the threshold displacement energy (Ed) is crucial for predicting radiation damage in materials, particularly in applications like nuclear reactors, aerospace, and advanced materials engineering. This repository includes:
- Data used as features for monoatomic and polyatomic materials to derive analytical models to predict Ed using the [SISSO](https://github.com/rouyang2017/SISSO) machine learning method.
- Scripts for running examples and reproducing results.

The provided resources enable reproducible research, facilitate further exploration of radiation damage in materials, and can, in general, be useful for any research requiring fundamental property data of materials.

---

## Repository Structure

```plaintext
machine-learning-threshold-energy-dataset/
│
├── CITATION.bib          # Citation information for the repository
├── README.md             # Overview of the repository
├── LICENSE               # Licensing information
├── data/                 # Datasets and metadata
│   ├── monoatomic/       # Monoatomic materials data
│   ├── polyatomic/       # Polyatomic materials data
│   ├── references.pdf    # References of data source
│
├── scripts/              # Scripts for reproducing results
│   ├── R_squared.py     # Script to calculate R2 after running the example
│
└── example/        # Example data and scripts for using the dataset
    
```

---

## Getting Started

### Prerequisites
To use the scripts and notebooks, ensure you have the following installed:
- Python 3.8+
- Required Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

Install the required libraries using:
```bash
pip install -r requirements.txt
```

### Usage

1. **Explore the Data**  
   - Navigate to the `data/` directory to view the raw and processed datasets for monoatomic and polyatomic materials.
   - Detailed metadata is available in `data/monoatomic/metadata.md` and `data/polyatomic/metadata.md`.

2. **Run examples**  
   - Use the files in `example/` to run your first example.

3. **Reproduce Results**  
   - Open `scripts/` for reproducing R-squared values shown in the manuscript.

---

## Dataset Description

- **Monoatomic Materials**:  
  Includes data for 33 monoatomic elements with features like atomic number, cohesive energy, melting temperature, density, and calculated threshold displacement energy (Ed).

- **Polyatomic Materials**:  
  Includes data for alloys, ceramics, and semiconductors with features like stoichiometry, bond lengths, etc.

For detailed information, refer to the metadata files in the `data/` directory.

---

## Citation

If you use this dataset or scripts in your work, please cite the manuscript:
```
@article{duque2025machine,
  title={Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials},
  author={Duque, Rosty B Martinez and Duha, Arman and Borunda, Mario F},
  journal={arXiv preprint arXiv:2502.01813},
  year={2025}
}
```

---

## License

This repository is licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/). You are free to share, adapt, and build upon this work, provided appropriate credit is given.

---

## Contributing

Contributions are welcome! If you encounter any issues, have questions, or wish to improve this repository, feel free to open an issue or submit a pull request.

---

## Contact

For questions or feedback, please contact:  
**Arman Duha**  
📧 [arman.duha@okstate.edu](mailto:arman.duha@okstate.edu)  
🌐 [LinkedIn](https://www.linkedin.com/in/arman-duha)  

---
