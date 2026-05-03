# Environment Setup Guide

## Prerequisites
- Python 3.8+
- Tableau Desktop or Tableau Public (free: https://public.tableau.com/)
- Access to WRDS (Wharton Research Data Services) for Compustat/CRSP data

## Python Environment Setup

### 1. Clone the repository
git clone https://github.com/KubraBanu/chips-act-analysis.git
cd chips-act-analysis

### 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install dependencies
pip install -r requirements.txt

## Data Sources
- **Compustat**: Financial statement data via WRDS (https://wrds-www.wharton.upenn.edu/)
- **CRSP**: Stock return data via WRDS
- **WRDS Access**: Requires institutional subscription — contact your institution's library

## Running the Analysis
1. Open `Kubra.html` in a browser to view the rendered Python notebook
2. To run interactively, use the source .ipynb file if available
3. Update data file paths at the top of the notebook to point to your downloaded WRDS data

## Tableau Visualization
1. Open Tableau Desktop or Tableau Public
2. Open the `.twbx` file if included, or connect to the provided CSV outputs
3. Data source: processed outputs from the Python analysis

## Key Files
- `Kubra.html` — Main analysis notebook (HTML export)
- `Kubra_chips-act.pptx` — Presentation slides
- `Kubra_Project1-3.pdf` — Full project report
