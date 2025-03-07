# currencyConverter
The Currency Converter Web App provides real-time currency conversion using ExchangeRate-API. Users can select currencies, enter an amount, and get instant results. Built with HTML, CSS, and JavaScript, it updates country flags dynamically and defaults to USD to INR. Ideal for travelers and finance enthusiasts, it ensures accurate conversions.
# Currency Converter Web App

## Overview
The **Currency Converter Web App** is a simple and efficient tool designed to provide real-time currency conversion. It allows users to select source and destination currencies, input an amount, and instantly view the converted value. The application fetches live exchange rates from **ExchangeRate-API**, ensuring accuracy and up-to-date information. This project is ideal for travelers, finance enthusiasts, and anyone needing quick currency conversions.

## Features
- **Real-time exchange rates** fetched using **ExchangeRate-API**.
- **User-friendly interface** with dropdowns for selecting currencies.
- **Dynamic country flag updates** based on selected currencies.
- **Default conversion from USD to INR** for quick access.
- **Error handling** for invalid inputs.
- **Responsive design**, making it accessible on different devices.

## Technologies Used
- **HTML** - Structure of the web app.
- **CSS** - Styling and layout.
- **JavaScript** - Functionality and API integration.
- **ExchangeRate-API** - Fetching live exchange rates.

## Installation & Usage
### 1. Clone the Repository
```sh
 git clone https://github.com/yourusername/currencyConverter.git
 cd currencyConverter
```
### 2. Open the Project
Simply open the `index.html` file in your web browser to use the application.

## How It Works
1. Users enter an amount in the input field.
2. Select the "From" currency and "To" currency.
3. Click the **Get Exchange Rate** button.
4. The application fetches the latest exchange rate and displays the converted amount.

## API Usage
- The app uses **ExchangeRate-API** to retrieve real-time exchange rates.
- Example API endpoint:
  ```sh
  https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest/USD
  ```

## Future Enhancements
- Add a **dark mode** for better user experience.
- Support for **cryptocurrency conversion**.
- Store user preferences for faster access.

## License
This project is **open-source** and available under the MIT License.

## Contributors
- [Your Name](https://github.com/yourusername)

Feel free to contribute by reporting issues or suggesting new features!

