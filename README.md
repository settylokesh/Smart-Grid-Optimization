# Smart Grid Optimization Project

## Project Overview
This project focuses on electricity load forecasting and smart grid optimization using historical data from California's power grid. By analyzing and modeling electricity load patterns, the project aims to improve grid management, reduce costs, and enhance the integration of renewable energy sources into the grid.

## Data Sources
The project utilizes multiple data sources:
1. **Electricity Production Data**: Yearly production data from 2020 to 2025, containing hourly information about electricity generation from various sources.
2. **Weather Data**: California hourly weather data from 2020 to 2025, including temperature, humidity, wind speed, and solar radiation.
3. **Merged Dataset**: The combined dataset with both electricity load and weather variables.

## Project Structure

### 1. Setup and Modeling
The [Setup and Modeling.ipynb](./Setup%20and%20Modeling.ipynb) notebook handles:
- Data acquisition from multiple sources
- Initial data exploration and preprocessing
- Merging of electricity production data with weather data
- Feature engineering for model preparation

### 2. Exploratory Data Analysis (EDA)
The [EDA.ipynb](./EDA.ipynb) notebook provides:
- Comprehensive analysis of load patterns
- Visualization of key variables and their distributions
- Investigation of relationships between weather factors and electricity load
- Temporal analysis (hourly, daily, weekly, seasonal patterns)

### 3. Basic Prophet Forecasting
The [prophet.ipynb](./prophet.ipynb) notebook implements:
- Time series forecasting using Facebook's Prophet library
- Integration of external variables (temperature, humidity, etc.) as regressors
- Model training, evaluation, and visualization of predictions
- Performance metrics calculation (MAE, RMSE, MAPE, R²)

### 4. Advanced Prophet Modeling
The [Prophet(Extra_Feature_Eng).ipynb](./Prophet%28Extra_Feature_Eng%29.ipynb) notebook extends the forecasting capabilities with:
- Advanced feature engineering (lag features, rolling averages, seasonal flags)
- Time-based features (hour of day, day of week, weekend flags, working hours)
- Improved model training and evaluation
- Detailed component analysis (daily, weekly, yearly patterns)
- Feature importance analysis

## Key Findings and Visualizations
The project produces several key insights:
- Detailed electricity load patterns across different timeframes (daily, weekly, yearly)
- Impact of weather variables on electricity consumption
- Identification of peak load periods and seasonal variations
- Performance evaluation of prediction models

## Technologies Used
- **Python**: Core programming language
- **Pandas & NumPy**: Data manipulation and numerical operations
- **Matplotlib & Seaborn**: Data visualization
- **Prophet**: Time series forecasting
- **Scikit-learn**: Machine learning metrics and preprocessing
- **Plotly**: Interactive visualizations

## Future Improvements
Potential enhancements to the project include:
- Integration of deep learning models (LSTM, Transformer-based architectures)
- Real-time forecast updates based on new data
- Grid optimization strategies based on forecasts
- Economic impact analysis and cost optimization
- Integration with renewable energy forecasting for grid balancing

## How to Use
1. Clone the repository
2. Install required dependencies 
3. Run the notebooks in the following order:
   - Setup and Modeling.ipynb
   - EDA.ipynb
   - prophet.ipynb
   - Prophet(Extra_Feature_Eng).ipynb
4. Explore the visualizations and findings in each notebook
