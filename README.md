# NASA Meteorite Data Analysis and Clustering

## Project Overview

This project explores and analyzes meteorite landing data sourced from NASA’s open datasets. It focuses on fetching, cleaning, and processing the data, 
performing exploratory data analysis (EDA), and applying machine learning clustering techniques to identify patterns based on meteorite characteristics 
such as mass, location, year, and classification.

## Objectives

- Download and preprocess meteorite landing data from NASA’s API.
- Conduct exploratory data analysis to understand temporal trends and distribution of meteorite classes.
- Visualize meteorite landings geographically and over time.
- Apply KMeans clustering to group meteorites based on their features.
- Save models and generate summary reports for further scientific analysis.

## Dataset

- **Source:** NASA Open Data Portal – Meteorite Landings
- **Format:** JSON
- **Key Fields:** Name, ID, Mass (g), Year, Latitude, Longitude, Meteorite Class, Fall Type

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- KMeans Clustering
- Requests
- Joblib

## Usage Instructions

1. **Data Download:** Run the data fetching script or use the pre-downloaded JSON file located in `data/raw/meteorites.json`.
2. **Data Cleaning and EDA:** Execute the notebook or Python scripts to perform exploratory data analysis, generate visualizations, and understand the data.
3. **Machine Learning:** Apply clustering algorithms to the cleaned dataset and interpret the clusters.
4. **Save Outputs:** Models and plots are saved to the `models/` and `outputs/plots/` directories respectively.
5. **Reports:** Summary statistics and results are saved in `outputs/eda_summary.csv`.

## Key Functions

- `fetch_data()`: Fetch meteorite data from NASA API.
- `clean_data()`: Clean and preprocess the dataset.
- `perform_eda()`: Generate exploratory plots and statistics.
- `run_clustering()`: Apply KMeans clustering and save the model.
- `visualize_clusters()`: Visualize clustering results spatially.

## Results

- Identification of temporal trends in meteorite landings.
- Geographic distribution maps of meteorite falls.
- Clustering reveals groups based on mass and spatial location.
- Summary reports provide insights into meteorite classes and fall types.

## Future Work

- Implement more advanced clustering methods (e.g., DBSCAN, hierarchical clustering).
- Integrate chemical composition data for enhanced classification.
- Develop interactive visualizations using libraries like Folium or Plotly.
- Explore predictive modeling of meteorite impact risks.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or collaboration, please contact:  
**Arslan Gill**  
Email: arslangill4437@gmail.com   
LinkedIn: www.linkedin.com/in/arslan-gill-ab97b414b

---

*This project was developed as part of my data science portfolio leveraging NASA Earth observation data and machine learning techniques.*
