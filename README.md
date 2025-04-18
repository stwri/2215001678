# Social Media Analytics Frontend Web Application

## Overview
This project is a React-based frontend web application designed for social media analytics. It provides real-time insights into user behavior by displaying data retrieved from a social media platform's API. The application is intended for business stakeholders who need to monitor user interactions without requiring user registration or login.

## Features
- **Top Users**: Displays the top five users with the most commented posts.
- **Trending Posts**: Shows the post(s) with the maximum number of comments.
- **Feed**: A dynamic feed that displays posts in real-time, with the newest posts appearing at the top.

## Project Structure
```
social-media-analytics
├── public
│   ├── index.html
│   └── favicon.ico
├── src
│   ├── components
│   │   ├── Feed.tsx
│   │   ├── TopUsers.tsx
│   │   ├── TrendingPosts.tsx
│   │   └── common
│   │       ├── Header.tsx
│   │       └── Footer.tsx
│   ├── services
│   │   └── api.ts
│   ├── utils
│   │   └── helpers.ts
│   ├── App.tsx
│   ├── index.tsx
│   └── styles
│       └── global.css
├── package.json
├── tsconfig.json
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd social-media-analytics
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the application:
   ```
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage
- Navigate through the application using the header links to access the Top Users, Trending Posts, and Feed pages.
- The Feed page will update in real-time to reflect new posts as they are fetched from the backend.

## Technologies Used
- React
- TypeScript
- CSS
- Axios (for API calls)

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.