# Trading App Backend
This project is a basic backend implementation to interact with a fyer's API for trading purposes. It provides functionality to fetch current holdings, place buy and sell orders, receive postbacks from the broker, and get real-time price updates via websockets.

## Features
* Fetch current holdings: Retrieve the list of current holdings in the trading account.(/holdings inside first.py)
* Place buy order: Execute a buy order for a specified stock.(/buy inside first.py)
* Place sell order: Execute a sell order for a specified stock.(/sell inside first.py)
* Receive postback from the broker: Handle postbacks received from the broker after order execution.(/postbacks inside first.py)
* Get real-time prices via websocket: Subscribe to real-time price updates for specified stocks using websockets.(/subscribe inside first.py)
* Adding real time Web Sockets Data into the Database which can be used for backtesting.

## Technologies Used
Python: A Programming Language
Flask: A micro web framework for building web applications.
Fyers API: API for interacting with the Fyers trading platform.
HTML: A markup language for frontend

## Usage

1. Clone the repository
   ```
   git clone https://github.com/pandharkardeep/Trading_AppBackend.git
   ```
2. Install dependencies
   ```
   pip install -r requirements.txt
   ```
3. Set up Fyer's API credentials.
4. Run the Flask Application
   ```
   python first.py
   ```
5. Open the Frontend in the HTML File

## Acknowledgements
Flask: A micro framework for backend development using Python
Fyers Web API
