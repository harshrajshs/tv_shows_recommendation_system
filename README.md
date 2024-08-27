# VistaVibe - A TV Shows Recommender System

![VistaVibe Banner](path/to/your/banner/image.png)

## Overview
**VistaVibe** is a comprehensive TV show recommender system that leverages both content-based and collaborative filtering techniques to provide personalized show recommendations. The project scrapes data from [The Movie Database (TMDb)](https://www.themoviedb.org/tv) and utilizes this information to enhance user experience.

## Features
- **Content-Based Filtering**: 
  - Recommendations based on similar keywords, creators, actors, overview, and genres.
  - Utilizes tokenization for improved recommendation accuracy.
  
- **Collaborative Filtering**:
  - Implemented using the ALS (Alternate Least Squares) method.
  - Provides recommendations based on user behavior and preferences.

- **User Authentication**:
  - Secure login and registration system using Firebase.
  - Personalized experience based on user profiles.

- **Search Functionality**:
  - Quickly find TV shows by name, genre, or keyword.

- **Genre-Based Browsing**:
  - Explore shows by selecting genres from a dropdown menu.
  - View all shows within a chosen genre.

- **Detailed Show Information**:
  - Click on any TV show to view its description, trailer, and top 30 recommendations.
  
## Data Collection
Data was scraped from [TMDb](https://www.themoviedb.org/tv) using Python's Beautiful Soup and Requests libraries. The data is stored in a CSV file with the following columns:
- `name`
- `overview`
- `id`
- `poster_path`
- `rating`
- `vote_count`
- `adult`
- `director`
- `producer`
- `creator`
- `actors`
- `year_released`
- `genres`
- `keywords`
- `tags`
- `trailer`

## Website Structure
- **Homepage**: A welcoming interface showcasing featured TV shows and popular genres.
  ![Homepage Screenshot](path/to/homepage/screenshot.png)

- **Search**: A search icon allows users to quickly find their favorite shows.
  ![Search Feature Screenshot](path/to/search/screenshot.png)

- **Genre Selection**: Dropdown menu for exploring shows by genre.
  ![Genre Selection Screenshot](path/to/genre/screenshot.png)

- **Show Details**: In-depth information about the selected show, including trailer and recommendations.
  ![Show Details Screenshot](path/to/show/details/screenshot.png)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/harshrajshs/tv_shows_recommendation_system.git
2. Install the required Python packages:
3. Run the website:
   simply run index.html
## Technologies Used
- **Python**: For data scraping, processing, and backend logic.
- **Beautiful Soup & Requests**: For web scraping.
- **Pandas**: For data handling and CSV management.
- **Scikit-Learn**: For content-based filtering.
- **Surprise**: For collaborative filtering with ALS.
- **Firebase**: For user authentication and data storage.
- **HTML/CSS/JavaScript**: For front-end development.
- **Flask**: As the web framework.
- **Bootstrap**: For responsive design.

## Contribution
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
