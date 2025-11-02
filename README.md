# YouTube TV Banner Viewer

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CORS Proxy](https://img.shields.io/badge/CORS_Proxy-4A90E2?style=for-the-badge&logo=server&logoColor=white)
![Web App](https://img.shields.io/badge/Web_App-00C853?style=for-the-badge&logo=googlechrome&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

A web-based tool for previewing YouTube channel banners and profile pictures with responsive layout visualization across different device views and download capability.

## Related Tools

- [Main Banner Editor](../README.md) - Create and customize YouTube banners
- [Thumbnail Viewer](thumbnail-viewer.md) - Preview YouTube video thumbnails in various resolutions

## Features

- **Channel Preview**: Fetch and display YouTube channel banners and profile pictures
- **Multiple Layouts**: 
  - Full Image (TV) - 2560 × 1440
  - Desktop View - 2560 × 423 (masked view)
  - Tablet View - 1855 × 423 (masked view)
  - Mobile View - 1546 × 423 (masked view)
  - Full Image with View Lines - 2560 × 1440 (overlay indicators)
- **Sequential Layout Switching**: Cycle through layouts with a single button
- **Banner Download**: Download channel banners in high resolution
- **Real-time Preview**: See channel banners instantly as you enter URLs
- **Responsive Design**: Works on different screen sizes
- **Channel Information**: Displays channel name and subscriber count
- **Tool Switching**: Easily switch between the TV Viewer, Banner Editor, and Thumbnail Viewer
- **User-Friendly Interface**: Modern UI with clear feedback for all actions

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Running the Application

1. Open `TV-banner-viewer.html` directly in your web browser
2. Enter a YouTube channel URL in the input field
3. Click "View Channel" or press Enter to load the channel data

## How to Use

1. **Enter Channel URL**: Paste a YouTube channel URL (e.g., `https://www.youtube.com/@channelname`)
2. **View Channel**: Click "View Channel" or press Enter to fetch and display the banner
3. **Change Layout**: Click the "Layout" button to cycle through different views:
   - Full Image: Shows the complete 2560×1440 banner
   - Desktop View: Shows only the desktop-safe area with masking
   - Tablet View: Shows only the tablet-safe area with masking
   - Mobile View: Shows only the mobile-safe area with masking
   - Full with Lines: Shows the full banner with overlay indicators for all device views
4. **Download Banner**: Click "Download Banner" to save the channel banner image
5. **Switch Tools**: Use the "Switch to Thumbnail Viewer" button to access the thumbnail viewer, or "Switch to Banner Editor" to access the main editor
6. **Responsive Controls**: The interface adapts to different screen sizes

## Layout Descriptions

- **Full Image**: Displays the complete YouTube banner at 2560×1440 resolution
- **Desktop View**: Masks the banner to show only the 2560×423 area visible on desktop
- **Tablet View**: Masks the banner to show only the 1855×423 area visible on tablets
- **Mobile View**: Masks the banner to show only the 1546×423 area visible on mobile devices
- **Full with Lines**: Displays the full banner with colored overlay lines indicating the safe areas for each device type

## Technical Features

- **CORS Proxy**: Uses `corsproxy.io` to fetch channel data
- **Banner Download**: Enables downloading of high-resolution channel banners
- **Image Optimization**: Automatically resizes images to optimal dimensions
- **Error Handling**: Displays user-friendly error messages for invalid URLs or private channels
- **Loading States**: Shows spinner and status messages during data fetching
- **Responsive UI**: Adapts layout for mobile and tablet devices
- **Keyboard Support**: Press Enter to fetch channel data after entering a URL

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Built With

- HTML5
- CSS3 (with advanced features like clip-path and box-shadow)
- JavaScript (ES6+ with async/await)
- [corsproxy.io](https://corsproxy.io/) - For bypassing CORS restrictions

## Author

Joshua Pavia Basco

## License

This project is free to use and modify.