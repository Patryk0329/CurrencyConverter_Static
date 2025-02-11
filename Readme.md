# Currency Converter

This is a simple currency converter application built using WPF and .NET 8.0. The application uses static data for currency exchange rates, which are hardcoded in the code. This project serves as a base for a future project that will fetch real-time exchange rates.

## Features

- **Convert between different currencies using static exchange rates.**
- **Simple and intuitive user interface.**
- **Validation to ensure only numeric input is accepted for the amount to be converted.**

## Static Data

The application uses the following static exchange rates:

- **PLN:** 1
- **USD:** 4.0071
- **EUR:** 4.1483
- **CHF:** 4.3874
- **GBP:** 4.9845
- **CAD:** 2.7999
- **CZK:** 0.1639

## Future Enhancements

This project is a base for a future project that will:

- **Fetch real-time exchange rates from an external API.**
- **Update the exchange rates dynamically.**

## How to Run

1. **Open the solution in Visual Studio 2022.**
2. **Build the project to restore the necessary packages.**
3. **Run the application.**

## Usage

1. **Enter the amount to be converted in the "Enter Amount" textbox.**
2. **Select the currency to convert from in the "From" dropdown.**
3. **Select the currency to convert to in the "To" dropdown.**
4. **Click the "Convert" button to see the converted amount.**
5. **Click the "Clear" button to reset the inputs.**

## Dependencies

- **.NET 8.0**
- **MaterialDesignInXamlToolkit**

## Note

This project is intended for educational purposes and as a base for future development. The exchange rates are static and do not reflect real-time data.