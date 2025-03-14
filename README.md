 # Log File Classification using DBSCAN and Regex

## Description
This project classifies log files using the DBSCAN clustering algorithm along with regular expressions (regex) for pattern recognition. It helps in identifying patterns and anomalies within log data, making it useful for log analysis and cybersecurity applications.

## Features
- Utilizes **DBSCAN** for clustering log entries.
- Uses **regular expressions (regex)** to extract meaningful patterns from log data.
- Helps in **identifying anomalies** in log files.
- Supports **automated log classification** for easier analysis.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python (>= 3.x)
- Jupyter Notebook (optional, if running in a notebook environment)
- Required Python libraries:
  ```sh
  pip install numpy pandas scikit-learn, sentence-transformer
  ```

## Usage
1. Load your log file into the script.
2. The regex patterns will extract meaningful features.
3. DBSCAN will cluster log entries based on the extracted patterns.
4. The output will show clustered log data and anomalies.

### Running the Script
If you are using Jupyter Notebook:
```sh
jupyter notebook newJupty.ipynb
```
If running as a Python script:
```sh
python newJupty.py
```

## Code Structure
### 1. Data Loading and Preprocessing
- The script first loads the log file into a structured format.
- Any necessary cleaning and formatting are applied to standardize the data.

### 2. Pattern Extraction with Regex
- Regular expressions are used to extract key components from log entries.
- This helps in identifying meaningful patterns within the logs.

### 3. Clustering with DBSCAN
- The extracted log patterns are processed using the **DBSCAN** algorithm.
- Logs with similar characteristics are grouped into clusters, while anomalies are marked as noise.

## Example Output
- Clustered logs grouped by similarity.
- Detected anomalies.

## Contribution
Feel free to contribute by submitting a pull request or opening an issue!

## License
This project is licensed under the MIT License.

## Contact
For any issues or suggestions, please open an issue on GitHub.

