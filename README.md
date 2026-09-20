YouTube Clone

A YouTube-style video app built with React, Redux, and Tailwind CSS.

Live demo: [add your Vercel/Netlify link here]

Show Image

<!-- Take a screenshot of the running app, save it as screenshot.png in the project root -->
Features
Home feed with a grid of video cards
Category buttons to filter the feed
Watch page for playing a selected video
Collapsible sidebar and navbar
Live chat panel on the watch page, with state managed in Redux
Responsive layout styled with Tailwind CSS
<!-- Edit this list so it matches exactly what your app does. Remove anything it doesn't do. -->
Tech Stack
Area	Tools
UI	React (Create React App)
State management	Redux Toolkit
Routing	React Router
Styling	Tailwind CSS
Getting Started

You need Node.js installed.

bash
# 1. Clone the repository
git clone <your-repo-url>
cd <your-repo-folder>

# 2. Install dependencies
npm install

# 3. Start the app
npm start

The app opens at http://localhost:3000.

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
<!-- add one or two things that were hard or interesting -->
Future Improvements
<!-- e.g. search with suggestions, infinite scroll, dark mode -->