# Traffic Accident Analysis: Road Conditions, Weather, and Time

## Task Description
This repository contains the code and documentation for Task 5 completed during my internship at Prodigy Infotech as a Data Science Intern. The task focused on analyzing traffic accident data to identify patterns related to road conditions, weather, and time of day, with the aim of visualizing accident hotspots and contributing factors.

## Data Handling
### Initial Data Overview
The dataset contains 12,316 entries and 32 columns, including features such as time, day of the week, age band of drivers, road surface conditions, weather conditions, and accident severity.

### Data Cleaning
- Checked for missing values in the dataset. Various columns had missing values, which were handled by dropping the rows with missing data.
- Checked for and dropped duplicate entries in the dataset.

## Data Analysis
### Machine Learning Model
- Utilized a Random Forest Classifier to predict accident severity based on weather conditions, road surface conditions, and time of day.
- Achieved an accuracy of 86% on the test dataset.

### Visualizations
- Analyzed the distribution of accidents by weather conditions, road surface conditions, and time of day using bar plots and histograms.
- Visualized the correlation between contributing factors using a heatmap.
- Identified accident hotspots by creating a heatmap of accidents by time of day, weather conditions, and road surface conditions.
- Explored the types of vehicles involved in accidents and different collision types using count plots.

## Usage
To reproduce the analysis:
1. Ensure all required libraries are installed (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
2. Clone the repository to your local machine.
3. Navigate to the `notebooks/` directory and run the Jupyter notebooks.

## Contributions
Contributions to this repository are welcome. Feel free to suggest improvements, report issues, or contribute code to enhance the analysis and visualization process.

## License
This project is licensed under the MIT License.




