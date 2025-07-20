# Interactive EU Energy Statistics Map

An interactive Jupyter Notebook-based dashboard allowing users to explore European energy statistics by country via an IPyLeaflet map and dynamic plots.

[![Launch on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/charliemunro/Interactive-Stats-Map-for-Hackathon-project/HEAD?filepath=interactive_map.ipynb)

[![Launch as Voilà App](https://img.shields.io/badge/Launch%20as-Voilà%20App-blue)](https://mybinder.org/v2/gh/charliemunro/Interactive-Stats-Map-for-Hackathon-project/HEAD?urlpath=voila%2Frender%2Finteractive_map.ipynb)

---

## 📖 Overview

This project provides an interactive map of Europe where clicking on a country updates energy source breakdown and CO₂ per capita plots. Built with:

- **Geopandas** for geographic data
- **IPyLeaflet** for interactive map widgets
- **Matplotlib** for dynamic plots
- **SQLite** and **Pandas** for data storage and manipulation

---

## 📁 Repository Structure

```
Interactive-Stats-Map-for-Hackathon-project/
├── data/
│   ├── Europe.shp               # Shapefile of European countries
│   └── energy_data.db           # SQLite database of energy stats
├── translator.ipynb             # Jupyter Notebook with full interactive dashboard
├── requirements.txt             # List of Python dependencies
├── environment.yml              # (Optional) Conda environment specification
└── README.md                    # This file
```

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/charliemunro/Interactive-Stats-Map-for-Hackathon-project.git
   cd Interactive-Stats-Map-for-Hackathon-project
   ```

2. **Install dependencies**

   - **Using pip**:
     ```bash
     pip install -r requirements.txt
     ```
   - **Using Conda (if `environment.yml` provided)**:
     ```bash
     conda env create -f environment.yml
     conda activate interactive-map
     ```

3. **Launch the notebook**

   ```bash
   jupyter notebook translator.ipynb
   ```

4. **Or launch via Binder / Voilà**

   - Click the **Launch on Binder** badge above to run in your browser.
   - Or click the **Voila App** badge to see a clean dashboard without Jupyter UI.

---

## ⚙️ Usage

- **Click** on any country on the map to view:
  - Energy source percentage breakdown over time
  - Renewable energy vs CO₂ per capita bar chart
- **Explore** different years via the dynamic plots.

---

## 🤝 Contributing

Contributions welcome! Please open an issue or submit a pull request to enhance functionality, add new data, or improve styling.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
