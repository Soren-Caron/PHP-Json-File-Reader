# Movie Table Display - README

## Overview
This project is a simple PHP web application that dynamically generates a table of movies using data from a JSON file. The table is styled with **Bootstrap** for a clean and professional appearance.

## Structure
The project includes the following files:
1. **`index.html`**:
   - Main HTML file with embedded PHP code to display the movie table.
   - Uses **Bootstrap 5** for styling.
2. **`movies.json`**:
   - JSON file containing the movie data (title, year, genre, director).
3. **`style.css`** (optional):
   - Custom CSS for additional styling.

## Features
- Dynamically displays a list of movies in a styled table.
- Uses Bootstrap's table classes (`table-striped` and `table-hover`) for a polished look.
- Data is loaded from a JSON file, making it easy to update or expand the list of movies.

## How It Works
1. The PHP code reads the **`movies.json`** file using `file_get_contents()`.
2. The JSON data is decoded into an associative array with `json_decode()`.
3. A `foreach` loop iterates over the movie data, dynamically generating rows for each movie.
4. The table displays the movie details (`title`, `year`, `genre`, `director`).

## Running the Application
1. Place the files (`index.html`, `movies.json`, and optionally `style.css`) in the root directory of your local server (e.g., `htdocs` for XAMPP or `www` for WAMP).
2. Start your local PHP server. For example, if you're using XAMPP, start Apache.
3. Access the project in your browser. Example URL:
