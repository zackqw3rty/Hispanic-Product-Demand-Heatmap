# Hispanic Demographic & Product Demand Mapper

## 📌 Overview
This project identifies ZIP codes across select regions with high Hispanic population density and evaluates the correlation with potential demand for culturally significant food products. The goal is to support strategic retail placement and regional sales targeting based on data-driven insights.

## 🚀 Purpose
To build a simple yet powerful tool that:
- Maps Hispanic population concentration by ZIP code
- Cross-references population data with grocery retail store locations
- Highlights high-potential regions for product demand
- Outputs actionable insights for market expansion and sales strategy

## 📂 Features
- ✅ Census data ingestion and cleaning
- ✅ Visualization of demographic clusters (via Plotly)
- ✅ Basic demand estimation model using population-to-store proximity
- ✅ Exportable tables of high-opportunity ZIP codes
- ⏳ Future: Store-level revenue correlation and predictive modeling, SNAP

## 📊 Data Sources
- [U.S. Census Bureau ACS 5-Year Estimates](https://www.census.gov/data.html)
- Retail store location data (manually sourced)

## 🛠 Tech Stack
- Python (Pandas, Plotly)
- Jupyter Notebook

## 📈 Outputs
- Interactive maps showing ZIP code demand hotspots
- Ranked CSV tables of ZIP codes by demand potential
- Plots and graphs for data storytelling

## 🧠 Why It Matters
Cultural relevance and accessibility drive food purchase behavior. By identifying the right regions, brands can:
- Increase revenue through smarter placement
- Serve communities more authentically
- Reduce risk and waste in logistics and marketing

## 🔮 Planned Feature Enhancements

To improve the accuracy and strategic value of this analysis, the following data layers will be added:

### 🏷 SNAP Participation Data
- Identify ZIP codes with high SNAP (Supplemental Nutrition Assistance Program) usage
- Evaluate affordability alignment and potential for cost-sensitive product placement

### 💰 Median Household Income
- Assess economic fit for pricing strategies
- Filter out low-potential areas for premium or specialty SKUs

### 🛒 Grocery Store Availability
- Cross-reference Hispanic population clusters with proximity to grocery chains
- Detect under-served areas (high demand, low access)
- Guide retail outreach efforts for in-store placement

These data layers will feed into a composite **Opportunity Score**, ranking each ZIP by product-market fit and retail activation priority.

## 🚀 How to Run This Project

1. **Clone the repo**
   ```bash
   git clone git@github.com:zackqw3rty/hispanic-dem-map.git
   cd hispanic-dem-map
   ```

2. **Set up a Python virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open the file**
   Navigate to `notebooks/demographic_heatmap.ipynb` and run all cells to visualize the heatmap.

---

## ✅ Requirements
- Python 3.8+
- pip
- Jupyter Notebook
- Internet connection (for map rendering via Plotly)

For issues or setup help, feel free to open an issue or contact the repo owner.
## 🤝 Contributing
This project is in MVP stage — feel free to fork, adapt, or suggest features via issues or pull requests.

## 📬 Contact
For questions or collaboration, reach out via LinkedIn or open an issue here.

---

> "Data tells you where your culture belongs. Use it wisely."
