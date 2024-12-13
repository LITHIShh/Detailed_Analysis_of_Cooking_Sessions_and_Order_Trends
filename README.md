# Detailed Analysis of Cooking Sessions and Order Trends

## Overview
This project analyzes user behaviors, cooking session preferences, and order trends by merging and processing multiple datasets. The insights derived can help businesses optimize their services and cater to customer needs effectively. The analysis is supported by Python code, visualizations, and a comprehensive report.

---

## Files in the Project

### 1. **Data File**
   - **Name**: `Assignment` 
   - **Description**: Contains information about users, cooking sessions, and order details.
   - **Key Columns**:
     - `user_id`: Unique identifier for each user.
     - `session_id`: Unique identifier for each cooking session.
     - `dish_name`: Name of the dish cooked or ordered.
     - Additional demographic and activity data.

---

### 2. **Notebook File**
   - **Name**: `main.ipynb`
   - **Description**: Jupyter Notebook containing the Python code for data processing, merging, analysis, and visualization.
   - **Key Sections**:
     1. Data Loading and Cleaning.
     2. Merging `UserDetails`, `CookingSessions`, and `OrderDetails`.
     3. Exploratory Data Analysis (EDA).
     4. Insights and Recommendations.

---

### 3. **Converted PDF of Notebook**
   - **Name**: `main_ipynb_pdf_version.pdf`
   - **Description**: A PDF version of the Jupyter Notebook, suitable for sharing or offline viewing.
   - **Purpose**: To provide a readable format of the code and analysis for stakeholders.

---

### 4. **PDF Report**
   - **Name**: `Detailed Report on Analysis of Cooking Sessions and Order Trends.pdf`
   - **Description**: A detailed report summarizing findings, insights, and recommendations based on the analysis.
   - **Sections**:
     - Popular Dishes
     - User Demographics
     - Correlation Between Cooking Sessions and Orders
     - Key Business Recommendations

---

### 5. **Word File**
   - **Name**: `Detailed Report on Analysis of Cooking Sessions and Order Trends.docx`
   - **Description**: Editable version of the PDF report for further modifications or presentations.

---

## How to Use

1. **Run the Analysis Notebook**:
   - Open `main.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Install dependencies using `pip install -r requirements.txt` (if required).
   - Execute the cells sequentially to reproduce the analysis and visualizations.

2. **Review the Outputs**:
   - Refer to `main_ipynb_pdf_version.pdf` for a PDF version of the notebook.
   - Use `Detailed Report on Analysis of Cooking Sessions and Order Trends.pdf.pdf` or `Detailed Report on Analysis of Cooking Sessions and Order Trends.pdf.docx` for a detailed summary of insights and recommendations.

3. **Explore the Data**:
   - Load the provided `Assignment.csv` file in any tool of your choice (Excel, Python, etc.) to explore the raw data used for analysis.

---

## Key Insights

- **Top Dishes**: Popular items cooked and ordered, including Spaghetti and Grilled Chicken.
- **Demographics**: Age-based meal preferences and user activity trends.
- **Engagement**: A strong correlation between cooking sessions and order frequency.
- **Business Recommendations**: Strategies to enhance user engagement, improve loyalty, and boost revenue.

---

## Dependencies

- **Python Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `jupyter`

Install all dependencies via:
```bash
pip install -r requirements.txt
