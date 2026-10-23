DataPilot AI — Intelligent Data Cleaning, Feature Selection & Model Improvement Assistant

From messy dataset to tested machine-learning model. DataPilot AI is a comprehensive, client-side data science assistant built to help students, data analysts, and ML beginners prepare data, understand column significance, select optimal features, and prove model improvement.

🚀 Project Overview & Motivation

When building machine learning models, beginners often fall into common traps:

Feeding raw, messy data (missing values, duplicates, extreme outliers) directly into models.

Ranking features using statistical correlation without proving whether removing less useful columns actually improves model performance.

Using naive association measures instead of rigorous machine learning feature selection (Filter, Wrapper, and Embedded methods).

DataPilot AI solves the complete workflow in one single application running entirely in the browser.

🛠️ Key Features

📂 Step 1 — Upload & Target Selection: Instant client-side CSV parsing with Papa Parse, dataset row/column counters, and prediction target selection.

🩺 Step 2 — Data Health Check: Scans datasets for missing values, exact duplicates, structural flaws, and numeric outliers using IQR.

🧹 Step 3 — Automatic Data Cleaning: Interactive cleaning panel to impute missing values (Median/Mode), cap outliers, and remove duplicates with an Undo mechanism and live Before/After preview.

⚙️ Step 4 — Advanced Feature Selection: Implements three distinct paradigms with plain-English insights:

Filter Methods: Pearson correlation, ANOVA effect size ($\eta^2$), and Cramér's V.

Wrapper Approximations: Recursive Feature Elimination (RFE) score simulation.

Embedded Methods: Tree-based Gini importance & L1 regularization scores.

📊 Step 5 — Test & Model Improvement Proof: Trains two leakage-safe models (Baseline with all features vs. Optimized with selected features) and compares Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Training Time visualized with Chart.js.

📥 Step 6 — Export & Reproducible Code: Download cleaned CSV datasets, text analysis reports, and copy clean, ready-to-run Python code (Pandas & Scikit-Learn).

🖥️ Live Demo & Usage

Open [DataPilot_AI.html](https://datapilot-app-sigma.vercel.app) in any modern web browser.

Click "Load Sample Dataset" to test immediately with housing price data, or upload your own CSV file.

Follow the guided 6-step top navigation bar from upload to export!
