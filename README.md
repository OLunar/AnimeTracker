# Anime Watchlist

A Progressive Web App (PWA) to track your favorite anime effortlessly.

## Features

- Add and categorize anime as "Watched," "In Progress," "Dropped," or "Plan to Watch"
- View your lists on seperate tabs depending on where you categorized the show. 
- Offline support with service worker
- Responsive design with MaterializeCSS

## Updates 
- Created an offline.html
- Made it more visible compared to the first version. 

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Olunar/AnimeWatchlist-V2.git
    cd AnimeWatchlist-V2
    ```

2. Open the `index.html` file in your browser to start the app.

## Usage

- Use the input field to add new anime to your list.
- Click on an anime card to update its status.
- Use the tabs to filter anime by category.

## Technologies Used

- HTML
- CSS
- JavaScript
- MaterializeCSS
- Service Worker

### Caching Strategy
- **Cache on install**: Pre-caching the main assets during the service worker installation phase.
- **Fetch event handling**: Serving cached assets and updating the cache with new assets fetched from the network.  

## Contributing

Feel free to submit pull requests or open issues if you find bugs or want to contribute!

AnimeWatchlist-V2
