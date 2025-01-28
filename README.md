# GEOSPATIAL-TEMPORAL VISUALIZATION OF GROUND WATER DATA ON MAP OF INDIA

## **Project Description**
This project visualizes groundwater quality across India using geospatial-temporal analysis techniques. Leveraging water sample data collected by a government organization between 2010 and 2018, it provides valuable insights into water quality variations by region and time. The analysis assesses physicochemical parameters against BIS/WHO standards for safe drinking water, enabling targeted environmental monitoring and public health interventions.

---

## **Dataset Overview**
The dataset consists of:
1. **Geographical Details:**
   - Site ID
   - State Name
   - District Name
   - Block Name
   - Latitude and Longitude

2. **Water Quality Parameters:**
   - Total Dissolved Solids (TDS)
   - Sulphate
   - Calcium
   - Arsenic
   - Fluoride
   - Iron
   - 17 other chemical components

---

## **Objective**
1. Visualize groundwater quality across India on a geospatial map.
2. Determine if physicochemical parameters meet BIS/WHO standards for drinking water.

---

## **Key Features**
1. **Geospatial Analysis:**
   - Interactive visualizations of water quality data on the map of India.
   - Cluster formation by water safety levels (green, yellow, blue, red).
   - Visualization of state and district boundaries with custom styles.
   
2. **Temporal Analysis:**
   - Time-based variation of groundwater quality parameters.
   
3. **Google Maps Integration:**
   - Enhanced interactive maps with popups indicating drinkable status at specific sites.
   
4. **Heatmaps:**
   - Geospatial heatmaps showcasing high-concentration regions for various contaminants.

---

## **Approach**
1. **Libraries Used:**
   - `GeoPandas`, `Pandas`, `NumPy`, `Folium`, `Matplotlib`, `re`, `Shapely`, `GeoJSON`

2. **Data Preparation:**
   - Cleaned and formatted raw data.
   - Converted latitude and longitude to a standardized geospatial format.
   - Created water GeoDataFrame by integrating geographical and quality data.

3. **Visualization:**
   - Overlaid water quality clusters on India’s map.
   - Used state and district boundary datasets for detailed mapping.
   - Color-coded clusters based on BIS/WHO drinking water standards.
   - Displayed temporal variations and heatmaps for enhanced insights.

4. **Analysis:**
   - Identified regions with high concentrations of contaminants such as arsenic, fluoride, sodium, etc.
   - Highlighted regions prone to acidic and undrinkable water.

---

## **Results**
1. **Identified High-Concentration Regions:**
   - High Arsenic: Tripura, Assam, Arunachal Pradesh, Meghalaya.
   - High Acidity: Kerala, Maharashtra, Tamil Nadu.
   - High Sodium: Andhra Pradesh, Rajasthan, Gujarat.
   - High Fluoride: Rajasthan, Karnataka.

2. **Visualizations:**
   - Geospatial maps with clusters for safe and unsafe drinking water.
   - Temporal variation plots showing trends over time.
   - Google Maps-based visualizations with interactive popups displaying drinkable status.

---

## **Usage Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis:
   ```bash
   python main.py
   ```

5. Open the generated HTML maps in your browser for interactive visualization.

---

## **Project Structure**
```
repository-name/
├── data/
│   ├── groundwater_data.csv           # Water quality data
│   ├── india_state_boundaries.json    # State boundaries GeoJSON
│   ├── india_district_boundaries.json # District boundaries GeoJSON
├── notebooks/
│   └── eda_and_visualization.ipynb    # Jupyter notebook for EDA and visualizations
├── scripts/
│   ├── data_cleaning.py               # Data cleaning script
│   ├── clustering.py                  # Clustering logic
│   └── visualization.py               # Geospatial visualization scripts
├── outputs/
│   ├── india_water_quality_map.html   # Main interactive map
│   └── temporal_variation_plot.png    # Temporal variation plot
├── requirements.txt                   # Python dependencies
├── README.md                          # Project documentation
└── main.py                            # Entry point for the project
```

---

## **Dependencies**
Install the following Python libraries:
- GeoPandas
- Pandas
- NumPy
- Folium
- Matplotlib
- Shapely
- GeoJSON

---

## **How to Contribute**
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## **License**
This project is licensed under the [MIT License](LICENSE).

---

## **Acknowledgments**
We thank the government organization for providing the groundwater dataset. Special thanks to the open-source community for developing the libraries and tools used in this project.


