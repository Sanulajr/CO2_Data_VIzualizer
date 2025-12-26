# CO₂ Data Visualizer 🌍📊

An interactive data visualization project that explores **global CO₂ emissions trends** using **Python, Pandas, hvPlot, and Panel**. This visualizer enables users to analyze emissions data across countries and regions over time, using the open-source dataset provided by **Our World in Data**.

## Project Objective

The goal of this project is to demonstrate **data analysis and visualization skills** by transforming raw environmental data into **interactive, insightful visual dashboards** that support trend analysis and comparison.

---

## Features

* **Interactive Visualizations**: Explore CO₂ emissions dynamically using hvPlot and Panel.
* **In-depth Analysis**: Filter data by country, region, and year to uncover emission patterns.
* **Customizable Charts**: Switch between line, bar, and scatter plots and select different metrics.

---

## Dataset

The dataset is sourced from **Our World in Data**, available [here](https://github.com/owid/co2-data/blob/master/owid-co2-data.csv).

Key attributes include:

* `country` – Country or region name
* `year` – Year of observation
* `co2` – Total CO₂ emissions
* `co2_per_capita` – CO₂ emissions per capita
* `gdp` – Gross Domestic Product
* Additional environmental, energy, and economic indicators

---

## Installation

To run the project locally, install the required dependencies:

```bash
pip install pandas hvplot panel
```

---

## Usage

1. **Clone the repository**

   ```bash
   git clone https://github.com/Sanulajr/co2-data-visualizer.git
   cd co2-data-visualizer
   ```

2. **Run the Jupyter Notebook**

   * Open `co2_visualizer.ipynb`
   * Run all cells to generate the visualizations

3. **Launch the Panel Dashboard**

   ```python
   panel.serve('co2_visualizer.ipynb')
   ```

---

## Project Structure

* `co2_visualizer.ipynb` – Main notebook containing data analysis and visualization logic
* `README.md` – Project documentation
* `requirements.txt` – Required Python libraries

---

## Tech Stack

* **Python**
* **Pandas**
* **hvPlot**
* **Panel**
* **Jupyter Notebook**

