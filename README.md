# QuizForge

QuizForge is a web-based platform for creating, sharing, and taking quizzes in real-time. It supports user authentication, quiz building, live participation, and score tracking.

## Features
- User registration and login
- Quiz creation and editing
- Real-time quiz participation
- Score tracking and leaderboard
- RESTful API backend (Node.js, Express)
- MongoDB database integration

## Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Arpit-tech-ai/quiz-forge.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your MongoDB connection in `config/db.js`.
4. Start the server:
   ```bash
   node server.js
   ```
5. Open `public/index.html` in your browser.

## Folder Structure
- `server.js` - Main server file
- `routes/` - API route handlers
- `models/` - Mongoose models
- `middleware/` - Custom middleware
- `public/` - Frontend files (HTML, CSS, JS)
- `config/` - Configuration files

## License
MIT
