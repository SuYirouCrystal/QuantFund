# QuantFund

> Jupyter-based quantitative finance analyses and tools from Winter 2024 internship projects, including return-hold performance assessment and risk parity portfolio construction.

## Table of Contents

1. [About](#about)  
2. [Notebooks](#notebooks)  
3. [Prerequisites](#prerequisites)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## About

This repository contains two core analyses completed during a Winter 2024 quantitative finance internship:

- **Return-Hold Assessment**: Evaluating performance persistence of assets under various holding periods.  
- **Risk Parity Calculation**: Building and backtesting a risk-parity portfolio, balancing asset volatilities.

Each analysis is delivered as a self-contained Jupyter Notebook with narrative explanations, charts, and code.

---

## Notebooks

| Notebook                      | Description                                          |
| ----------------------------- | ---------------------------------------------------- |
| `return-hold-assessment.ipynb` | Assess performance metrics across different hold periods. |
| `risk-parity.ipynb`            | Construct and backtest a volatility-weighted portfolio. |

---

## Prerequisites

- Python 3.8+  
- Jupyter Notebook or JupyterLab  
- Core libraries:
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `scipy`  
  - `yfinance` (or other data-fetch library)  

---

## Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/SuYirouCrystal/QuantFund.git
   cd QuantFund
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. (Optional) If requirements.txt is not present, install manually:
   ```bash
   pip install pandas numpy matplotlib scipy yfinance
   ```

## Usage
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open and run each notebook cell by cell.
3. Modify parameters (tickers, dates, weights) at the top of each notebook to explore different scenarios.

## Project Structure
```plaintext
QuantFund/
├── return-hold-assessment.ipynb
├── risk-parity.ipynb
├── LICENSE.md
├── README.md
└── requirements.txt
```

## Contributing
Contributions and suggestions are welcome! Please open an issue or submit a pull request with improvements, bug fixes, or additional analyses.

## License
This project is licensed under the MIT License.
