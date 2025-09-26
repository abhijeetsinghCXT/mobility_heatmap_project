# mobility_heatmap_project

# AI-Powered Mobility Heatmaps for Pathways

## Project Overview

This project utilizes the Smart Mobility and Traffic Optimization Dataset to analyze urban traffic patterns, identify high-congestion zones, and inform smart city planning. By leveraging data visualization and machine learning, the goal is to provide actionable insights for designing more efficient and intelligent transportation pathways, ultimately aiming to reduce congestion and improve urban accessibility.


## Dataset

The analysis is performed on the `smart_mobility_dataset.csv` file. This dataset integrates various data sources to provide a comprehensive view of urban mobility.

**Key columns include:**
* **Timestamp & Location:** `Timestamp`, `Latitude`, `Longitude`
* **Traffic Data:** `Vehicle_Count`, `Traffic_Speed_kmh`, `Traffic_Condition`
* **Environmental Impact:** `Emission_Levels_g_km`
* **Smart Mobility Metrics:** `Ride_Sharing_Demand`, `Parking_Availability`


## ✨ Features & Analyses

The primary Jupyter Notebook (`mobility_analysis.ipynb`) in this repository performs the following analyses:

1.  **Exploratory Data Analysis (EDA):** Initial analysis of the dataset's structure, statistical summary, and distribution of traffic conditions.
2.  **Interactive Mobility Heatmap:** An interactive map generated with Folium to visualize traffic density based on vehicle counts, allowing for dynamic exploration of high-traffic areas.
3.  **AI-Powered Congestion Hotspot Detection:** K-Means clustering is used to automatically identify the epicenters of high congestion, marking them on a map as prime candidates for infrastructure review.
4.  **Time-Series Analysis of Traffic Patterns:** A line graph visualizes how 'High' and 'Low' congestion levels fluctuate throughout the day, clearly identifying morning and evening rush hours.


## 🛠️ Technologies Used

* **Python 3**
* **Pandas:** For data manipulation and analysis.
* **Matplotlib & Seaborn:** For static data visualization.
* **Folium:** For creating interactive geospatial maps.
* **Scikit-learn:** For implementing the K-Means clustering algorithm.
* **Jupyter Notebook:** For organizing and executing the analysis workflow.

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/abhijeetsinghCXT/mobility_heatmap_project.git
    cd mobility_heatmap_project
    ```

2.  **Set up the environment:**
    It's recommended to use a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install pandas matplotlib seaborn folium scikit-learn jupyterlab
    ```

4.  **Add the dataset:**
    Place your `smart_mobility_dataset.csv` file in the root directory of the repository.

5.  **Launch the notebook:**
    ```bash
    jupyter lab mobility_analysis.ipynb
    ```
    Then, run the cells in the notebook from top to bottom.

---

## 📈 Results & Visualizations

The analysis produces several key visualizations that help in understanding traffic behavior:

* **Congestion Hotspots Map:** Identifies the precise geographical centers of recurring high traffic.
    

* **Mobility Density Heatmap:** Shows a high-level overview of movement density across the city.
    

* **Rush Hour Analysis:** A line graph clearly illustrates the morning and evening peaks in traffic congestion.
