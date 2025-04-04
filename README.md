# Journal Chat Assistant

A web-based journal and chat assistant application that can be wrapped in an Android app using MIT App Inventor.

## Features

- Chat interface with AI assistant
- Multi-user profile support
- Local journal storage
- Responsive design for both desktop and mobile
- Secure API key injection from Android wrapper

## Setup

1. Clone this repository
2. Host on GitHub Pages (Settings > Pages > Source: main branch)
3. Create an Android wrapper using MIT App Inventor:
   - Use WebViewer component to load the GitHub Pages URL
   - Implement API key injection using JavaScript interface
   - Add any desired native Android features (notifications, etc.)

## Security Note

The API key is securely stored in the Android wrapper and injected at runtime. The web application itself does not contain any sensitive information.

## Usage

1. Open the application in a web browser or through the Android wrapper
2. Create a new profile or select an existing one
3. Start chatting with the AI assistant
4. All conversations are automatically saved to your journal

## Development

The application consists of:
- `index.html`: Main application file
- `style.css`: Styling and responsive design
- No server-side components required

## License

MIT License 