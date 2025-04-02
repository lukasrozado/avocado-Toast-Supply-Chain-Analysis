# What's in an Avocado Toast: A Supply Chain Analysis

You find yourself in London, crafting a delectable avocado toast—a dish that has soared in popularity on breakfast menus since the 2010s. This straightforward recipe requires just five ingredients: a ripe avocado, half a lemon, a generous pinch of salt flakes, two slices of sourdough bread, and a good drizzle of extra virgin olive oil. Today, these ingredients are staples in grocery stores, but their journey to your plate is far from simple!

## Project Overview

In this project, you will conduct a supply chain analysis of three key ingredients used in avocado toast using the Open Food Facts database. This open database offers extensive, crowd-sourced information on various foods, including their origins. Through this analysis, you'll gain an in-depth understanding of the complex supply chain behind producing a single dish.

## Data Files

The data folder contains three pairs of files for each ingredient:
- **CSV files** (e.g., `avocado.csv`): Contain detailed data about each food item and its country of origin.
- **TXT files** (e.g., `relevant_avocado_categories.txt`): Include only the category tags of interest for that food.

### Key Points:
- **Data Filtering:** Many rows in the CSV files may include irrelevant data. You'll need to filter out rows based on values in the `categories_tags` column. Examples of relevant categories include fruits, vegetables, and fruit-based oils.
- **Multiple Tags:** Each data row can contain multiple category tags. The column `origins_tags` holds strings indicating the country of origin.
- **Outcome:** At the end of the project, you’ll have a refined list of ingredients along with their countries of origin, setting the stage for further analyses (e.g., exploring the average time these ingredients spend at sea).

## Technologies Used

- **Python** (pandas, matplotlib, seaborn, numpy)
- **Open Food Facts Database**

## How to Run the Project

1. **Install Dependencies:**  
   Ensure you have Python 3.6 or higher. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```

2. **Run the Analysis Script:**  
   Execute your data analysis script (e.g., `analysis.py` in the `src` folder):
   ```bash
   python src/analysis.py
   ```

3. **Generate Visualizations:**  
   Run the visualization script (e.g., `visualization.py` in the `src` folder) to view charts:
   ```bash
   python src/visualization.py
   ```

## Repository Structure

```
/data
    avocado.csv
    olive_oil.csv
    sourdough.csv
    lemon.csv
    salt_flakes.csv
    relevant_avocado_categories.txt
    relevant_olive_oil_categories.txt
    relevant_sourdough_categories.txt
/src
    analysis.py
    visualization.py
README.md
```

## Acknowledgments

- **Open Food Facts** for providing the open data.
- The developers of **pandas**, **matplotlib**, and **seaborn** for the robust data processing and visualization tools.
