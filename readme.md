# Car Price Prediction

## Project Overview
This project focuses on predicting car prices using machine learning techniques. It includes data preprocessing, exploratory data analysis, and the implementation of a Linear Regression model to predict car prices based on various features.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you need to have Python installed on your system. After cloning the repository, install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/AmrMohamed17/car-price-prediction.git
   cd car-price-prediction
   ```

2. Run the Jupyter notebook or Python script:
   ```bash
   jupyter notebook car_price_prediction.ipynb
   ```
   or
   ```bash
   python car_price_prediction.py
   ```

## Data

The project uses the 'cars_info.csv' dataset, which contains various features of cars including:
- Name
- Company
- Year
- Price
- Kilometers driven
- Fuel type

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Data type conversion
   - Feature engineering (e.g., simplifying car names)
   - Outlier removal

2. **Exploratory Data Analysis (EDA)**:
   - Examining unique values in different columns
   - Visualizing data distributions (not explicitly shown in the code, but recommended)

3. **Machine Learning**:
   - Feature encoding using OneHotEncoder
   - Train-test split
   - Linear Regression implementation using scikit-learn
   - Model evaluation using Mean Squared Error and R-squared score
   - Hyperparameter tuning through multiple train-test splits

## Results

The model's performance is evaluated using the R-squared score. The best model is selected after running multiple iterations with different random states for train-test splits.

Final R-squared score: [Add your best R-squared score here]

The model can predict the price of a car given its features. For example:
```python
car_features = ['Maruti Suzuki Swift', 'Maruti', 2010, 1000, 'Diesel']
predicted_price = [Add the predicted price here]
```

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

