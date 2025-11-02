# YouTube Thumbnail Viewer

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CORS Proxy](https://img.shields.io/badge/CORS_Proxy-4A90E2?style=for-the-badge&logo=server&logoColor=white)
![Web App](https://img.shields.io/badge/Web_App-00C853?style=for-the-badge&logo=googlechrome&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

A web-based tool for previewing YouTube video thumbnails in various resolutions with download capability.

## Related Tools

- [Main Banner Editor](README.md) - Create and customize YouTube banners
- [TV Banner Viewer](README.md) - Preview YouTube channel banners across different device layouts

## Features

- **Thumbnail Preview**: Fetch and display YouTube video thumbnails in multiple resolutions
- **Multiple Quality Options**: View thumbnails in Maximum, Standard, High, Medium, and Default qualities
- **Thumbnail Download**: Download any thumbnail in its original quality
- **Video Navigation**: Direct link to the YouTube video page
- **Real-time Preview**: See thumbnails instantly as you enter video URLs or IDs
- **Responsive Design**: Works on different screen sizes
- **Tool Switching**: Easily switch between the Thumbnail Viewer, Banner Editor, and TV Viewer
- **User-Friendly Interface**: Modern UI with clear feedback for all actions

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Running the Application

1. Open `thumbnail-viewer.html` directly in your web browser
2. Enter a YouTube video URL or ID in the input field
3. Click "Get Thumbnails" or press Enter to load the thumbnails

## How to Use

1. **Enter Video URL or ID**: Paste a YouTube video URL (e.g., `https://www.youtube.com/watch?v=videoID`) or just the video ID
2. **Get Thumbnails**: Click "Get Thumbnails" or press Enter to fetch and display available thumbnails
3. **Preview Thumbnails**: View all available thumbnail resolutions in a grid layout
4. **Download Thumbnails**: Click "Download Image" under any thumbnail to save it
5. **View Images**: Click "View Image" to open the thumbnail in a new tab
6. **See Video**: Click "See Video" to go directly to the YouTube video page
7. **Switch Tools**: 
   - Use the "Switch to TV Viewer" button to access the TV banner viewer
   - Use the "Switch to Banner Editor" button to access the main editor

## Technical Features

- **Video ID Parsing**: Automatically extracts video IDs from various YouTube URL formats
- **Thumbnail Validation**: Checks which thumbnail resolutions are available for each video
- **Download Functionality**: Enables downloading of thumbnails with proper filenames
- **Error Handling**: Displays user-friendly error messages for invalid URLs or unavailable videos
- **Loading States**: Shows spinner and status messages during thumbnail fetching
- **Responsive UI**: Adapts layout for mobile and tablet devices
- **Keyboard Support**: Press Enter to fetch thumbnails after entering a URL

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Built With

- HTML5
- CSS3
- JavaScript (ES6+ with async/await)
- [corsproxy.io](https://corsproxy.io/) - For bypassing CORS restrictions

## Author

Joshua Pavia Basco

## License

This project is free to use and modify.