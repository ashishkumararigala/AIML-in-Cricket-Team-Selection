🏏 AI-Driven Team Selection in Professional Cricket
MSc Dissertation – University of Limerick (2025)
This project explores how Artificial Intelligence (AI) and Machine Learning (ML) can improve cricket team selection and player performance prediction compared to traditional selector-based methods.
📌 Overview
•	Developed ML and Deep Learning models to predict player performance and recommend optimal team compositions.
•	Applied feature engineering to define performance indices:
o	Batting Impact → weighted score of runs, strike rate, and consistency.
o	Bowling Impact → wickets, economy rate, and match context.
o	All-Round Index → balanced score for all-rounders.
•	Compared AI-driven predictions with historical human-based selections.
📊 Dataset
•	Source: ESPNcricinfo & ICC
•	Size: 18,000+ player-match instances after preprocessing
•	Features: Batting averages, strike rates, wickets, economy, venue, opposition, match type
•	Target Variable: Player selection impact score
🛠️ Methodology
1.	Data Preprocessing: Cleaning, normalization, feature engineering.
2.	Model Training:
o	Random Forest
o	Support Vector Machine (SVM)
o	XGBoost
o	Deep Q-Learning (for reinforcement-based strategy optimization)
3.	Evaluation Metrics: Accuracy, precision, recall, and match outcome correlation.
🚀 Key Results
•	AI-driven models achieved 85–90% prediction accuracy, vs 65–70% for traditional selectors.
•	Improved correct player selection by ~20%.
•	Reduced injury-related dropouts by ~30% using predictive workload monitoring.
🔑 Contributions
•	Developed a data-driven framework for cricket team selection.
•	Reduced human bias in selection.
•	Provided decision-support insights for coaches, analysts, and selectors.
📂 Repository Structure
├── data/                # Preprocessed datasets (sample only)  
├── notebooks/           # Jupyter notebooks with model training  
├── src/                 # Python scripts for preprocessing & modeling  
├── results/             # Evaluation metrics, charts, and reports  
└── README.md            # Project documentation
📖 Citation
If you use this work, please cite:
Arigala, A.K. (2025). AI-Driven Team Selection in Professional Cricket. MSc Dissertation, University of Limerick.

