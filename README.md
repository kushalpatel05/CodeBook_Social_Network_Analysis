# CodeBook Social Network Analysis

This repository contains a data science project analyzing user data from "CodeBook – The Social Media for Coders." The primary goal of this project is to process, clean, and extract meaningful insights from a user dataset using only standard Python libraries.

## 📝 Project Overview

This project is divided into four main parts, simulating a data science internship task:

1.  **Data Loading and Exploration**: The initial step involves loading user and page data from a JSON file and displaying it in a structured format.
2.  **Data Cleaning**: This part addresses common data issues such as missing values, duplicate entries, and inactive user profiles to ensure data quality.
3.  **"People You May Know" Feature**: A recommendation algorithm to suggest potential friends to a user based on the number of mutual connections.
4.  **"Pages You Might Like" Feature**: A recommendation system that suggests pages to a user based on the pages liked by other users with similar interests.

## 🚀 Technologies Used

* **Language:** Python 3
* **Libraries:** `json` (standard library)

## 🛠️ How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/CodeBook-Social-Network-Analysis.git](https://github.com/your-username/CodeBook-Social-Network-Analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd CodeBook-Social-Network-Analysis
    ```
3.  **Place your data files** (`original_data.json`, `messy_data.json`) inside a `data` directory.

4.  **Open and run the Jupyter Notebook:**
    ```bash
    jupyter notebook Codebook_Analysis.ipynb
    ```

## 📂 File Structure

* `Codebook_Analysis.ipynb`: The main Jupyter Notebook containing all the Python code and analysis.
* `data/`: A directory to store the JSON data files.
* `README.md`: This file.
