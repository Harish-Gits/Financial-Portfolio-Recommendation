# Financial Portfolio Recommendation

## Overview

This project provides personalized investment portfolio recommendations using a reinforcement learning model. The application is built using Python, TensorFlow/Keras, and Flask, and offers real-time stock information and investment projections based on user inputs.

## Features

- Personalized portfolio diversification recommendations
- Real-time stock information
- Investment projection based on user inputs
- Web-based user interface for easy interaction

## Skills Utilized

- Python Programming
- Machine Learning
- Reinforcement Learning
- Flask Framework
- Web Development
- TensorFlow/Keras
- API Integration
- Finance and Investment Knowledge
- ngrok
- yfinance

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harish-Gits/financial-portfolio-recommendations.git
    cd financial-portfolio-recommendations
    ```

2. Set up ngrok:
    ```bash
    ngrok authtoken YOUR_NGROK_AUTHTOKEN
    ```

## Usage

1. Run the Flask application:
    ```bash
    python app.py
    ```

2. Start the ngrok tunnel:
    ```bash
    ngrok http 5000
    ```

3. Access the application using the provided ngrok URL.

## Project Structure

- `Financial_Portfolio_Investment.py`: The main Flask application file.
- `investment_dataset.csv`: The dataset used for training the model.
- `rl_portfolio_diversification_model.h5`: The trained reinforcement learning model.

## Example

1. Input your details (age, salary, SIP, risk, investment period, and expected returns) to get personalized portfolio diversification recommendations.
2. Get real-time stock information by entering the stock name.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please contact me at [harsih14rs@gmail.com](mailto:harsih14rs@gmail.com).
