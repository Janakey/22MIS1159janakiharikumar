# Mobile Device Usage Analysis with Self-Organizing Maps DIGITAL ASSIGNMENT-2 BIG DATA ANALYTICS -JANAKI 22MIS1159

## About the Dataset
This dataset provides a comprehensive analysis of mobile device usage patterns and user behavior classification. It contains 700 samples of user data, including metrics such as app usage time, screen-on time, battery drain, and data consumption. Each entry is categorized into one of five user behavior classes, ranging from light to extreme usage.

Key Features:
- User ID
- Device Model
- Operating System
- App Usage Time (in minutes)
- Screen On Time (in hours)
- Battery Drain (in mAh)
- Number of Apps Installed
- Data Usage (in MB)
- Age
- Gender
- User Behavior Class (1 to 5)

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- minisom

You can install the required packages using pip:
pip install numpy pandas matplotlib minisom

#Project Overview
This project utilizes Self-Organizing Maps (SOM) to analyze mobile device usage data. The primary goal is to visualize user behavior patterns based on various features such as app usage time and screen on time.

#Steps Involved:
Data Loading: Load the mobile device usage dataset.
Data Preprocessing: Extract relevant features for analysis.
SOM Initialization: Set up the SOM with specified parameters.
Training: Train the SOM using the extracted data.
Visualization: Create visual representations of the SOM distance map and user behavior patterns.

#How to Run the Implementation
Download the dataset and place it in the same directory as the script, naming it user_behavior_dataset.csv.
Run the script using the following command:
python som_analysis.py

#Hardware Requirements
Any machine capable of running Python 3.x.
Minimum of 4GB RAM is recommended for efficient execution.

#Software Requirements
Python 3.x: The programming language used for implementing the analysis.
Libraries:
NumPy: A library for numerical operations and handling arrays.
Pandas: A library for data manipulation and analysis, particularly with data frames.
Matplotlib: A plotting library for creating visualizations.
MiniSom: A library specifically for creating and training Self-Organizing Maps.

#Author
Janaki Hari Kumar 22MIS1159
