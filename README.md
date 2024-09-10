# Ames Housing Price Prediction

This project is a solution for the Ames Housing Price Prediction competition on Kaggle. It uses machine learning techniques to predict the sale price of houses in Ames, Iowa, based on various features of the properties.

## Competition Description

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often-cited Boston Housing dataset.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Model Details

This solution uses an ensemble of three models:

1. Random Forest
2. XGBoost
3. LightGBM

The preprocessing pipeline handles missing values, scales numerical features, and one-hot encodes categorical features.

## Evaluation

The competition uses Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

## Contributing

Contributions to improve the model or the code structure are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
