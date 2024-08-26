
# Stock Sentiment Analysis

## Project Overview
This project aims to analyze news headlines to predict stock market movements (up or down) based on sentiment analysis. The analysis involves using machine learning models like Random Forest and XGBoost to classify the market movements.

### Objectives
- Perform sentiment analysis on news headlines.
- Build and evaluate machine learning models to predict market movements.
- Utilize metrics like ROC curves and AUC to assess model performance.

## Data
The dataset consists of daily news headlines from various sources, with labels indicating whether the stock market moved up or down on that day.

### Columns:
- `Date`: The date of the news.
- `Label`: 0 indicates the stock market went down, 1 indicates it went up.
- `Top1` to `Top25`: The top 25 headlines for that day.

## Methods
1. **Sentiment Analysis**: News headlines are cleaned and vectorized using TF-IDF.
2. **Random Forest**: A tree-based ensemble model used to classify market movements.
3. **XGBoost**: A gradient boosting model optimized for speed and performance.
4. **ROC and AUC**: ROC curves and AUC scores are used to evaluate the classification performance.

## Instructions to Run
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```
   jupyter notebook Stock_Sentimental_Analysis.ipynb
   ```

## Results
- **Model Performance**: Both Random Forest and XGBoost models are evaluated using accuracy, precision, recall, F1-score, and AUC. ROC curves are plotted to visualize the model's performance.

## Conclusion
The project demonstrates how sentiment analysis combined with machine learning models can be used to predict stock market movements. The results indicate the effectiveness of using these techniques to make informed predictions.
