# React Currency Converter

This project is a React application built with Vite. It allows users to convert currency using the [Currency API](https://github.com/fawazahmed0/currency-api).

## Features

- Fetches real-time currency conversion rates from the Currency API.
- Converts currency based on user input.
- Lightweight and fast, thanks to Vite and React.

## How It Works

The application uses the following API endpoint to fetch currency conversion data:

Here, `{currency}` is dynamically replaced with the currency code (e.g., `usd`, `eur`) to fetch the relevant conversion rates.

The `useCurrencyInfo` custom hook is responsible for fetching and managing the currency data. It uses React's `useEffect` and `useState` hooks to fetch data whenever the currency code changes.

## Getting Started

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server with `npm run dev`.
4. Open the application in your browser at `http://localhost:5173`.

## Dependencies

- React
- Vite

## License

This project is licensed under the MIT License.