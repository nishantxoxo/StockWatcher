# Stock Market App

## About the Project

This application allows users to view a list of companies, search for specific companies, and see detailed information about a company's stock. The app follows the MVVM (Model-View-ViewModel) architecture and utilizes a clean architecture approach.

## Features

*   **Company Listings:** View a list of companies with their stock information.
*   **Search:** Search for companies by name or symbol.
*   **Company Details:** View detailed information about a company, including its stock chart.
*   **Data Caching:** Stock market data is cached locally using a Room database, allowing for offline access.

## Tech Stack

*   **Kotlin:** The primary programming language.
*   **Jetpack Compose:** For building the UI.
*   **Coroutines:** For managing asynchronous operations.
*   **Hilt:** For dependency injection.
*   **Retrofit:** For making network requests to the stock market API.
*   **Room:** For local data storage.
*   **Moshi:** For parsing JSON data.
*   **Coil:** For loading images.
*   **Compose Destinations:** For navigation.
*   **OpenCSV:** For parsing CSV data.

## ScreenShots
<p align="center">
  <img src="https://github.com/user-attachments/assets/aae0a960-c411-4f90-a6d2-314c960d0b22" width="30%" />
  <img src="https://github.com/user-attachments/assets/58ce6918-498c-49fb-9c25-26ec6171e05c" width="30%" />
  <img src="https://github.com/user-attachments/assets/4681f941-d556-47ee-abb7-9470c8581b29" width="30%" />
</p>

## Project Structure

The project is organized into the following packages:

*   `data`: Contains the data layer, including the repository implementation, data sources (local and remote), and data transfer objects (DTOs).
*   `di`: Contains the Hilt dependency injection modules.
*   `domain`: Contains the domain layer, including the repository interface and use cases.
*   `presentation`: Contains the presentation layer, including the ViewModels and UI components.
*   `ui`: Contains the UI-related files, such as themes and composables.
*   `util`: Contains utility classes and functions.

