# Doodler - Multiplayer Web Game 🎨

## 📚 Webster 2K23 Project Submission

- **Project Name:** Doodler

### 👥 Team Member
- **Yash Kumar** - [GitHub Profile](https://github.com/yash1721/)

## 📜 About the Project

**Doodler** is an engaging multiplayer web game that blends creativity and competition. In this game, one player draws an object, and other players race against the clock to guess what the object is. The faster and more accurately they guess, the more points they earn. Doodler challenges artistic and observational skills, offering a thrilling mix of creativity and quick thinking. It promises endless fun for players of all ages.

## 🎥 Video Demonstration

Check out the project in action: [Watch the Video](https://drive.google.com/drive/folders/1ijB97ziIfwLNaNVH4vWFgyzaD0HsueDK)

## 📸 Screenshots

Explore images from the site: [View Screenshots](https://drive.google.com/drive/folders/122Nu5mHcoJPQwgyVg9vAnTSFg_o1yeo7)

## 🚀 Current Features

- **User Authentication and Authorization:** Secure login and registration.
- **Profile Management:** Users can view and edit their profile, change avatars, names, and passwords.
- **Friend Feature:** Send and receive friend requests in real-time.
- **Chat Feature:** In-game chat and an external chat feature for real-time communication.
- **Game Modes:**
  - **Play with Friends:** Create or join rooms, invite friends with a code.
  - **Play Online:** Match with random players in real-time.
- **Multiplayer Game:** Supports up to 5 players, with one player drawing while others guess.
- **In-game Chat Moderation:** Host can restrict chat, block users for profanity.
- **Whiteboard Features:**
  - Download and share whiteboard images.
  - Drawing tools: Pencil, eraser, line, shapes (square, rectangle, circle, ellipse, trapezium), color picker, thickness adjuster.
  - Undo and Redo drawing actions.
- **Game Rounds:** Three rounds per game, with each player presenting for one minute.
- **Game History:** Automatically saved and viewable on the homepage.

## 🛠 Upcoming Features

- **Collaborative Drawing:** Work together on a single drawing.
- **Mobile Compatibility:** Play seamlessly on mobile devices.
- **AI Opponent:** Play against a computer with an ML model.
- **Advanced Drawing Tools:** More shapes and painting tools for the whiteboard.

## 💻 Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Libraries:** Socket.io, Rough.js

## 🛠 How to Run on the Local System

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/doodler.git

2. **Install Dependencies:** Navigate to the root, client, and server directories, then run:
    cd Doodler       # Navigate to the project root directory
    npm install      # Install dependencies for the root
    cd client        # Navigate to the client directory
    npm install      # Install dependencies for the client
    cd ../server     # Navigate to the server directory
    npm install      # Install dependencies for the server

3. **Setup Environment Variables:** Create a .env file in the Doodler/server directory and add your             configurations. Example .env file:
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret

4. **Run the Application:** From the Doodler directory, run:
    npm start

