🌍 CIS2300 Final Project – Disaster Data Analysis
📘 Overview

This project, developed for the CIS2300 course at Baruch College, leverages the EM-DAT (Emergency Events Database) to analyze global disaster data. The dataset includes records of over 27,000 disasters worldwide from 1900 to the present, focusing on events that required external assistance (emdat.be
).

📁 Project Structure

CynthiaChin_CIS2300_FinalProject.ipynb: Jupyter Notebook containing the data analysis and visualization code.

emdat_disasters.xlsx: Excel file sourced from the EM-DAT database, detailing disaster events and impacts.

📊 Dataset Details

The emdat_disasters.xlsx file includes the following columns:

DisNo: Unique disaster identifier.

Year: Year of the disaster.

Country: Affected country.

Disaster Type: Classification of the disaster (e.g., flood, earthquake).

Total Deaths: Number of fatalities.

Total Affected: Number of affected individuals.

Start Date: Date the disaster began.

End Date: Date the disaster ended.

For a full description of all columns, refer to the EM-DAT documentation (doc.emdat.be
).

🛠️ Setup Instructions

Clone the repository:

git clone https://github.com/Cynthia-Chin/CIS2300-final-project.git
cd CIS2300-final-project


Make sure you have Python 3 and Jupyter Notebook installed. You will also need the following Python libraries (install if not already installed):

pip install pandas matplotlib seaborn openpyxl


Launch Jupyter Notebook:

jupyter notebook


Open CynthiaChin_CIS2300_FinalProject.ipynb and run the cells to execute the analysis.

📈 Analysis Highlights

The notebook demonstrates how to:

Load and preprocess disaster data from the Excel file.

Perform exploratory data analysis (EDA) to identify trends and patterns.

Visualize findings using charts and graphs.

📄 License

This project is licensed under the MIT License.
