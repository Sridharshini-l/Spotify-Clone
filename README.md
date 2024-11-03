# 🎶 Spotify-Like Music Player

A simple, web-based music player inspired by Spotify. Built using HTML, CSS, and JavaScript, this project allows users to browse, play, pause, and skip through a playlist of songs. 

## 🚀 Project Features

- **Dynamic Playlist**: Displays a list of songs with titles and cover images, all dynamically generated from JavaScript.
- **Audio Controls**: Users can play, pause, skip to the next song, and go back to the previous song.
- **Seekbar**: A progress bar that shows the current position of the song. Users can drag the bar to skip to specific parts of the track.
- **Responsive Layout**: The UI adapts to different screen sizes to ensure an optimal experience across devices.

## 🛠️ Technologies Used

- **HTML**: For structuring the elements on the page.
- **CSS**: For styling and layout, including Flexbox for alignment and responsiveness.
- **JavaScript**: For dynamic functionality, including audio playback controls, playlist management, and DOM manipulation.

## 📂 Project Structure

```
/project-folder
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
├── script.js           # JavaScript file for functionality
├── songs/              # Folder containing audio files (.mp3)
├── covers/             # Folder containing song cover images (.jpg or .png)
└── README.md           # Project documentation
```

## 🎨 Visual Overview

The project includes the following sections:

1. **Navigation Bar**: Displays the brand logo and navigation links (e.g., Home, About).
2. **Song List**: Shows a list of songs with their names, play buttons, and cover images.
3. **Player Controls**: Includes play/pause, next, and previous buttons, as well as a seekbar to control the song progress.
4. **Currently Playing**: Displays the title of the currently playing song and a GIF to indicate play status.

## 🔧 Installation and Usage

1. Clone the repository or download the files as a ZIP.
    ```bash
    git clone https://github.com/your-username/spotify-music-player.git
    ```
2. Open the project folder and locate `index.html`.
3. Double-click `index.html` to open the project in a browser.

> **Note**: Make sure that the `songs` and `covers` folders are correctly linked and contain the required files (e.g., `1.mp3`, `2.mp3`, `1.jpg`, `2.jpg`, etc.).

## 📜 How It Works

### 1. JavaScript Functionality
- **Play/Pause**: When the play button is clicked, JavaScript toggles the play and pause states of the audio.
- **Song Switching**: The next and previous buttons allow users to navigate through the playlist.
- **Dynamic Song List**: The playlist is populated using an array of objects in JavaScript, where each object contains details about a song (name, file path, cover path).
- **Progress Bar**: As the song plays, an event listener updates the seekbar. Users can also drag the seekbar to skip to a specific time in the song.

### 2. CSS Styling
- **Flexbox**: Used for layout and alignment of elements, particularly for centering and spacing in the player.
- **Responsive Design**: Media queries are used to adjust styling for different screen sizes.
  
## 📸 Screenshots

1. **Main Page**: Shows the playlist and controls.
2. **Playing a Song**: Illustrates how the song title and play/pause button change state.

## 🚀 Future Improvements

- **Volume Control**: Add a volume slider to allow users to adjust audio levels.
- **Repeat/Shuffle**: Implement repeat and shuffle functionality for a more dynamic listening experience.
- **Search Functionality**: Allow users to search for songs in the playlist.
- **Playlist Management**: Enable users to add or remove songs from the playlist.

