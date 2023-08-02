# Currency Converter

This is a simple Python script that allows you to convert an amount from Indian Rupees (INR) to another currency. The script reads currency conversion rates from a `currency.txt` file and performs the conversion based on the user's input.

## Table of Contents

1. [Badges](#badges)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Documentation](#documentation)

## Badges

[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

## Installation

1. Ensure you have Python installed on your system. You can download Python from the official website: [Python.org](https://www.python.org/downloads/)

2. Download the `currency.txt` file and place it in the same directory as the Python script. The `currency.txt` file contains currency conversion rates in the following format:

   ```
   CurrencyCode   ConversionRate
   ```

   For example:
   ```
   USD   0.013
   EUR   0.011
   GBP   0.009
   ```

3. Run the Python script in a Python environment.

## Usage

1. The script will prompt you to enter an amount in INR (Indian Rupees).

2. Next, it will display a list of available currency codes that you can convert the amount to.

3. Enter one of the currency codes from the list.

4. The script will then perform the conversion and display the result.

## Configuration

The `currency.txt` file is used to store the conversion rates of different currencies. You can modify this file to add or update currency conversion rates as per your needs. Make sure to follow the same format of `CurrencyCode   ConversionRate`.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to open a pull request or create an issue on the GitHub repository.

## License

This project is open-source and licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code, but please provide proper attribution to the original creator, Harsh Gupta (Desparete Enuf).

## Acknowledgments

The Currency Converter was created by Harsh Gupta (Desparete Enuf) as a simple utility to convert currency values from INR to other currencies. The code is provided here for reference and learning purposes.

## Documentation

The script uses the following concepts:

1. **File Handling**: The script reads currency conversion rates from the `currency.txt` file using file handling. The conversion rates are stored in a Python dictionary `currencyDict`, where the currency code is the key and the conversion rate is the value.

2. **User Input**: The script takes user input for the amount in INR and the currency code to which the amount needs to be converted.

3. **Currency Conversion**: The script performs the currency conversion using the conversion rate from the `currencyDict` dictionary and displays the converted amount.

4. **Loop and List Comprehension**: The script uses a loop to read lines from the `currency.txt` file and list comprehension to display available currency codes to the user.

Feel free to use this Currency Converter as a starting point for your own projects or to enhance your Python skills. Happy coding!
