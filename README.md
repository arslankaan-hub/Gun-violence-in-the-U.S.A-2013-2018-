# Gun Violence Analysis  

## Tableau storyboard link : https://public.tableau.com/app/profile/kaan.arslan6544/viz/Gunviolence_17589872173530/Story1

## Project Summary  
This project focuses on analyzing patterns of gun violence incidents across the United States. Using official datasets, the analysis investigates geographic trends, temporal distributions and incident-level outcomes (fatalities and injuries). While numerous reports exist on gun violence, this project emphasizes building a structured exploratory analysis and developing an interactive Tableau storyboard for effective communication of findings.  

Through exploratory data analysis (EDA), regression testing, clustering and time series evaluation the project identifies factors associated with incident severity and regional variations. The findings provide insights into which states and time periods are most affected and propose evidence-based recommendations for stakeholders.  

By addressing key questions such as which states record the highest incident counts, how fatalities and injuries are distributed, and whether linear relationships exist between variables, the analysis delivers actionable insights to inform prevention strategies, policymaking, and further research.  

## Key Questions  
- Which states experience the highest numbers of fatalities and injuries due to gun violence?  
- How do incidents vary over time (by year, month, or season)?  
- Is there a relationship between fatalities and injuries within incidents?  
- Can clustering methods reveal distinct groups of states or incidents based on severity?  
- Which demographic or environmental factors (if available) contribute to differences in outcomes?  
- What trends emerge when analyzing long-term time series data?  

## Folders  
**01 Project Management** – Contains the project brief. 

**02 Data** – Includes:  (Couldn't upload due to size issue.)
- `Original Data`: Raw CSV gun violence dataset (with JSON spatial file for state mapping).  
- `Prepared Data`: Cleaned and merged datasets ready for analysis.  

**03 Scripts** – Jupyter Notebooks with code for each stage of the analysis:  
- *6.1 Sourcing and Analyzing Time Series Data*  
- *6.2 Exploring Relationships & Visualizations*  
- *6.3 Data Visualization with Folium*  
- *6.4 Machine Learning Regression Analysis*  
- *6.5 Machine Learning Clustering*  

**04 Analysis** – Contains saved plots and choropleth maps, regression plots, clustering results, etc.).    

## Code Overview  
- **pandas** – Data cleaning, merging, and transformation.  
- **numpy** – Numerical computations and handling arrays.  
- **matplotlib** – Visualization of temporal and state-level patterns.  
- **seaborn** – Statistical visualizations and advanced aesthetics.  
- **folium** – Choropleth and geospatial mapping in Python.  
- **scikit-learn** – Regression and clustering (k-means).  
- **json / geopandas** – Integration of spatial data for mapping.  

## Disclaimer  
This dataset was sourced for educational purposes as part of the **CareerFoundry Data Analytics program from Kaggle.  
