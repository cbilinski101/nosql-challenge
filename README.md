# NoSQL Analysis Project

![MongoDB](https://img.shields.io/badge/Powered_by-MongoClient-green?style=flat&logo=mongodb)
![Pandas](https://img.shields.io/badge/Powered_by-pandas-blue?style=flat&logo=pandas)
![JSON](https://img.shields.io/badge/Powered_by-JSON-lightgrey?style=flat&logo=json)
![VSCode](https://img.shields.io/badge/Developed_with-VSCode-blue?style=flat&logo=visualstudiocode)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Powered_by-Jupyter-orange?style=flat&logo=jupyter)

## Overview
This challenge involves setting up and analyzing a NoSQL database to help the editors of the food magazine *Eat Safe, Love* evaluate food hygiene ratings across the United Kingdom. The insights gained will assist their journalists and critics in planning future articles.

This project includes starter notebooks for working with NoSQL databases, specifically aimed at analyzing and setting up NoSQL databases for various use cases.

## Insights

**What are the top 5 establishments with a `RatingValue` rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?**

![image](https://github.com/user-attachments/assets/612e5fb6-5e57-4ec7-8dcf-f3583af1db39)
![image](https://github.com/user-attachments/assets/48d160e8-a326-46df-b46f-37b7c4b62057)

**How many establishments in each Local Authority area have a hygiene score of 0?**

![image](https://github.com/user-attachments/assets/0e96d803-3bff-46cc-8bba-c875d8640ccd)
![image](https://github.com/user-attachments/assets/c7c5f64a-6745-4970-9962-503aaec64e54)

## Project Files

- **NoSQL_analysis_starter.ipynb**: A Jupyter Notebook designed to help you analyze data stored in NoSQL databases. It provides an outline and examples for querying and interpreting data.
- **NoSQL_setup_starter.ipynb**: A Jupyter Notebook aimed at guiding the setup process for NoSQL databases. It includes code snippets and instructions for creating and managing collections, documents, and other NoSQL features.

## Features

- **Data Analysis**: Tools and examples for querying NoSQL data, filtering results, and generating insights.
- **Database Setup**: Step-by-step instructions for setting up collections, inserting documents, and managing indices.
- **Flexibility**: Designed for compatibility with various NoSQL databases, including MongoDB, Cassandra, and others.

## Requirements

- Python 3.8 or later
- Jupyter Notebook
- NoSQL database driver (e.g., `pymongo` for MongoDB)
- Dependencies as listed in the notebooks

## Usage

### Using Visual Studio Code

1. Open the project in Visual Studio Code:
    ```bash
    code .
    ```
2. Install the recommended extensions for a smoother experience:
    - **Python**: For running Jupyter Notebooks and Python scripts.
    - **Jupyter**: To work directly with `.ipynb` files within VSCode.
3. Open the desired notebook file (`NoSQL_analysis_starter.ipynb` or `NoSQL_setup_starter.ipynb`) directly in VSCode.
4. Use the integrated terminal in VSCode to install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Run the cells directly in VSCode or launch a Jupyter server if needed.

### General Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/cbilinski101/nosql-challenge.git
    ```
2. Navigate to the project directory:
    ```bash
    cd NoSQL-Project
    ```
3. Install required dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebooks:
    ```bash
    jupyter notebook
    ```
5. Run the appropriate notebook based on your task:
    - **Setup**: Use `NoSQL_setup_starter.ipynb`.
    - **Analysis**: Use `NoSQL_analysis_starter.ipynb`.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was developed with the assistance of the following resources:

- **Turtoring Session** – Provided guidance on data analysis.
- **Xpert Learning Assistant** – Provided guidance on and data analysis.
- **GitLab UofT Activities** – Supplied foundational activities and exercises for analysis.
- **ChatGPT** – Assisted with code, explanations, and README formatting. 
