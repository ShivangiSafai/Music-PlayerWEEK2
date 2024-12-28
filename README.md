# Music-PlayerWEEK-2
The week2 task submission under Edunet Foundation in collaboration with EY GDS AND AICTE.

# Folder Structure

spotify-clone/ ├── backend/ │ ├── node_modules/ │ ├── src/ │ │ ├── routes/ │ │ │ ├── auth.js │ │ │ └── user.js │ │ ├── controllers/ │ │ │ ├── authController.js │ │ │ └── userController.js │ │ ├── models/ │ │ │ ├── User.js │ │ └── app.js │ ├── .env │ ├── package.json │ ├── package-lock.json │ └── README.md ├── frontend/ │ ├── node_modules/ │ ├── public/ │ │ ├── index.html │ │ └── favicon.ico │ ├── src/ │ │ ├── assets/ │ │ │ ├── images/ │ │ │ └── styles/ │ │ │ └── tailwind.css │ │ ├── components/ │ │ │ ├── Header.js │ │ │ └── Footer.js │ │ ├── pages/ │ │ │ ├── Login.js │ │ │ └── Register.js │ │ ├── App.js │ │ └── index.js │ ├── .env │ ├── tailwind.config.js │ ├── package.json │ ├── package-lock.json │ └── README.md ├── .gitignore └── README.md

# Tech Stack Used
Here are the technologies used in the Spotify Clone project, categorized point-wise:

Backend (Express.js)

Node.js: Runtime environment for executing JavaScript on the server.

Express.js: Lightweight web application framework for building REST APIs.

MongoDB (or another database): NoSQL database for storing user and playlist data.

Mongoose: ODM library for MongoDB, simplifies schema and query definitions.

Dotenv: For managing environment variables securely.

JSON Web Tokens (JWT): For user authentication and session management.

Bcrypt.js: For hashing and securely storing passwords.

Cors: Middleware for handling cross-origin requests between frontend and backend.

Frontend (React with Tailwind CSS)

React.js: Frontend library for building user interfaces.

Tailwind CSS: Utility-first CSS framework for styling components.

Axios: For making HTTP requests to the backend API.

React Router: For managing routing and navigation between pages.

Vite or Create React App: For bootstrapping the React project.

General Tools and Platforms

Git and GitHub: Version control and repository management.

Postman: API testing tools for backend endpoints.

Visual Studio Code: Code editor for development.

Task Details
Week two task was to create a beautiful and functional UI for a Spotify clone music player website. The task involved designing pages that closely resembled the original Spotify interface while ensuring smooth navigation and an engaging user experience. The UI included a visually appealing layout with a side navigation pane that provided easy access to various sections such as Home, Playlists, Albums, and Songs. The navigation pane, inspired by Spotify’s design, added a professional touch and enhanced usability.

To manage the music data effectively, routes were added for seamless navigation between different sections. Users could view albums, playlists, and individual songs with the help of structured routes. Each album and playlist displayed relevant details, such as thumbnails and artist names, to provide a more immersive experience. The thumbnails were carefully designed to maintain consistency with the overall theme and design of the website, giving it an authentic and polished appearance.

The task also required integrating backend functionality to fetch and display music data. For this, I used Postman to test and verify API endpoints that supported operations like fetching all albums, viewing a specific album, retrieving playlists, and displaying all songs. These endpoints were crucial for ensuring the application could dynamically update and show the correct data in the UI. The interaction with Postman allowed for efficient debugging and validation of the API responses, ensuring that the application worked smoothly.

The playlist view provided an overview of the available playlists, while the individual song view displayed the song details, including its thumbnail and artist name. The GUI was carefully crafted to ensure responsiveness and compatibility with various devices, providing an optimal user experience across different screen sizes.

Overall, this task required balancing aesthetics and functionality to create a visually appealing and feature-rich music player website. By the end of week two, I successfully completed all the requirements, including designing the UI, adding routes for navigation, testing API endpoints with Postman, and integrating dynamic data for albums, playlists, and songs. The project was completed with a high level of detail and precision, closely resembling the original Spotify website. I have done it.
