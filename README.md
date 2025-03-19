Overview
This web application allows users to search for movies using the OMDB API, view detailed information about each movie, and maintain a watchlist of favorite movies. The application is built using HTML, CSS, and JavaScript, and it leverages the OMDB API to fetch movie data.

Features
Search for Movies: Users can search for movies by typing the movie name in the search bar.

View Movie Details: Clicking on a movie from the search results or watchlist will display detailed information about the movie, including its plot, cast, ratings, and more.

Add to Watchlist: Users can add movies to their watchlist, which is stored in the browser's local storage.

Remove from Watchlist: Users can remove movies from their watchlist.

Responsive Design: The application is designed to be responsive and works well on both desktop and mobile devices.

Prerequisites
Before running the application, ensure you have the following:

A modern web browser (e.g., Google Chrome, Mozilla Firefox, Safari).

An active internet connection (to fetch data from the OMDB API).

How to Run the Application
Download the Project: Clone or download the project repository to your local machine.

Open the Project Folder: Navigate to the project folder where the HTML, CSS, and JavaScript files are located.

Run the Application:

Open the index.html file in your web browser by double-clicking it or dragging it into your browser window.

Alternatively, you can use a local server to run the application. For example, if you have Python installed, you can run the following command in the project directory:

bash
python -m http.server
Then, open your browser and navigate to http://localhost:8000.

Search for Movies: Type the name of a movie in the search bar and press Enter or click the search icon. The search results will be displayed below the search bar.

View Movie Details: Click on any movie from the search results to view its detailed information.

Add to Watchlist: While viewing a movie's details, click the bookmark icon to add the movie to your watchlist.

View Watchlist: Navigate to the "Watchlist" page by clicking the "Watchlist" link in the header. Here, you can view all the movies you've added to your watchlist.

Remove from Watchlist: On the "Watchlist" page, click the trash icon next to a movie to remove it from your watchlist.

Project Structure
index.html: The main HTML file that contains the structure of the home page.

movie.html: The HTML file that displays detailed information about a selected movie.

favorite.html: The HTML file that displays the user's watchlist.

style.css: The CSS file that contains all the styling for the application.

script.js: The JavaScript file that contains the logic for fetching data from the OMDB API, handling user interactions, and managing the watchlist.

API Key
The application uses the OMDB API to fetch movie data. The API key used in this project is ddfbf9c2. If you want to use your own API key, you can sign up for one at OMDB API and replace the key in the script.js file.

Deployment to GitHub Pages
To deploy this application to GitHub Pages, follow these steps:

Create a GitHub Repository: Create a new repository on GitHub and push your project files to it.

Enable GitHub Pages:

Go to the repository settings on GitHub.

Scroll down to the "GitHub Pages" section.

Select the main branch (or the branch where your project files are located) and click "Save".

Access Your Application: Once GitHub Pages is enabled, you can access your application using the URL provided in the GitHub Pages section.
