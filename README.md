# masters_thesis_stable
Repository of the code used for my masters thesis "Automated Market Maker - Impermanent Loss in High and Low Volatility Markets"

# Automated Market Maker – Impermanent Loss Analysis

This repository contains Jupyter notebooks used for the analysis conducted in the master's thesis titled "Automated Market Maker – Impermanent Loss in High and Low Volatility Markets." The primary goal of this research was to investigate impermanent loss within the context of Automated Market Makers (AMMs) and to test the validity of two key hypotheses:

1. **Hypothesis 1:** AMM deposits are profitable in high volatility markets.
2. **Hypothesis 2:** AMM deposits are profitable in low volatility markets.

## Notebooks

The analysis is organized into two Jupyter notebooks, each corresponding to the validation of the above hypotheses:

1. [`Notebook 1: USD EUR Analysis`](High_Volatility_Analysis.ipynb): This notebook presents the analysis conducted to address Hypothesis 1. It explores impermanent loss in high volatility markets, provides insights into the impact on liquidity providers' profitability, and supports the conclusion that AMM deposits remain profitable despite the challenges posed by impermanent loss.

2. [`Notebook 2: USD ETH Analysis`](notebooks/Low_Volatility_Analysis.ipynb): This notebook focuses on Hypothesis 2, examining impermanent loss in low volatility markets. It analyzes the profitability of AMM deposits in stable environments, highlights the consistent trading fee potential, and substantiates the hypothesis that AMM deposits are indeed profitable in such market conditions.

2. [`Notebook 2: CZK EUR Analysis`](notebooks/Low_Volatility_Analysis.ipynb): This notebook focuses on Hypothesis 2, examining impermanent loss in low volatility markets. It analyzes the profitability of AMM deposits in stable environments, highlights the consistent trading fee potential, and substantiates the hypothesis that AMM deposits are indeed profitable in such market conditions.


## Usage

To explore the analysis conducted in this study, follow these steps:

1. Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/danielmalinovsky/masters_thesis_stable.git
   ```

2. Navigate to the `notebooks` directory:

   ```bash
   cd masters_thesis_stable/notebooks
   ```

3. Open the Jupyter notebooks using your preferred environment (e.g., Jupyter Notebook, JupyterLab):

   ```bash
   jupyter notebook
   ```

4. Select either `High_Volatility_Analysis.ipynb` or `Low_Volatility_Analysis.ipynb` to start exploring the analysis, methodology, and results.

## Dependencies

The notebooks have been developed using Python and utilize popular data analysis libraries. Ensure you have the required dependencies installed by creating a virtual environment and installing the dependencies listed in the `requirements.txt` file:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
pip install -r requirements.txt
```

## Citation

If you find this analysis or the corresponding master's thesis helpful, please consider citing it:

```
Author(s). "Title of the Thesis." Year. URL to the Master's Thesis (if available).
```

## License

This repository is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for more details.
