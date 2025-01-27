# Machine Learning-Driven Threshold Displacement Energy Dataset

This repository contains the dataset, metadata, and analysis scripts associated with the manuscript:

**"Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials"**  
*Authors*: Rosty B. Martinez Duque, Arman Duha, and Mario F. Borunda  
*Date*: January 22, 2025

## Overview

Understanding the threshold displacement energy (Ed) is crucial for predicting radiation damage in materials, particularly in applications like nuclear reactors, aerospace, and advanced materials engineering. This repository includes:
- Data for monoatomic and polyatomic materials.
- Analytical models derived using the SISSO machine learning method.
- Scripts for preprocessing, analysis, and visualization.

The provided resources enable reproducible research and facilitate further exploration of radiation damage in materials.

---

## Repository Structure

```plaintext
machine-learning-threshold-energy-dataset/
│
├── README.md             # Overview of the repository
├── LICENSE               # Licensing information
├── data/                 # Datasets and metadata
│   ├── monoatomic/       # Monoatomic materials data
│   ├── polyatomic/       # Polyatomic materials data
│   ├── supplementary/    # Supporting data and references
│
├── scripts/              # Scripts for data preprocessing and analysis
│   ├── preprocess.py     # Script to clean and prepare raw data
│   ├── analyze_data.ipynb# Jupyter notebook for analysis
│   ├── generate_figures.py # Script to create visualizations
│
├── docs/                 # Detailed documentation
│   ├── methods.md        # Methods used for data collection and modeling
│   ├── results.md        # Explanation of results and model performance
│
├── CITATION.cff          # Citation information for the repository
└── example_usage/        # Example scripts for using the dataset
    ├── load_data.py      # Example script for loading the data
    ├── model_comparison.ipynb # Notebook comparing model performance
```

---

## Getting Started

### Prerequisites
To use the scripts and notebooks, ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Required Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

Install the required libraries using:
```bash
pip install -r requirements.txt
```

### Usage

1. **Explore the Data**  
   - Navigate to the `data/` directory to view the raw and processed datasets for monoatomic and polyatomic materials.
   - Detailed metadata is available in `data/monoatomic/metadata.md` and `data/polyatomic/metadata.md`.

2. **Run Analysis Scripts**  
   - Use the scripts in `scripts/` to preprocess data, run analyses, or generate figures.
   - Example workflows are provided in `example_usage/`.

3. **Reproduce Results**  
   - Open `scripts/analyze_data.ipynb` for an end-to-end analysis pipeline.
   - Figures and tables used in the manuscript can be generated using `generate_figures.py`.

---

## Dataset Description

- **Monoatomic Materials**:  
  Includes data for 33 monoatomic elements with features like atomic number, cohesive energy, melting temperature, density, and calculated threshold displacement energy (Ed).

- **Polyatomic Materials**:  
  Includes data for alloys, ceramics, and semiconductors with features like stoichiometry, bond lengths, and effective threshold displacement energy (Eeff).

For detailed information, refer to the metadata files in the `data/` directory.

---

## Citation

If you use this dataset or scripts in your work, please cite the manuscript:
```
@article{Duha2025,
  title={Machine Learning-Driven Analytical Models for Threshold Displacement Energy Prediction in Materials},
  author={Rosty B. Martinez Duque, Arman Duha, and Mario F. Borunda},
  journal={Journal Name},
  year={2025},
  doi={10.XXXX/XXXXXX}
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
