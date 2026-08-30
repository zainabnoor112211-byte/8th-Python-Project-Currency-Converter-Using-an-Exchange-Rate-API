# 8th-Python-Project-Currency-Converter-Using-an-Exchange-Rate-API
# Currency Converter  A beginner-friendly Python currency converter that uses the Frankfurter Exchange Rate API to convert amounts between different currencies using live exchange-rate data.
# Currency Converter

The project uses the **Requests library** to connect to the **Frankfurter v2 Exchange Rate API**, retrieves exchange-rate data in JSON format, and calculates the converted amount.

## Features

* Takes an amount from the user
* Accepts source and target currency codes
* Automatically converts currency codes to uppercase
* Fetches exchange rates from an online API
* Reads exchange-rate data from JSON
* Calculates the converted amount
* Supports currencies such as USD, PKR, EUR, GBP, AED, SAR, and JPY
* Handles negative amounts
* Handles invalid numeric input
* Handles empty or invalid currency codes
* Handles internet and API connection errors
* Supports same-currency conversion

## Technologies Used

* Python
* Requests Library
* REST API
* JSON
* Jupyter Notebook

## Formula

**Converted Amount = Amount × Exchange Rate**

## How to Run

Install the required library:

`pip install requests`

Then run the Jupyter Notebook and execute the cells in order.

## Learning Outcomes

This project demonstrates practical use of Python `input()`, `float()`, `strip()`, `upper()`, `requests.get()`, JSON data, dictionaries, conditional statements, exception handling, and `round()`.

Exchange rates are updated over time, so conversion results may vary depending on the latest available API data.
