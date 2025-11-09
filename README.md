# Personal Dashboard

A dynamic personal dashboard that provides at-a-glance information, including a beautiful background image, real-time cryptocurrency prices, the current time, and local weather. This project is built with vanilla JavaScript and demonstrates how to fetch data from multiple third-party APIs.

## Features

-   **Dynamic Background:** Fetches and displays a new random nature-themed background image from the [Unsplash API](https://unsplash.com/developers) each time the page is loaded. The author of the image is also credited.
-   **Cryptocurrency Tracker:** Displays the current price of Bitcoin, along with the 24-hour high and low, using the [CoinGecko API](https://www.coingecko.com/en/api).
-   **Live Clock:** Shows the current time, updated every second.
-   **Weather Widget:** Gets the user's current location and displays the local weather, including temperature and a weather icon, from the [OpenWeatherMap API](https://openweathermap.org/api).

## Concepts and Technologies Covered

This project puts several core web development and JavaScript concepts into practice, including:

-   **Asynchronous JavaScript:** Makes heavy use of `async/await` for handling asynchronous operations in a clean and readable way.
-   **Fetch API:** Used to make `GET` requests to the various APIs for data.
-   **Working with APIs:**
    -   Unsplash API for images.
    -   CoinGecko API for cryptocurrency data.
    -   OpenWeatherMap API for weather information.
-   **Error Handling:** Uses `try...catch` blocks to gracefully handle potential errors during API requests, providing a fallback background image if needed.
-   **DOM Manipulation:** Dynamically updates the HTML to display the fetched data, including background images, text content, and new HTML elements.
-   **Browser APIs:**
    -   `navigator.geolocation` to get the user's geographical coordinates for the weather feature.
    -   `new Date()` and `setInterval` to create the live clock.
-   **JSON:** Parses JSON data returned from the APIs.

## How to Use

1.  Clone this repository.
2.  Open the `index.html` file in your web browser.
3.  The browser may ask for permission to access your location. Allow this to enable the weather feature.
4.  Enjoy your personal dashboard!
## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Fullstack Developer Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/courses)
- [The Frontend Career Path](https://scrimba.com/fullstack-path-c0fullstack)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
