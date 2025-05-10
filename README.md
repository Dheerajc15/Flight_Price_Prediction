# Flight Price Prediction
This project focuses on predicting airline ticket prices using machine learning techniques based on historical flight data. It leverages structured datasets containing features such as airline, source, destination, total stops, departure/arrival times, and duration.

📊 Project Overview
Built a Decision Tree Regressor model to predict flight prices with a high test R² score of 0.83, indicating reliable generalization to unseen data.

Conducted extensive exploratory data analysis (EDA) using matplotlib and seaborn to visualize trends and relationships in the data.

Engineered domain-specific features like journey day/month, duration in minutes, and route complexity to improve model performance.

Visualizations included:

Box plots to show fare distribution across airlines.

Bar charts to compare price trends across source and destination cities.

Histograms to analyze duration and price spread.

Feature importance was used to identify key contributors such as total stops, duration, and airline, enhancing model interpretability.

📁 Dataset
Data_Train.csv: Training dataset with ~10,000 rows of past flight booking information.

Test_set.csv: Testing dataset used for inference and performance evaluation.

🛠️ Tools & Libraries
Python, Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn
