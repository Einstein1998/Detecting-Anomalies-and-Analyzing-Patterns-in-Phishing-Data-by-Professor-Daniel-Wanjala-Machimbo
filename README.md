# Detecting-Anomalies-and-Analyzing-Patterns-in-Phishing-Data-by-Professor-Daniel-Wanjala-Machimbo
# PhishScore Analyzer

The PhishScore Analyzer is a project aimed at analyzing and gaining insights from a dataset containing phishing-related information. By performing various analyses and applying anomaly detection techniques, the project aims to uncover trends, patterns, and anomalies in the data.

## Dataset

The dataset used for analysis is stored in a CSV file named `phish_score.csv`. It contains the following columns:

- `date`: Date and time of the recorded event.
- `Score`: PhishScore assigned to the event.
- `url`: URL associated with the event.
- `ip`: IP address associated with the event.

## Project Structure

The project consists of the following files:

- `phish_score.csv`: The dataset file in CSV format.
- `PhishScore_Analyzer.ipynb`: Jupyter Notebook containing the code for data analysis and visualization.
- `README.md`: This file, providing an overview of the project and instructions.

## Dependencies

The following dependencies are required to run the code in the Jupyter Notebook:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ipaddress (for IP analysis)

Install the necessary dependencies using pip:


## Usage

To use the PhishScore Analyzer, follow these steps:

1. Clone the repository or download the project files.
2. Ensure that you have the required dependencies installed.
3. Open the `PhishScore_Analyzer.ipynb` file in Jupyter Notebook.
4. Update the file path in the code to point to the `phish_score.csv` file if necessary.
5. Run the code cells in the Jupyter Notebook to perform the analyses and visualize the results.

## Results

The project provides several analyses and visualizations, including:

- Time-based Analysis: Trends and patterns over time, average scores for different intervals.
- Score Analysis: Distribution of scores, statistical measures, histograms, and box plots.
- URL Analysis: Most frequent URLs, categorization based on patterns or keywords.
- IP Analysis: Geolocation analysis, geographic distribution of IP addresses.
- Anomaly Detection: Identification of unusual patterns or outliers in scores, URLs, or IP addresses.

The results provide valuable insights into phishing activities and aid in the detection and prevention of phishing attempts.

