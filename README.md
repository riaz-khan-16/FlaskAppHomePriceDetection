# Home Price Prediction App

## Description

The Home Price Prediction App is a web application designed to provide users with an estimate of home prices based on various input features. This app leverages a machine learning model, specifically a linear regression algorithm, trained on historical home price data to make accurate predictions.


![Website Picture](https://github.com/riaz-khan-16/Flask_App_for_Home_Price_Detection/assets/63443462/7dd47551-25e8-4e8f-9e5d-d26d4efcb094)

## Features

- **Predict Home Prices:** Input various home features to get a predicted price.
- **User-Friendly Interface:** Simple and intuitive interface for easy user interaction.
- **Flask Backend:** Efficient backend server for handling prediction requests.
- **Machine Learning Model:** Linear regression model trained on historical data for accurate price predictions.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/home-price-prediction.git
    cd home-price-prediction
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask app:**

    ```bash
    flask run
    ```

5. **Open your browser and navigate to:**

    ```
    http://127.0.0.1:5000/
    ```

## Usage

- Enter the required home features (e.g., location, size, number of bedrooms) in the form on the main page.
- Click the "Predict" button.
- The predicted home price will be displayed on the page.

## Model Training

The linear regression model was trained using historical home price data. The training script (`train_model.py`) preprocesses the data, trains the model, and saves it as a pickle file (`model.pkl`). 


## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.




