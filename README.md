#public api connector html onepage
# API Updater

## Overview

The **API Updater** is a single-page web application that dynamically fetches and displays data from various public APIs. It showcases 25 different APIs, each displayed in its own div element. The page updates the content of these divs every 15 seconds, highlighting them briefly to indicate that new data has been fetched. If an API response contains an image, it displays only the image; otherwise, it displays the JSON data.

## Features

- **Parallel Fetching**: Fetches data from 25 APIs concurrently.
- **15-Second Update Interval**: Each API is updated every 15 seconds.
- **Image Display**: If the API response contains an image, only the image is displayed.
- **JSON Display**: For non-image responses, the JSON data is formatted and shown.
- **Highlighting**: Updated divs are highlighted briefly to indicate new data.
- **Responsive Design**: The page adjusts to different screen sizes and maintains smooth scrolling.

## APIs Used

The application interacts with a diverse set of public APIs, including:
- GitHub User Info
- Random Dog Image
- Random Cat Image
- OpenWeatherMap (Weather)
- JSONPlaceholder (Todos and Posts)
- Chuck Norris Jokes
- Kanye West Quotes
- Agify (Name Analysis)
- Random User Generator
- Exchange Rate Data
- Random Jokes
- Random Advice
- Public APIs Directory
- Random GIFs
- Bitcoin Price
- Google Books API
- Reddit Posts
- SpaceX Launch Data
- Cat Breeds
- Random Beer
- NASA Astronomy Picture of the Day

## Installation

To use this project, you don't need any special installation steps. You can run it directly in a web browser.