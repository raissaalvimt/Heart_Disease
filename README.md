Heart Disease Dataset Repository

📂 Dataset Overview
This repository contains data related to heart disease, widely used in research for developing Machine Learning models. The dataset comprises 76 attributes, although most published experiments utilize a subset of 14 attributes.

The primary dataset within this repository is the Cleveland database, the most extensively used dataset by Machine Learning researchers. The "goal" field denotes the presence of heart disease in a patient, with integer values ranging from 0 (no presence) to 4 (varying degrees of presence).
Most studies focus on simplifying this into a binary classification:

0: Absence of heart disease
1, 2, 3, 4: Presence of heart disease
📋 Additional Information
Data Anonymization: Names and social security numbers of the patients have been removed and replaced with dummy values.
Files:
A single processed file contains the Cleveland database.
Four unprocessed files are also available in this repository.
For more information on costs related to this dataset, refer to the "Costs" folder.

📝 Missing Values
The dataset contains missing values. Ensure appropriate preprocessing steps are applied before analysis.

📂 Repository Contents
Here is an overview of the key files and directories in this repository:

cleveland.data: The processed Cleveland database.
hungarian.data, long-beach-va.data, switzerland.data: Additional unprocessed datasets.
Costs/: A directory containing details on test costs, including:
heart-disease.cost: Individual test costs in Canadian dollars (source: Ontario Health Insurance Program fee schedule).
heart-disease.delay: Test result timing (immediate or delayed).
heart-disease.expense: Full and discounted costs for groups of tests.
heart-disease.group: Shared costs among grouped tests.
README.md: This document.
heart-disease.names: Attribute documentation.

💡 Usage
1. How to Use the Dataset

2. Clone the repository: git clone https://github.com/raissaalvimt/Heart-Disease.git

3. Load the data in your preferred programming environment (e.g., Python, R).
  
4. Perform exploratory data analysis and preprocessing to handle missing values and other data inconsistencies.


📜 License
This dataset is shared for educational and research purposes. Ensure compliance with any relevant ethical guidelines and attributions when using this data.
