# Random Video Player with WAV Sync

This project synchronizes a video playlist with the duration of a WAV audio file. The application selects random videos and ensures they play in sync with the audio file's duration.

## Features

- **WAV Sync**: Automatically calculates the duration of the uploaded WAV file and synchronizes the video playlist.
- **Random Video Selection**: Randomly selects videos from a predefined list without repeating the previous video consecutively.
- **Silent Video**: Ensures a seamless transition with a silent video at the end.
- **Real-Time Playback Counter**: Displays the total playback time and tracks the current playback progress.
- **Preloading**: Videos are preloaded to minimize playback delays.
- **Muted Videos**: Videos play without sound while the WAV file plays its audio.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/random-video-player.git
   ```
   
2. Navigate to the project directory:
   ```bash
    cd random-video-player
    ```
  
3. Place your video files (video1.mp4, video2.mp4, silent.mp4, etc.) in the same directory as the HTML file.
4. Open index.html in your browser.

## Usage
1. Upload a WAV audio file using the file input provided on the webpage.
2. The application will calculate the audio duration and generate a synchronized video playlist.
3. Watch the videos play in sync with the WAV file. Playback progress will be displayed in real time.


## File Structure
```
.
├── index.html         # Main HTML file
├── video1.mp4         # Example video file
├── video2.mp4         # Example video file
├── video3.mp4         # Example video file
├── silent.mp4         # Silent video file
├── README.md          # Project documentation
```

## Requirements
- A modern web browser (e.g., Chrome, Firefox, Edge) with support for:
  - HTML5
  - Web Audio API
  - JavaScript ES6
- Video.js library for video playback:
  - Video.js CDN
