# masters_thesis_stable
Repository of the code used for my masters thesis "Automated Market Maker - Impermanent Loss in High and Low Volatility Markets"

# Automated Market Maker – Impermanent Loss in High and Low Volatility Markets

This repository contains Jupyter notebooks used for the analysis conducted in the master's thesis titled "Automated Market Maker – Impermanent Loss in High and Low Volatility Markets." The primary goal of this research was to investigate impermanent loss within the context of Automated Market Makers (AMMs) and to test the validity of two key hypotheses:

1. **Hypothesis 1:** AMM deposits are profitable in high volatility markets.
2. **Hypothesis 2:** AMM deposits are profitable in low volatility markets.

## Notebooks

The analysis is organized into two Jupyter notebooks, each corresponding to the validation of the above hypotheses:

1. [`Notebook 1: USD EUR Analysis`](AMM_v0.3_USDEUR.ipynb): This notebook presents the analysis conducted to address Hypothesis 1. It explores impermanent loss in high volatility markets, provides insights into the impact on liquidity providers' profitability, and supports the conclusion that AMM deposits remain profitable despite the challenges posed by impermanent loss.

2. [`Notebook 2: USD ETH Analysis`](AMM_v0.3_USDETH.ipynb): This notebook focuses on Hypothesis 2, examining impermanent loss in low volatility markets. It analyzes the profitability of AMM deposits in stable environments, highlights the consistent trading fee potential, and substantiates the hypothesis that AMM deposits are indeed profitable in such market conditions.

2. [`Notebook 2: CZK EUR Analysis`](AMM_v0.3_CZKEUR.ipynb): This notebook focuses on Hypothesis 2, examining impermanent loss in low volatility markets. It analyzes the profitability of AMM deposits in stable environments, highlights the consistent trading fee potential, and substantiates the hypothesis that AMM deposits are indeed profitable in such market conditions.


## Usage

To explore the analysis conducted in this study, follow these steps:

1. Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/danielmalinovsky/masters_thesis_stable.git
   ```

2. Navigate to the `notebooks` directory:

   ```bash
   cd masters_thesis_stable
   ```

3. Open the Jupyter notebooks using your preferred environment (e.g., Jupyter Notebook, JupyterLab):

   ```bash
   jupyter notebook
   ```

4. Select either `AMM_v0.3_USDEUR.ipynb`, `AMM_v0.3_USDETH.ipynb` or `AMM_v0.3_CZKEUR.ipynb` to start exploring the analysis, methodology, and results.

## Citation

If you find this analysis or the corresponding master's thesis helpful, please consider citing it:

```
Daniel Malinovsky. "Automated Market Maker – Impermanent Loss Analysis in High and Low Volatility Markets" Year. [URL](https://github.com/danielmalinovsky/masters_thesis_stable).
```

## License

This repository is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for more details.
