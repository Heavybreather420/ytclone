# Security Notice

## Environment Variables Setup

This project requires a YouTube Data API v3 key to function. **Never commit API keys to version control.**

### Setup Instructions

1. **Get a YouTube API Key**
   - Visit [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
   - Create a new project or select an existing one
   - Enable the YouTube Data API v3
   - Create credentials (API Key)
   - Restrict the key to YouTube Data API v3 only

2. **Configure Your Environment**
   - Copy `.env.example` to `.env`
   - Replace `your_api_key_here` with your actual API key
   - The `.env` file is already in `.gitignore` and will not be committed

3. **Start the Application**
   ```bash
   npm install
   npm start
   ```

### Note to Contributors

If you find any exposed API keys or sensitive data in this repository, please report it immediately by opening a private security advisory on GitHub.
