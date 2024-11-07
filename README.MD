## Crypto Tracker Application

A simple and intuitive crypto tracker application that provides up-to-date information on various cryptocurrencies. This app fetches data from the CoinCap API to display real-time information about different cryptocurrencies and their historical price trends through line graphs.

### Features
Real-Time Crypto Prices: View current prices, market cap, and other key metrics for popular cryptocurrencies.
Historical Price Graphs: Track price trends over time with interactive line charts for each cryptocurrency.
Top Performers: View the top-performing cryptocurrencies based on market cap or price change.
User-Friendly Interface: Simple navigation with an intuitive and responsive UI.

## Screenshots
### Dark Theme
![CoinList Dark](https://github.com/user-attachments/assets/95954a29-30fd-48c0-a63d-96cf92ef3f15)
![CoinDetail Dark](https://github.com/user-attachments/assets/68c8d111-9bde-49f5-b549-f16e3586e747)
### Light Theme
![CoinList Light](https://github.com/user-attachments/assets/86227c90-62b3-4178-9453-a6073e8ee660)
![CoinDetail Light](https://github.com/user-attachments/assets/4f053d30-3b1d-4a23-b770-f3208837e3bb)

### Tech Stack
Frontend: Jetpack Compose (for UI components)
Backend: CoinCap API

API Reference
This application uses the CoinCap API to fetch real-time cryptocurrency data and historical price information.

Endpoints Used
Get All Cryptocurrencies

Endpoint: /v2/assets
Description: Returns a list of all cryptocurrencies with their current data.
Get Cryptocurrency Details

Endpoint: /v2/assets/{id}
Description: Provides details for a specific cryptocurrency, such as price, market cap, and volume.
Get Historical Price Data

Endpoint: /v2/assets/{id}/history?interval=d1
Description: Returns historical price data for a specific cryptocurrency. The interval can be adjusted (e.g., hourly, daily).