# Data Driven Exploration of the Gaming Landscape in 2021

## Project Overview  
This project, conducted under **Professor X** as part of the course **"Y"** at the University of Colorado Boulder, provides a data-driven analysis of significant trends and player behavior in the gaming industry for 2021. The study uses web scraping, data preprocessing, and machine learning models to predict the number of game owners based on various attributes. This project offers insights into game dynamics, industry trends, and player preferences to facilitate better decision-making in the gaming sector.

## Data Explanation  
- **Name:** The name of the game.  
- **developers_publishers:** Developers and publishers of the game.  
- **genre:** The game genre (e.g., RPG, FPS).  
- **category:** Game categories or tags (e.g., multiplayer, single-player).  
- **release_date:** Release date of the game.  
- **price:** Price of the game (in USD).  
- **owners:** Predicted number of game owners.  
- **followers:** Number of followers on the Steam page.  
- **playtime_total:** Average playtime (in hours) for predicted owners.

## Features and Highlights  
- **Data Collection:**  
  - Web scraping from SteamSpy using `BeautifulSoup`.
  - Collected data on 9,901 games with 9 attributes, including release date, genre, publisher, price, and ownership statistics.

- **Data Cleaning & Preprocessing:**  
  - Removed unnecessary columns and null values.
  - Converted data types (e.g., dates to datetime, prices to floats).
  - Extracted useful features like the month from the release date.

- **Machine Learning Models Implemented:**  
  - **Linear Regression:** For preliminary trend analysis.  
  - **Support Vector Regressor (SVR):** To handle non-linear relationships.  
  - **K-Nearest Neighbors (KNN):** For localized patterns.  
  - **Random Forest:** For robust ensemble-based predictions.  
  - **Artificial Neural Networks (ANN):** To capture intricate, non-linear patterns. ANN performed best with a **Mean Squared Logarithmic Error (MSLE) of 0.48**.

## Results  
- **Top-performing Model:** ANN with MSLE of **0.48**.  
- **Comparison of Model Performance:**  
  - Linear Regression: MSLE 2.54  
  - SVR: MSLE 1.09  
  - KNN: MSLE 0.75  
  - Random Forest: MSLE 0.67  
  - ANN: MSLE 0.48  

## Key Findings  
1. **Emerging Trends:** Next-gen consoles like PS5 and Xbox Series X/S boosted industry sales.
2. **Behavioral Shifts:** Gaming evolved as a social platform during lockdowns.
3. **Innovations:** AI-powered analytics and real-time behavior tracking improved gaming experiences.

## Future Work  
- **Enhanced Feature Engineering:** Explore more predictors, such as user engagement metrics.  
- **Advanced Architectures:** Use RNNs or CNNs to capture temporal or spatial trends.  
- **Explainability:** Implement SHAP or LIME for transparent model predictions.  
- **User Segmentation:** Build personalized models for targeted recommendations.  
- **Ethics & Fairness:** Address algorithmic fairness and data privacy concerns.

## How to Run
1. **Data Preprocessing:**  
   - Run `data_cleaning.ipynb` to prepare the dataset.
2. **Model Training:**  
   - Execute `model_training.ipynb` to train models on the cleaned data.
3. **Evaluation:**  
   - View results using `evaluation.ipynb`.

## Contributors  
- **Shreyash Sahare** – Data Collection & Feature Engineering  
- **Adwait Mahajan** – Machine Learning Models & Evaluation  
- **Junsoo Jung** – Data Cleaning & Report Writing  

## Contact  
For any questions or collaborations, please reach out to:  
- Shreyash Sahare: shsa7246@colorado.edu  
- Adwait Mahajan: adma4717@colorado.edu  
- Junsoo Jung: juju6944@colorado.edu

This project was done under Prof. **Alfonso Bastias** as a part of the **CSCI-5502 Data Mining** course at the University of Colorado Boulder.
