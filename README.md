# **Sales Trend Analysis: Insights and Predictions**

## **Project Overview**
This project analyzes the `Sample Supermarket Sales` dataset to uncover actionable insights and enhance business decision-making. The analysis employs techniques in data cleaning, exploratory data analysis (EDA), statistical evaluation, and predictive modeling. By identifying key trends and relationships within the data, this project provides strategic recommendations for improving profitability and operational efficiency.

## **Key Objectives**
- Identify the most profitable regions and categories.
- Quantify the impact of discounts on profitability.
- Explore relationships between sales, profit, and discounts.
- Develop predictive models to forecast profitability and sales.

## **Technologies and Tools Used**
- **Python**: For data analysis and visualization.
- **Libraries**:
  - `Pandas`: Data manipulation and cleaning.
  - `Matplotlib` & `Seaborn`: Data visualization.
  - `Scikit-Learn`: Predictive modeling.

## **Dataset**
The dataset contains 9,994 rows and 13 columns, including:
- **Numerical Features**: `Sales`, `Profit`, `Discount`.
- **Categorical Features**: `Region`, `Category`, `Sub-Category`, and more.
- **Source**: [Kaggle - Sample Supermarket Sales Dataset](https://www.kaggle.com/bravehart101/sample-supermarket-dataset).

## **Key Findings**
### **General Metrics**
- **Total Sales**: `$2,296,195.59`
- **Total Profit**: `$286,241.42`
- **Average Discount**: `15.63%`

### **Regional Performance**
| **Region**   | **Sales**       | **Profit**      |
|--------------|-----------------|-----------------|
| West         | $725,255.64     | $108,329.81     |
| East         | $678,435.20     | $91,506.31      |
| Central      | $500,782.85     | $39,655.88      |
| South        | $391,721.91     | $46,749.43      |

- The **West region** generated the highest profit (`$108,329.81`) and sales (`$725,255.64`).
- The **Central region** recorded the lowest profit (`$39,655.88`) despite significant sales.

### **Category Insights**
| **Category**       | **Sales**       | **Profit**      |
|--------------------|-----------------|-----------------|
| Technology         | $836,154.03     | $145,454.95     |
| Office Supplies    | $718,735.24     | $122,364.66     |
| Furniture          | $741,306.31     | $18,421.81      |

- **Technology** was the most profitable category with `$145,454.95` in profit.
- **Furniture** had high sales but low profitability, indicating inefficiencies.

### **Impact of Discounts**
- **Discounts negatively correlated with profit** (`-0.22`).
- Discounts above `20%` often resulted in losses.

### **Predictive Modeling**
1. **Linear Regression**:
   - **Mean Squared Error (MSE):** `344,656.87`
2. **Random Forest Classifier**:
   - **Accuracy:** `93.34%`

## **Visualizations**
- **Sales and Profit by Region** (Bar Chart)
- **Sales and Profit by Category** (Bar Chart)
- **Correlation Heatmap**
- **Discount vs Profit** (Scatter Plot)

All visualizations are embedded in the accompanying Jupyter Notebook.

## **Recommendations**
1. **Focus on the West Region**:
   - Allocate additional resources to this highly profitable region.
2. **Refine Discount Strategies**:
   - Avoid discounts exceeding `20%` to maintain profitability.
3. **Enhance Furniture Margins**:
   - Investigate pricing, production costs, and discounts.
4. **Prioritize Technology Products**:
   - Invest in this consistently high-performing category.


## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/sales-trend-analysis.git
2. Native to the project directory:
    cd sales-trend-analysis
3. Install required Python Libraries:
   pip install -r requirements.txt
4. Open the Jupyter Notebook:
   jupyter notebook notebooks/sales_analysis.ipynb

## **License**
This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/).

### **What This Means:**
1. **You Are Free To:**
   - **Use** the project for personal or commercial purposes.
   - **Share** the project (e.g., redistribute it) in its original, unmodified form.

2. **You Cannot:**
   - **Modify** the project, including creating derivative works.
   - **Use** the project in a way that suggests endorsement by the original author.

3. **Attribution Required:**
   - You must give appropriate credit to the author.
   - Provide a link to the license in any shared copies of the work.

4. **No Warranty or Liability:**
   - The project is provided \"as is\" without any warranties.
   - The author is not liable for any damages or issues arising from the use of the project.

### **Why This License?**
This license ensures that the project can be freely used and shared while protecting the original work from unauthorized modifications. It is ideal for individuals who want to maintain the integrity of their work while allowing others to benefit from it.

