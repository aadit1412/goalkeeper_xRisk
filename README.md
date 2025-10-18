# Goalkeeper Pass Risk Analysis

This repository presents a **data-driven approach to analyzing goalkeeper passes** in professional football, focusing on the **expected risk of each pass**. The analysis leverages **machine learning techniques** (XGBoost, Logistic Regression) to estimate the likelihood of a pass being unsuccessful, helping identify risky passing patterns and evaluate goalkeeper performance. The models have been trained on 2 full seasons of football: La Liga 2015/16 and Premier League 2015/16.

---

## Project Context

The project was designed to study **what makes a goalkeeper pass risky** and how pass features and match context influence success.  

Key aspects of the analysis include:

- Processing **event-level match data** to engineer features such as pass length, angle, match minute, and pressure
- Using **XGBoost and Logistic Regression models** to predict pass success probabilities
- Identifying **key drivers of pass risk** and visualizing risky zones on the pitch  
- Comparing goalkeeper performance based on **volume and success of risky passes** (La Liga and Premier League 2015/16)
- Creating **heatmaps and scatterplots** for tactical insights and player comparisons

The goal is to provide a **quantitative understanding of goalkeeper decision-making**, supporting tactical analysis and scouting.

---

## What's Included

- `expected_risk.ipynb`: Full notebook with feature engineering, model training, and visualizations  
- `expected_risk.py`: Clean Python script version of the workflow
- `xRisk_Images`: Visualisations
- `README.md`: Project overview and context

---

## Tools Used

- **Python** (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, XGBoost, mplsoccer)  
- **Event-level football data** (goalkeeper passes, match context)

---

## Future Work

- Explore **league comparisons and cross-season trends** (once I have access to enough data)
- Integrate **advanced spatial metrics** and more granular pressure/context features (scoreline, number of defenders pressing, exact height of pass etc.)
- Build **interactive dashboards** to explore goalkeeper risk patterns in real time (again, once I have access to enough data) 

---

## Contact

For discussions on football analytics, predictive modeling, or collaborations:

- [LinkedIn](https://www.linkedin.com/in/aaditpahuja)  
- 📧 aaditpahuja@gmail.com  
