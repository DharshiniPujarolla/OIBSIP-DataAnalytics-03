# Data Analytics – Customer Segmentation Analysis (iFood Marketing Dataset)

This project was completed as part of the **Oasis Infobyte Summer Internship Program (OIBSIP) – Data Analytics track**. It performs **customer segmentation analysis** on the **iFood marketing campaign dataset** to understand customer behavior and group customers based on purchasing patterns and demographics.

## 📌 Project Overview

The goal of this task is to analyze customer-level data from a marketing campaign and segment customers into meaningful groups for targeted marketing strategies. The notebook covers data exploration, preprocessing, and segmentation analysis on `ifood_df.csv`.

Typical steps covered in the notebook include:

- Loading and inspecting the `ifood_df.csv` dataset
- Exploring customer demographics (income, age, education, marital status, etc.)
- Analyzing spending behavior across product categories (wines, fruits, meat, fish, sweets, gold products)
- Examining campaign acceptance and response rates
- Studying purchase channels (web, catalog, store visits)
- Feature scaling/encoding in preparation for segmentation
- Applying clustering techniques (K-Means) to group customers into segments
- Visualizing and interpreting the resulting customer segments

## 🗂️ Repository Structure

```
OIBSIP-DataAnalytics-03/
├── ifood_df.csv      # iFood marketing campaign customer dataset
├── main.ipynb        # Jupyter Notebook containing the full segmentation analysis
└── README.md         # Project documentation
```

## 📊 Dataset

**ifood_df.csv** contains customer-level marketing data, including fields such as:

| Column | Description |
|---|---|
| `Income` | Customer's yearly household income |
| `Age` / `Year_Birth` | Customer age / birth year |
| `Education`, `Marital_Status` | Demographic details |
| `Kidhome`, `Teenhome` | Number of children/teenagers in the household |
| `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds` | Amount spent on each product category |
| `NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases` | Purchases made through different channels |
| `NumWebVisitsMonth` | Number of website visits per month |
| `AcceptedCmp1`–`AcceptedCmp5` | Whether the customer accepted each marketing campaign |
| `Response` | Whether the customer responded to the most recent campaign |

## 🛠️ Tools & Libraries Used

- **Python 3**
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – feature scaling and clustering (e.g., K-Means)
- **Jupyter Notebook** – interactive analysis environment

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3 installed along with the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/DharshiniPujarolla/OIBSIP-DataAnalytics-03.git
   cd OIBSIP-DataAnalytics-03
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
3. Run the cells sequentially to reproduce the analysis.

## 📈 Key Insights

The notebook explores questions such as:

- What demographic and income patterns distinguish high-value customers?
- Which product categories drive the most spending, and for which customer groups?
- How do purchase channel preferences (web, catalog, store) vary across segments?
- Which customers are most likely to respond to marketing campaigns?
- What distinct customer segments emerge from clustering, and how can they inform targeted marketing?

*(Refer to `main.ipynb` for the detailed analysis, clustering results, and visualizations.)*

## 🎯 About OIBSIP

This project is part of the **Oasis Infobyte Internship Program**, where interns complete hands-on data analytics tasks to strengthen practical, real-world data skills.

## 👩‍💻 Author

**Dharshini Pujarolla**
GitHub: [@DharshiniPujarolla](https://github.com/DharshiniPujarolla)

## 📄 License

This project is open-source and available for learning purposes.
