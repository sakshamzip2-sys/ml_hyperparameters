# Logistic Regression Playground (Streamlit App)


An interactive web application built with **Streamlit** and **scikit-learn** that allows users to experiment with different **Logistic Regression** parameters and instantly visualize their effects on classification.  

This tool is great for students, beginners, and ML enthusiasts who want to understand how parameters such as `C`, `penalty`, `solver`, and `max_iter` influence model behavior.

---

## Features
- Choose between **binary** and **multiclass** datasets.
- Adjust Logistic Regression parameters interactively:
  - `penalty` (`l1`, `l2`, `elasticnet`, `none`)
  - `C` (inverse regularization strength)
  - `solver` (`newton-cg`, `lbfgs`, `liblinear`, `sag`, `saga`)
  - `max_iter` (maximum iterations)
  - `multi_class` (`auto`, `ovr`, `multinomial`)
  - `l1_ratio`
- Visualize decision boundaries in real-time.
- Check model **accuracy score** for chosen settings.

---

## Installation

Clone this repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name 

Install required dependencies: pip install -r requirements.txt
Run the Streamlit app: streamlit run Logistic_Reg_Parameter.py
Open your browser at: http://localhost:8501/



