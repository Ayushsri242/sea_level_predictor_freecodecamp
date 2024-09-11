### Repository Description:
The **Sea Level Predictor** repository provides a Python solution for predicting future sea levels using historical data. This project is part of FreeCodeCamp’s **Data Analysis with Python** course. The project utilizes linear regression to analyze historical sea level data and predict future trends. The results are plotted on a graph, helping visualize both past and predicted sea levels.

### Key Features:
1. **Data Visualization**:
   - Uses `matplotlib` to create line plots that display historical sea level data alongside future predictions.
   
2. **Linear Regression**:
   - Employs `scipy.stats.linregress` to perform linear regression on the data, fitting lines for both past data (from 1880) and more recent data (from 2000).

3. **Multiple Timeframes**:
   - Fits two regression models: one using the full dataset (1880 onwards) and another using data from 2000 onwards for comparison of trends.

4. **Future Predictions**:
   - Predicts sea levels up to the year 2050 based on the linear regression models and plots the extrapolated data.

5. **Test-Driven**:
   - Includes unit tests to ensure accuracy in regression calculations and plots.

This project helps users gain experience with data visualization, regression analysis, and predicting trends from real-world datasets.
