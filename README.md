# 🎬 TVMaze Web App

A simple PHP-based web application that allows users to search for TV shows and view detailed show information using the [TVMaze API](https://www.tvmaze.com/api). This app is built with Bootstrap for a clean and responsive UI.

## 🚀 Features

- 🔍 Search for TV shows by name
- 📄 View detailed information about each show
- 🖼️ Show images, summaries, genres, and premiere dates
- ⭐ Displays a list of 5 popular shows (can be customized)
- ⚡ Fast and lightweight PHP integration with TVMaze API

## 🛠️ Tech Stack

- PHP
- Bootstrap 4
- HTML/CSS
- TVMaze REST API

## 📁 Project Structure

/tvmaze-web-app/ 
├── show.php # Displays search form, show details, and popular shows 
├── index.php # Redirects or loads default view (optional) 
├── includes/ 
│ └── api.php # Handles all TVMaze API interactions 
├── assets/ 
│ ├── css/ │ 
│ └── style.css # Custom styles │ └── js/ │ 
└── main.js # (Optional) JS functionality

## 🔧 Setup Instructions

1. Clone the repository:
   
   git clone https://github.com/Aubreykuseli/tvmaze-web-app.git
   cd tvmaze-web-app
   
Run it on a local server (e.g., XAMPP, MAMP, etc.) since it’s PHP-based.

Make sure to configure your API interaction file (includes/api.php) with proper methods for:

searchShows()

getShowDetails()

Open show.php in your browser and start searching!

📦 TVMaze API
All show data is fetched from the official TVMaze API. No API key required for public endpoints.

📸 Screenshots
(Add screenshots of the UI here if available)

📄 License
This project is open-source and available under the MIT License.

Feel free to contribute or fork the project to improve and add more features like:

Pagination

Genre filtering

Favorite shows

User accounts


Live demo link 

www.projects265.infy.uk






