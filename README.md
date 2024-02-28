# Used Car Price Prediction with Machine Learning

This project aims to predict the price of used cars using machine learning techniques. It utilizes a dataset containing various features such as the car's model, year of manufacture, mileage, etc., to build a predictive model.

## Requirements

- Python 3.x
- Libraries:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

## Installation

1. Clone the repository:
   ```
   git  https://github.com/mehrdadOrouei/car_price_prediction.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have a dataset containing relevant features such as car model, year, mileage, fuel type, etc., along with the target variable indicating the price.

2. Run the main script:
   ```
   python main.py
   ```

3. Follow the prompts to input car details and obtain price prediction results.

## Dataset

The project utilizes a dataset containing information about used cars, including features like model, year, mileage, fuel type, transmission type, etc.

## Approach

1. **Data Preprocessing**: Clean and preprocess the dataset, handle missing values, encode categorical variables, and normalize numerical features.

2. **Feature Engineering**: Create new features or modify existing ones to enhance the predictive power of the model.

3. **Model Selection**: Choose appropriate regression algorithms such as linear regression, decision trees, random forests, etc., to train on the preprocessed dataset.

4. **Model Training**: Train the selected model(s) on the dataset, using techniques like cross-validation to optimize performance.

5. **Model Evaluation**: Evaluate the trained model(s) using metrics such as mean squared error, mean absolute error, and R-squared score.

6. **Hyperparameter Tuning**: Fine-tune the parameters of the selected model(s) to improve predictive performance.

7. **Prediction**: Utilize the trained model to predict the price of used cars based on input features.

## Contributors

- mehrdad.orouei@yahoo.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
