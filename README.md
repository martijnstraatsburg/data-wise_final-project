# Data Wise Minor - Collaborative Data Project

This repository contains the resources and scripts for a "Search Keyword Clustering for Enhanced Search Optimization". It is designed to improve search functionality within article content databases by developing a solution that clusters related search keywords based on their semantic similarities and analyzing ways to distinguish multiple topics.

Below is an overview of the structure and functionality of the repository.

## Repository Structure

```
.
├── data/              # Directory for storing raw and processed data (empty due to privacy restrictions)
├── model/             # Directory containing the trained Word2Vec model
├── extract-data.sql   # SQL script for data extraction
├── pipeline.ipynb     # Jupyter Notebook for the data processing pipeline
├── README.md          # This file innit
```

### Contents of Folders and Files

- **`data/`**: This folder is meant to store the raw data and processed datasets used in this project. For privacy reasons, this folder is currently empty. Please ensure data confidentiality by not uploading sensitive information to this folder.

- **`model/`**: Contains the trained Word2Vec model, which is used for clusters related search keywords based on their semantic similarities.

- **`extract-data.sql`**: An SQL script to extract the required data from a database. Adjust database connection details and queries as needed.

- **`pipeline.ipynb`**: A Jupyter Notebook that outlines the data processing pipeline. This includes steps such as data cleaning, feature engineering, and model training. The notebook uses the Word2Vec model stored in the `model/` folder.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries listed in `pipeline.ipynb` (e.g., pandas, gensim, etc.)
- A database to run the `extract-data.sql` script
- Sufficient system resources to train and load Word2Vec models

## Getting Started

1. **Set Up Environment**:
   - Clone this repository.
   - Install the required Python libraries. A virtual environment is recommended.

2. **Prepare Data**:
   - Place your datasets in the `data/` folder.
   - Run `extract-data.sql` on your database to extract the necessary data.

3. **Run the Pipeline**:
   - Open `pipeline.ipynb` in Jupyter Notebook.
   - Follow the step-by-step instructions to process the data and train the Word2Vec model.

4. **Model Usage**:
   - The trained Word2Vec model in `model/` can be loaded using `gensim` for various applications.

## Notes

- The `data/` folder is excluded to maintain privacy. Ensure any data added to this folder complies with data protection policies.
- If you encounter any issues, please check dependencies or consult the comments in `pipeline.ipynb`.

## Contributions

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.