YouTube Clone

A YouTube-style video app built with React, Redux, and Tailwind CSS.




Features
Home feed with a grid of video cards
Category buttons to filter the feed
Watch page for playing a selected video
Collapsible sidebar and navbar
Live chat panel on the watch page, with state managed in Redux
Responsive layout styled with Tailwind CSS
Tech Stack
Area	Tools
UI	React (Create React App)
State management	Redux Toolkit
Routing	React Router
Styling	Tailwind CSS
Getting Started

### Prerequisites
- Node.js installed
- YouTube Data API v3 key ([Get one here](https://console.cloud.google.com/apis/credentials))

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Heavybreather420/ytclone.git
cd ytclone

# 2. Install dependencies
npm install

# 3. Set up environment variables
# Copy the example file
cp .env.example .env

# Edit .env and add your YouTube API key:
# REACT_APP_YOUTUBE_API_KEY=your_api_key_here

# 4. Start the app
npm start
```

The app opens at http://localhost:3000.

> **Note:** You must provide your own YouTube API key in the `.env` file for the app to work.

Project Structure
src/
├── components/   # Navbar, Sidebar, Feed, Watch, LiveChat, VideoContainer, etc.
├── constant/     # Shared constants and API config
├── utils/        # Redux store and slices (app state, chat state), helper functions
├── App.js
└── index.js
What I Learned
Structuring a React app into small, reusable components
Managing shared state with Redux slices
Building responsive layouts with Tailwind CSS
