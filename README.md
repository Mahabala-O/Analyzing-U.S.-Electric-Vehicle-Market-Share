# U.S. Electric Vehicle Market Share Analysis

**Data Analysis Project** | Jupyter Notebook + Tableau Dashboard

📖 **Full write-up with interactive charts:** [portfolio-mo.vercel.app/projects/us-ev-market-share](https://portfolio-mo.vercel.app/projects/us-ev-market-share)

## 📋 Project Overview
An intermediate data analysis project examining U.S. EV adoption patterns using state-level vehicle registration data across all 50 states and D.C.

**Key deliverables:**
- Cleaned and analyzed EV, PHEV, HEV, and gasoline market shares
- Identified top/bottom adopting states and compared California vs. other large states
- Built interactive Tableau dashboard + presentation slides
- Provided data-driven recommendations for EV infrastructure investment

## 📌 Key Findings
- EVs are **1.24%** of the 287M registered vehicles in the U.S.
- **California holds 35% of all U.S. EVs**; outside California the EV share is 0.92%.
- California's EV share (3.41%) is **27×** North Dakota's (0.13%).
- Flex-fuel (E85) vehicles are 7% of the fleet, but that counts vehicles *capable* of running on E85; most run on regular gasoline.
- **Where to invest:** ranking states by how many EVs they are short of the national average (vehicles × (1.24% − state EV share)) puts **Texas (~89K), Ohio (~77K), and Pennsylvania (~56K)** first. Florida is already above the national average; Georgia ranks 17th.

## 🛠️ Tech Stack
- **Python**: Jupyter Notebook in VS Code (pandas for cleaning & calculations)
- **Visualization**: Tableau (map, bars, pie chart)
- **Presentation**: Tableau Workbook
- **Written Report**: PDF

## 📁 Project Structure
- `notebooks/EVs_Analysis.ipynb` → Main analysis notebook
- `notebooks/portfolio_checks.ipynb` → Follow-up checks behind the portfolio write-up (California's share of EVs, gap-to-average ranking)
- `data/` → Raw & cleaned datasets
- `reports/` → Final PDF report
- `presentations/` → Tableau Workbook
- `images/` → Dashboard screenshots

## 📊 Dashboard Previews

![U.S. EV Registrations Map](images/us-ev-registrations-map.png)

![Top States by EV Adoption Rate](images/top-states-ev-adoption-bar.png)


![National Vehicle Fleet Composition by Fuel Type](images/national-fuel-composition-pie.png)


![California vs Texas vs Florida vs New York - EV & HEV Comparison](images/ca-tx-fl-ny-ev-hev-comparison.png)


## 📊 Interactive Tableau Workbook
[👉 Open full interactive Tableau workbook (.twbx)](presentations/U.S._EV_Market_Share_Presentation.twbx)

## 📄 Downloadable PDF Report
[👉 Download Full Report](reports/U.S_Electric_Vehicle_Market.pdf)

> The PDF is the original April 2026 report. Its recommendations (Texas, Florida, Georgia) were chosen by judgment; the updated, metric-based ranking above is in `notebooks/portfolio_checks.ipynb` and the [portfolio write-up](https://portfolio-mo.vercel.app/projects/us-ev-market-share).

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/Mahabala-O/Analyzing-U.S.-Electric-Vehicle-Market-Share.git`
2. Open the notebook in VS Code or Jupyter
3. Install packages: `pip install -r requirements.txt`

## 📌 Topics
data-analysis, python, jupyter-notebook, tableau, electric-vehicles, ev-adoption, market-share, pandas, powerpoint

---

*Built as part of a data analytics portfolio project — April 2026*
