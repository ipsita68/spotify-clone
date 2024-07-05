
# Spotify Clone React App

This project is a Spotify-based web application built with React. It allows users to authenticate with Spotify, view their playlists, and interact with the Spotify API.

## Features

- User authentication via Spotify
- Fetch and display user information and playlists
- Play music directly from the app
- Responsive and user-friendly design

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/spotify-react-app.git
    cd spotify-react-app
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
    ```sh
    REACT_APP_SPOTIFY_CLIENT_ID=your_spotify_client_id
    REACT_APP_SPOTIFY_REDIRECT_URI=http://localhost:3000/callback
    REACT_APP_BACK_URI=http://localhost:8888
    ```

4. **Start the development server:**
    ```sh
    npm start
    ```

## Usage

- Navigate to `http://localhost:3000` in your web browser.
- Click on the "Login with Spotify" button to authenticate.
- Once authenticated, you will see your Spotify profile information and playlists.

## Project Structure

```plaintext
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── components
│   │   ├── sidebar-components
│   │   │   ├── Sidebar.js
│   │   │   ├── Logo.js
│   │   │   ├── NavList.js
│   │   │   ├── NavItem.js
│   │   │   ├── PlayLists.js
│   │   │   ├── FeaturedPlaylist.js
│   │   │   ├── FeaturedItem.js
│   │   │   ├── OtherPlaylist.js
│   │   │   └── InstallCTA.js
│   │   ├── footer-components
│   │   │   ├── Footer.js
│   │   │   ├── CTAbanner.js
│   │   │   └── Player.js
│   │   ├── featured-components
│   │   │   ├── Featured.js
│   │   │   └── Loading.js
│   ├── utilities
│   │   ├── getHashParams.js
│   │   ├── reqWithToken.js
│   │   └── context.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md
```
## Environment Variables

- REACT_APP_SPOTIFY_CLIENT_ID: Your Spotify application's client ID.
- REACT_APP_SPOTIFY_REDIRECT_URI: The redirect URI set in your Spotify application settings.
- REACT_APP_BACK_URI: The backend URI for handling the refresh token.

## Screenshot of app
![image](https://github.com/ipsita68/spotify-clone/assets/121110612/a7115bc6-537f-425c-b68d-95f7feee94ea)
