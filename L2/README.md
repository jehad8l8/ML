## Lab 02

### 1. Dataset Selection
- **Dataset Name:** House Prices Dataset (Ames Housing)
- **Source:** Open dataset (Ames, Iowa)
- **Data Format:** CSV
- **Description:**  
  The dataset contains detailed information about residential properties in Ames, Iowa.  
  It includes a mix of **numerical** and **categorical** attributes such as lot size, neighborhood, house style, overall quality, year built, and other structural and location-based features relevant to housing valuation.

---

### 2. Problem Definition
Based on an initial inspection of the dataset, the machine learning problem is defined as follows:

- **Problem Type:** Regression  
- **Reasoning:**  
  The objective is to predict a **continuous numerical value**, which is the sale price of a house, rather than assigning it to predefined categories.
- **Target Variable:** `SalePrice`  
- **Description:**  
  The final selling price of a residential property.
- **Goal:**  
  The model aims to learn the relationship between property characteristics and housing prices in order to accurately estimate the sale price of unseen homes.

---

### 3. Problem Description
The purpose of this lab is to develop an understanding of how housing features influence property prices and how these relationships can be modeled using machine learning techniques.

Using housing data collected from the city of Ames, Iowa, the dataset provides a comprehensive view of residential properties, including physical attributes (e.g., lot area, overall quality, year built), architectural style, and neighborhood-related factors.

The primary objective is to analyze these features and determine how effectively they can be used to predict a house’s sale price. This type of analysis is commonly applied in real-world scenarios such as real estate valuation, market analysis, and decision support systems.

---

### 4. Data Loading & Initial Inspection
The dataset was loaded into a **Jupyter Notebook** using the **Pandas** library.  
Initial data inspection steps included:
- Examining the dataset’s dimensions (number of rows and columns)
- Previewing the first few records
- Reviewing column names and data types  

These steps were performed to gain a clear understanding of the dataset structure before proceeding to preprocessing and exploratory data analysis.

📓 **Notebook:** [Jupyter Notebook](JupyterDataset.ipynb)
