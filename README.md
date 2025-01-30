# News App

This is a simple News App that fetches and displays news articles using the News API. The app allows users to search for news articles by keyword and filter news by categories such as IPL, Finance, and Politics.

## Features

- Fetches news articles from the News API.
- Displays news articles with images, titles, descriptions, and sources.
- Allows users to search for news articles by keyword.
- Provides category filters for IPL, Finance, and Politics.
- Responsive design using Bootstrap.

## Technologies Used

- HTML
- CSS
- JavaScript
- Bootstrap
- News API

## Setup Instructions

1. Clone the repository to your local machine.
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory.
    ```sh
    cd news
    ```
3. Open the `index.html` file in your preferred web browser.

## Usage

1. On page load, the app fetches and displays news articles related to "India".
2. Use the search bar to search for news articles by entering a keyword and clicking the "Search" button.
3. Click on the category links (IPL, Finance, Politics) in the navigation bar to filter news articles by category.
4. Click on any news card to open the full article in a new tab.

## API Key

The app uses the News API to fetch news articles. You need to provide your own API key in the `script.js` file.

1. Sign up at [News API](https://newsapi.org/) to get your API key.
2. Replace the `API_KEY` variable in the `script.js` file with your API key.
    ```javascript
    const API_KEY = "your_api_key_here";
    ```


