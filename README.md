# Root README.md

# Predicting Consumer Satisfaction in the Post-Pandemic Era

## 📚 Project Overview

This repository contains all materials for our final project in **STATS201 Machine Learning for Social Science (Spring 2025)** at Duke Kunshan University. The project focuses on predicting **consumer satisfaction** using an **e-commerce customer behavior dataset** sourced from Kaggle. 

Using a **logistic regression** model, we explore how transaction and demographic features influence satisfaction in the **post-pandemic** digital retail landscape. Our work includes **data preprocessing, model building, evaluation, and visualizations**, with applications in **business strategy, public policy, and ethical AI governance**.

---

## 📂 Repository Structure

```
ConsumerBehavior_PostPandemic/
├── code/
│   ├── README.md                           # Code description
│   ├── stats201_final.ipynb                # Full analysis in Jupyter Notebook
│   └── stats201_final.py                   # Full analysis in Python
├── data/
│   ├── ecommerce_customer_behavior.csv     # Raw dataset from Kaggle
│   └── README.md                           # Data dictionary and description
├── visualizations/
│   ├── Project Workflow Flowchart.png      # Figure 1: Project Workflow Flowchart
│   ├── confusion_matrix.png                # Figure 2: Confusion Matrix
│   ├── roc_curve.png                       # Figure 3: ROC Curve
│   └── feature_importance.png              # Figure 4: Feature Importance
├── docs/
│   └── Final_Project_Report.pdf            # Final academic report
├── requirements.txt                        # Required dependencies
└── README.md                               # Root README (this file)
```

---

## 🛠 Setup and Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/ConsumerBehavior_PostPandemic.git
   cd ConsumerBehavior_PostPandemic
   ```

2. **Create a Virtual Environment (Optional):**

   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

- **Jupyter Notebook:**  
  Run the full analysis interactively in:

  ```bash
  jupyter notebook
  ```

  Then open:

  ```
  code/stats201_final.ipynb
  ```

- **Python Script:**  
  Alternatively, execute:
  
  ```bash
  python code/stats201_final.py
  ```

---

## 📊 Poster

For a demonstration of our analysis and results:

- **Poster:** [View Poster](https://docs.google.com/presentation/d/1OPPqAaMMQvAm-oTtG3Yc7NHvv0OaPV6NeV-60rAdqhA/edit?usp=sharing)

---

## 📝 Supplementary Materials

Additional materials, including data preprocessing steps and discussions of alternative methods (see Appendix in the final report), can be found in the `docs/` folder.

---

## 👥 Authors and Acknowledgments

- **Authors:** Mohamed Sami Koudir
- **Acknowledgments:** Special thanks to **Professor Luyao Zhang**, classmates, and the **open-source community** for their invaluable contributions.

---

## 📚 License

This project is licensed under the [MIT License](LICENSE).

---

# data/README.md

# 📊 E-commerce Customer Behavior Dataset

## 📖 Overview

This dataset contains e-commerce transaction data, capturing **customer demographics, spending patterns, and satisfaction levels**. It is sourced from **Kaggle** and used to analyze **consumer behavior trends** in the post-pandemic era.

## 📃 Data Dictionary

| Variable                 | Type    | Description                                                           |
|--------------------------|---------|-----------------------------------------------------------------------|
| Customer ID              | Integer | Unique identifier for each customer                                  |
| Gender                   | String  | Gender of the customer (e.g., "Female", "Male")                      |
| Age                      | Integer | Age of the customer                                                  |
| City                     | String  | City of residence                                                    |
| Membership Type          | String  | Membership tier (Gold, Silver, Bronze)                               |
| Total Spend              | Float   | Total amount spent by the customer                                  |
| Items Purchased          | Integer | Number of items purchased                                           |
| Average Rating           | Float   | Average rating given by the customer                                |
| Discount Applied         | Boolean | Whether a discount was applied (True/False)                         |
| Days Since Last Purchase | Integer | Number of days since the last purchase                              |
| Satisfaction Level       | String  | Customer satisfaction ("Satisfied", "Neutral", "Unsatisfied")        |

## 🔒 Purpose

This dataset is used to **train a machine learning model** that predicts **consumer satisfaction** based on **transactional and demographic data**.

---

# visualizations/README.md

# 📊 Visualizations

This folder contains all **figures and charts** generated from the analysis of consumer satisfaction.

## 📸 Included Visualizations

- **confusion_matrix.png:**  
  - Heatmap of the confusion matrix showing classification performance.
  
- **roc_curve.png:**  
  - Receiver Operating Characteristic (ROC) curve evaluating model sensitivity vs. specificity.
  
- **feature_importance.png:**  
  - Bar chart of logistic regression coefficients, highlighting feature importance.

---

# requirements.txt

```plaintext
pandas==1.5.3
numpy==1.23.5
scikit-learn==1.2.2
matplotlib==3.6.2
seaborn==0.12.2
jupyter==1.0.0
```

---

# code/README.md

# 📑 Code Overview

This folder contains the **machine learning scripts** used for consumer satisfaction prediction.

## 📝 Scripts

- **stats201_final.ipynb**  
  - Jupyter Notebook with **full analysis**, including:
    - Data loading & preprocessing
    - Model training & evaluation
    - Visualizations (Confusion Matrix, ROC Curve, Feature Importance)

- **stats201_final.py** 
  - Python script version of the analysis.

## 🔧 How to Run

- **Run Jupyter Notebook:**  
  ```bash
  jupyter notebook
  ```
  Open `code/consumer_behavior_prediction.ipynb` and execute cells.

- **Run Python Script:**  
  ```bash
  python code/model_analysis.py
  ```

## 🛠 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
