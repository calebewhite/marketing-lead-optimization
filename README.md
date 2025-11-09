# 🧠 Predictive Lead Scoring — Turning a -$607 Loss into a $191 Profit

## 📋 Overview
This project demonstrates how predictive modeling can improve marketing ROI.  
I analyzed a marketing campaign dataset to identify the characteristics of ideal leads and build a machine learning model to predict response probability.  
Using this model to select a subset of leads turned a full campaign that lost **$607** into one that would have made **a $191 profit**.

---

## 🎯 Business Problem
Marketing teams often send campaigns to large audiences without knowing who will respond.  
The goal of this project was to:
- Identify which customer attributes drive response.  
- Build a predictive model to score leads.  
- Optimize campaign selection to maximize profit and ROI.

---

## 🧾 Data
- **Source:** [Kaggle Marketing Campaign Dataset](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)  
- **Size:** 2,240 records, 28 features  
- **Key Variables:** Recency, Income, Spending, Campaign Response  

---

## 🛠️ Tools & Methods
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Scikit-optimize, XGBoost  
- **Techniques:** Exploratory Data Analysis, Feature Engineering, Classification Modeling, ROI Simulation

---

## 🧩 Process

1. **Exploration:**  
   - Analyzed demographics across responders and non-responders.  

2. **Feature Engineering:**  
   - Created total spend and response features to capture engagement and customer value.  

3. **Modeling:**  
   - Trained an XGBoost classifier to predict campaign response.  

4. **Selection Optimization:**  
   - Ranked leads by predicted probability and simulated targeting different subsets of the population.  

5. **Evaluation:**  
   - Compared full-campaign results with model-based targeting to calculate profitability.

---

## 📈 Results

| Metric | Full Campaign | Model-Selected Subset |
|--------|----------------|----------------|
| Net Profit | **-$607** | **+$191** |
| ROI | -45% | +104% |
| Response Rate | 15% | 56% |

**Key Insight:** Predictive lead scoring improved profitability by approximately **130%** by mailing to the top 20% of predicted responders instead of the full list.

---

## 💡 Takeaways
- Predictive modeling can transform underperforming campaigns into profitable ones.  
- Even modest targeting improves ROI and reduces wasted marketing spend.  
- The same workflow can be adapted for email, digital ads, or direct mail campaigns.  

---

## 🧱 Next Steps
- Integrate cost-sensitive learning for better budget optimization.  
- Automate model retraining with new campaign data.  
- Extend to multi-channel marketing analysis.

---

## 📓 Notebook
👉 [View the full Jupyter Notebook](notebooks/lead_scoring.ipynb)

---

## 🧰 Tech Stack
Python • Scikit-learn • Pandas • Matplotlib • XGBoost • Jupyter Notebook  

---

## 👤 Author
**Caleb White**  
📫 [LinkedIn](https://linkedin.com/in/your-linkedin) • [GitHub](https://github.com/yourusername)

Notebook

👉 View the full Jupyter Notebook
