SpaceX Falcon 9: First Stage Landing Prediction
🚀 Project Overview
This project is part of the IBM Data Science Capstone certificate. The primary objective is to predict whether the first stage of a SpaceX Falcon 9 rocket will land successfully.

Since SpaceX advertises rocket launches at approximately $62 million (while other providers cost over $165 million), much of the savings come from their ability to reuse the first stage. Predicting landing success allows for a better estimation of launch costs, providing valuable intelligence for competitive bidding.

🛠 Methodology
The project follows a comprehensive Data Science pipeline:

Data Collection: * Gathered historical launch data using the SpaceX REST API.

Performed Web Scraping from Wikipedia using BeautifulSoup to supplement the dataset.

Data Wrangling: * Cleaned data, handled missing values, and performed feature engineering (e.g., creating a "Landing Outcome" binary label).

Exploratory Data Analysis (EDA): * Used SQL to query specific launch insights.

Visualized relationships between payload mass, launch sites, and orbit types using Matplotlib and Seaborn.

Interactive Visual Analytics: * Built maps with Folium to visualize launch site proximity and success rates.

Developed an interactive dashboard using Plotly Dash for real-time data filtering.

Machine Learning Classification: * Trained and compared four models: Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree.

Performed hyperparameter tuning using GridSearchCV.

📊 Key Findings
Success Trends: The launch success rate has improved significantly over the years as technology matured.

Launch Site Impact: KSC LC-39A proved to be the most successful launch site with a 76.9% success rate.

Optimal Payload: Success rates are highest for payloads between 2,000kg and 6,000kg.

Model Performance: All models achieved an accuracy of 83.3% on the test set. The Decision Tree model was identified as the best performer based on its F1-Score.

💻 Tech Stack
Language: Python

Data Analysis: Pandas, NumPy, SQL

Machine Learning: Scikit-Learn

Visualization: Matplotlib, Seaborn, Folium, Plotly Dash

Tools: Jupyter Notebook, GitHub

📂 Repository Structure
Plaintext
├── data/                         # CSV files with raw and processed data
├── notebooks/                    # Jupyter notebooks for each project phase
├── reports/                      # Final project presentation (PDF)
└── README.md                     # Project documentation
💡 Career Focus
This project demonstrates proficiency in:

End-to-end Data Science workflows.

Integrating multiple data sources (API & Web Scraping).

Applying advanced Machine Learning techniques for binary classification.

Translating complex data into actionable business insights.
