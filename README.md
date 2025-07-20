# Interactive EU Energy Statistics Map

An interactive Jupyter Notebook–based dashboard allowing users to explore European energy statistics by country via an IPyLeaflet map and dynamic plots.

[![Launch on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/charliemunro/Interactive-Stats-Map-for-Hackathon-project/HEAD?filepath=interactive_map.ipynb)  
[![Launch as Voilà App](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/charliemunro/Interactive-Stats-Map-for-Hackathon-project/HEAD?urlpath=voila%2Frender%2Finteractive_map.ipynb)  
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 📖 Overview

This notebook provides an interactive map of Europe where clicking on a country updates two dynamic plots:

- **Energy source breakdown** over time (oil, coal, gas, nuclear, renewables)  
- **Renewables vs CO₂ per capita** bar chart  

Built with:

- **GeoPandas** for geographic data  
- **IPyLeaflet** for the interactive map widget  
- **Matplotlib** for dynamic plotting  
- **SQLite** & **Pandas** for data storage and manipulation  

---

## 📂 Repository Structure

```
Interactive-Stats-Map-for-Hackathon-project/
├── data/
│   ├── Europe.shp               # Shapefile of European countries (with .dbf, .shx, etc.)
│   └── energy_data.db           # SQLite database of energy stats
├── interactive_map.ipynb        # Jupyter Notebook with full interactive dashboard
├── requirements.txt             # Python dependencies for pip
├── environment.yml              # Conda environment spec for Binder
├── docs/
│   └── interactive-map.gif      # Animated GIF preview
├── LICENSE                      # MIT License
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
   - **With pip**:  
     ```bash
     pip install -r requirements.txt
     ```  
   - **With Conda** (for Binder / local env):  
     ```bash
     conda env create -f environment.yml
     conda activate interactive-map
     ```

3. **Launch locally**  
   ```bash
   jupyter notebook interactive_map.ipynb
   ```

4. **Or launch in the cloud**  
   - Click **Launch on Binder** above to run in your browser.  
   - Click **Launch as Voilà App** for a clean, widget‑only view.

---

## 🎥 Demo Preview

<p align="center">
  <img src="docs/interactive-map.gif" alt="Interactive Map Demo" width="600"/>
</p>

*Click the Binder or Voilà badge above to try the live version!*

---

## ⚙️ Usage

- **Click** on any country in the map to update:  
  - A time‑series line chart of energy source shares.  
  - A combined bar chart of renewables vs CO₂ per capita.  
- **Customize** by editing the notebook cells (data filters, plot styles, map settings).

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request to:

- Add new data or years  
- Enhance interactivity or UI styling  
- Improve performance or code structure  

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🔖 Topics

`jupyter-notebook` · `geopandas` · `ipyleaflet` · `interactive-visualization` · `data-science`
