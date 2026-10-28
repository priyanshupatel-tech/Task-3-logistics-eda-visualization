# Week 3: Advanced Data Analysis and Visualization in Logistics

## Project Overview
This project demonstrates Exploratory Data Analysis (EDA) and data visualization techniques using a hypothetical logistics dataset. The goal is to understand shipment patterns, delivery performance, transportation costs, and relationships between operational variables.

## Objectives
- Analyze a simulated logistics dataset using Python.
- Calculate descriptive statistics and central tendency measures.
- Examine correlations between distance, shipment volume, transport cost, and delivery time.
- Create visualizations to identify patterns and compare logistics metrics.
- Interpret findings and suggest data-driven operational improvements.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset Description
The dataset contains 60 simulated shipment records with the following columns:

- `Shipment_ID`: Unique shipment identifier.
- `Region`: Shipment region (North, South, East, or West).
- `Distance_KM`: Shipment distance in kilometres.
- `Shipment_Volume`: Simulated shipment volume.
- `Transport_Cost`: Simulated transportation cost.
- `Delivery_Time_Hours`: Delivery duration in hours.
- `Delivery_Status`: Simulated status (On Time or Delayed).

**Note:** The dataset is hypothetical and is intended for educational and analytical practice. It does not represent actual logistics company records.

## Exploratory Data Analysis
The analysis includes:
- Dataset structure and data-type inspection.
- Descriptive statistics using `describe()`.
- Delivery status counts.
- Region-wise average delivery time and transport cost.
- Correlation analysis among numerical variables.

## Visualizations
Six charts are generated using Matplotlib:

1. **Delivery-Time Histogram:** Examines the distribution of delivery durations.
2. **Regional Transport-Cost Bar Chart:** Compares average transportation costs across regions.
3. **Distance vs Delivery-Time Scatter Plot:** Examines the relationship between distance and delivery duration.
4. **Shipment-Volume Box Plot:** Displays the median, spread, and potential outliers in shipment volume.
5. **Correlation Heatmap:** Visualizes pairwise correlations among numerical logistics variables.
6. **Regional Delivery-Time Bar Chart:** Compares average delivery durations across regions.

The charts are saved as PNG files in the `visualizations/` directory.

## Key Analytical Observations
The simulated data shows a positive association between shipment distance and delivery time, as well as between distance and transportation cost. Regional averages also vary in the generated sample.

These observations are illustrative only. Because the dataset is simulated, they should not be interpreted as actual operational performance or proof of causal relationships.

## Project Structure
```text
week-3-logistics-eda-visualization/
├── week3_logistics_eda_visualization.ipynb
├── week3_logistics_data.csv
├── week3_region_summary.csv
├── README.md
└── visualizations/
    ├── 01_delivery_time_histogram.png
    ├── 02_region_transport_cost.png
    ├── 03_distance_vs_delivery_time.png
    ├── 04_shipment_volume_boxplot.png
    ├── 05_correlation_heatmap.png
    └── 06_region_delivery_time.png
```

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install pandas numpy matplotlib`

3. Open `week3_logistics_eda_visualization.ipynb` in Jupyter Notebook.
4. Run the notebook cells in sequence to generate the dataset, analysis results, and visualizations.

## Recommendations
- Monitor delivery-time distributions and delayed-shipment rates.
- Compare transportation costs alongside distance and shipment volume.
- Investigate unusually long delivery times using additional operational data.
- Validate regional differences using larger, real-world datasets before making business decisions.

## Conclusion
This project demonstrates how EDA, descriptive statistics, correlation analysis, and visualizations can help interpret logistics data. It provides a foundation for identifying patterns and developing questions for further operational investigation.

## Author
Priyanshu Patel

## Limitations
The dataset is synthetic and relatively small. Results are intended for educational purposes and cannot be generalized to real logistics operations without additional data and validation.
