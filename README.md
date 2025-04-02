# Avocado Toast Supply Chain Analysis

## Description

This project performs a supply chain analysis of three main ingredients used in preparing **Avocado Toast**: avocado, olive oil, and sourdough bread. The analysis is based on data extracted from **Open Food Facts**, an open food database containing information about the origins of food ingredients.

Through this analysis, we aim to understand the countries of origin for these ingredients and how they are distributed globally. This study provides an opportunity to explore how seemingly simple foods can have diverse and complex origins.

## Objective

The goal of this project is to perform a data analysis on the following points:

- Identify the main countries of origin for the ingredients used in Avocado Toast.
- Explore the product categories and their origins.
- Visualize the geographic distribution of ingredients through charts.

## Ingredients Analyzed

1. **Avocado**  
2. **Olive Oil**
3. **Sourdough Bread**  
4. **Lemon**  
5. **Salt Flakes**

## Data

The data used in this project comes from **Open Food Facts** and is organized into CSV and TXT files containing information about the products, such as:

- Product name
- Quantity
- Serving size
- Product categories
- Countries of origin
- Countries of sale

The project uses the CSV file for each ingredient, along with a TXT file containing relevant categories for each one.

## Repository Structure

/data /avocado.csv /olive_oil.csv /sourdough.csv /lemon.csv /salt_flakes.csv /relevant_avocado_categories.txt /relevant_olive_oil_categories.txt /relevant_sourdough_categories.txt /src analysis.py visualization.py README.md

markdown
Copy

## How to Run the Project

### Prerequisites

- Python 3.6 or higher
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - numpy

### Install Dependencies

Create a virtual environment (optional) and install the dependencies:

```bash
pip install -r requirements.txt
Run the Analysis
To run the analysis and data visualization, simply execute the analysis.py script:

bash
Copy
python src/analysis.py
Visualization
After running the analysis, you can generate visualizations using the visualization.py script:

bash
Copy
python src/visualization.py
Results
The analysis will generate insights into:

The top 10 countries where each ingredient is most commonly sourced from.

The distribution of ingredients by country, allowing for a better understanding of global food trade and sourcing.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Open Food Facts for providing the open data used in this analysis.

Matplotlib and Seaborn for the powerful data visualization tools.

vbnet
Copy

This English version reflects the same structure as the Portuguese one, ensuring consistency 