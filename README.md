# Data Science Challenges for Fusion Analysis

A repository containing Jupyter notebooks that introduce students to real-world examples using data science tools to make predictions for key Fusion parameters using real Fusion data from the Mega Amp Spherical Tokamak (MAST).

## Description

This project contains a number of Jupyter notebooks designed to introduce students to data science techniques applied to fusion energy research. Using data from the Fair-MAST project, students will learn how to process, analyze, and build predictive models using real experimental fusion data.

The notebooks focus on:

- Data exploration and visualization of fusion parameters
- Predictive modeling of key fusion performance indicators
- Machine learning applications in fusion research

## Data Source

The data used in this project comes from the FAIR-MAST project, which aims to make fusion research data more Findable, Accessible, Interoperable, and Reusable (FAIR). The MAST (Mega Amp Spherical Tokamak) is a fusion energy experiment based at Culham Centre for Fusion Energy in the UK.

## Getting Started

### Prerequisites

- Python 3.11 or higher
- [uv](https://github.com/astral-sh/uv) - A faster and more reliable Python package installer and resolver

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/data-science-challenges.git
   ```

2. Navigate to the project directory

   ```bash
   cd data-science-challenges
   ```

3. Install [uv](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) if you don't have it already

   ```bash
   pipx install uv
   ```

4. Create a virtual environment and install dependencies using uv

   ```bash
   uv venv
   uv pip install -e .
   ```

5. Activate the virtual environment

   ```bash
   # On Windows
   .venv\Scripts\activate

   # On Unix or MacOS
   source .venv/bin/activate
   ```

## Usage

### Running Jupyter Notebooks

To run the Jupyter notebooks, make sure you've activated your virtual environment, then:

```bash
jupyter lab --notebook-dir notebooks/
```

This will open a browser window with the Jupyter interface where you can select and run any of the notebooks.

### Available Notebooks

1. **MAST Plasma Current** - Infer the value plasma current produced by CCFE's Mega Ampere Spherical Tokamak from discrete magnetic diagnostic data.
2. **MAST Plasma Volume** - Infer plasma volume from wide angle camera data.
3. **MAST Plasma Equilibrium** - Infer plasma equilibria from a diverse set of diagnostic data.

### Accessing Fair-MAST Data

Find sample data in the `fair_mast_data` directory. For more data:

1. Visit the [Fair-MAST Data Catalog](https://mastapp.site/)
2. Use the provided API to access the complete FAIR-MAST archive

## License

This project is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/deed.en) (CC BY-SA 4.0).

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This means you are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

See the [LICENSE](LICENSE) file for more details.
