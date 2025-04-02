# Avocado Toast Supply Chain Analysis

## 📌 Description
This project performs a supply chain analysis of the key ingredients used in preparing Avocado Toast: avocado, olive oil, sourdough bread, lemon, and salt flakes. The analysis is based on data extracted from Open Food Facts, an open food database containing information about the origins of food ingredients.

Through this analysis, we aim to understand the countries of origin for these ingredients and how they are distributed globally. This study highlights how seemingly simple foods can have diverse and complex origins.

## 🎯 Objective
The goal of this project is to perform data analysis on the following aspects:
- Identify the main countries of origin for Avocado Toast ingredients.
- Explore product categories and their respective origins.
- Visualize the geographic distribution of ingredients through charts.

## 🥑 Ingredients Analyzed
- Avocado  
- Olive Oil  
- Sourdough Bread  
- Lemon  
- Salt Flakes  

## 📂 Data
The data used in this project comes from Open Food Facts and is organized into CSV and TXT files containing information such as:
- Product name  
- Quantity  
- Serving size  
- Product categories  
- Countries of origin  
- Countries of sale  

Each ingredient has a corresponding CSV file, along with a TXT file containing relevant categories.

## 📁 Repository Structure
```
/data
  /avocado.csv
  /olive_oil.csv
  /sourdough.csv
  /lemon.csv
  /salt_flakes.csv
  /relevant_avocado_categories.txt
  /relevant_olive_oil_categories.txt
  /relevant_sourdough_categories.txt

/src
  analysis.py
  visualization.py

README.md
```

## 🚀 How to Run the Project

### Prerequisites
Ensure you have Python 3.6 or higher installed and the following libraries:  
- pandas  
- matplotlib  
- seaborn  
- numpy  

### Install Dependencies
Create a virtual environment (optional) and install the required dependencies:
```bash
pip install -r requirements.txt
```

### Run the Analysis
To execute the data analysis and visualization, run:
```bash
python src/analysis.py
```

### Generate Visualizations
After running the analysis, generate visualizations with:
```bash
python src/visualization.py
```

## 📊 Results
The analysis provides insights into:
- The **top 10 countries** where each ingredient is most commonly sourced from.
- The **distribution of ingredients by country**, offering a better understanding of global food trade and sourcing.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙌 Acknowledgments
- **Open Food Facts** for providing the open data used in this analysis.
- **Matplotlib and Seaborn** for the powerful data visualization tools.
