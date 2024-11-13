# Finance-And-Risk-Analytics

## Problem Statement
The wealth management industry has expanded significantly, with portfolio managers playing a crucial role in assisting individuals and businesses with investment decisions. Portfolio managers work with analysts to develop tailored investment portfolios, yet they face intense competition and must utilize resources effectively. This project focuses on providing investment consultation for two investors, Mr. Patrick Jyenger and Mr. Peter Jyenger, each with unique financial goals.

## Solution Approach
The solution involves a structured approach to analyzing and selecting stocks, including data gathering, preprocessing, visualization, and metric analysis, followed by custom portfolio recommendations.

### Key Steps

1. **Data Gathering**
   - Collected data on 24 different stocks across four sectors, along with S&P 500 data for benchmarking.

2. **Data Preprocessing**
   - Used Python to clean the dataset, resolving discrepancies and structuring it for analysis.

3. **Data Visualization**
   - Generated Power BI reports for each sector to visualize and compare stock performance, facilitating informed decision-making.

4. **Metric Calculation**
   - Calculated key financial metrics using Python:
     - Average daily return
     - Average risk
     - Annualized risk
     - Annualized return
     - Cumulative return
     - Sharpe ratio
   - These metrics were essential in guiding the investment process and forming the basis for comparison.

5. **Portfolio Selection**
   - Selected stocks aligned with the financial objectives of Mr. Patrick Jyenger and Mr. Peter Jyenger by analyzing calculated metrics and aligning them with their unique goals.
   - Created customized investment portfolios to suit their individual needs.

## Files and Structure
- `data/`: Contains the datasets for the 24 stocks and S&P 500.
- `notebooks/`: Jupyter notebooks with data cleaning, metric calculation, and visualization code.
- `reports/`: Power BI reports for sector-wise analysis.
- `src/`: Python scripts for metric calculations and portfolio selection.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Finance-And-Risk-Analytics.git
