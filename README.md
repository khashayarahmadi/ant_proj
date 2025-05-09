# The Sandwich Ant Experiment

## Overview
This project, "Statistical Insights into Food Preference in Ants," investigates how sandwich components—bread type, topping, and butter—affect ant attraction. Authored by Seyed Ahmad Ahmadi, the study uses statistical methods to analyze a dataset of ant counts, aiming to inform pest control, food storage, and preparation practices in ant-prone areas. The analysis includes descriptive statistics and nonparametric tests (Kruskal-Wallis H-test and Mann-Whitney U test), with key findings indicating that topping type, particularly Ham and gherkins with butter, significantly influences ant attraction.

## Project Structure
- **data/**: Contains the dataset `sandwich.csv` with 48 observations.
- **docs/**: Includes the project report `resualt.pdf` detailing the methodology, results, and findings.
- **scripts/**: (Optional) Placeholder for Python scripts used in data analysis (e.g., `analysis.py` if included).
- **README.md**: This file, providing an overview and instructions.

## Dataset
The `sandwich.csv` dataset includes the following variables:
- **antCount**: Number of ants attracted to sandwiches (numeric, continuous).
- **bread**: Type of bread (categorical: Whole Grain, White, Rye, Multi Grain).
- **topping**: Type of topping (categorical: Ham and gherkins, Peanut butter, Yeast spread).
- **butter**: Presence of butter (categorical: Yes, No).

The dataset has no missing values, though sample sizes vary across groups.

## Prerequisites
To reproduce the analysis, ensure you have the following installed:
- **Python 3.10** or later
- **Python libraries**:
  - pandas
  - matplotlib
  - seaborn
  - scipy (for statistical tests)
- **Git** (for cloning the repository)

Install dependencies using:
```bash
pip install pandas matplotlib seaborn scipy
```

## Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Explore the Dataset**:
   - Open `data/sandwich.csv` to view the raw data.
   - Refer to `docs/resualt.pdf` for a detailed description of the dataset and variables.

3. **Run Analysis** (if scripts are included):
   - Navigate to the `scripts/` folder.
   - Run the analysis script (e.g., `python analysis.py`) to generate statistical results and visualizations.

## Key Findings
- **Bread Type**: No significant effect on ant attraction (p=0.3996).
- **Topping**: Significant effect (p<0.0001), with Ham and gherkins with butter being the most attractive (median: 65.0 ants).
- **Butter**: No significant effect (p=0.0825), though it increases ant counts, especially for Whole Grain bread (up to 32.0 ants).

## Report
The full report, `resualt.pdf` in the `docs/` folder, includes:
- Introduction and problem description
- Statistical methods (descriptive statistics, Kruskal-Wallis H-test, Mann-Whitney U test)
- Evaluation with tables and visualizations
- Summary, bibliography, and appendix

## Contributing
Contributions are welcome! Please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details (if included).

## Contact
For questions or feedback, contact Seyed Ahmad Ahmadi via [your-email@example.com] or open an issue on GitHub.

## Acknowledgments
- References: Conover (1999), Hollander et al. (2013), Hölldobler & Wilson (1990).
- Tools: Python, pandas, matplotlib, seaborn, scipy.
