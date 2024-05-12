# Real-Time Chat Platform

Welcome to our real-time chat platform, where connectivity meets modern technology. Engage in lively conversations, create groups, and stay notified—all in real-time!

🌟 Enjoying the experience? Give us a Star on GitHub!


## Built With Passion Using

- **MERN Stack**: MongoDB, Express.js, React.js, Node.js
- **Real-Time Engine**: Socket.io
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS

## Exciting Features

- **Instant Messaging**: Experience seamless real-time chatting.
- **Secure Authentication**: Sign up/in with JWT or Google Auth.
- **Group Chats**: Create rooms and invite friends.
- **Notifications**: Never miss a message.
- **Emojis**: Express more with a range of emojis.
- **Personalized Profiles**: Update avatars and display names.
- **Search & Discover**: Find rooms and users effortlessly.
- **Responsive Design**: Perfect on any device.

## Get Started

To set up the project locally:

1. Fork and clone the repo or download the zip file.
2. Open the project in your preferred code editor.
3. Split your terminal: one for the client and one for the server.

### Client Setup

Navigate to the client directory and create a `.env` file:

```env
REACT_APP_GOOGLE_CLIENT_ID=your-google-client-id
REACT_APP_SERVER_URL=http://localhost:8000

To obtain your Google Client ID:

Visit the Google Cloud Credentials Page.
Create credentials > OAuth client ID.
Select ‘Web application’ and name your OAuth client.
Set the redirect URLs to http://localhost:3000 and http://localhost:3000/login.
Copy the Client ID to your .env file.
Install and start the client:

cd client
npm install
npm start

Server Setup
In the server directory, create a .env file with:

PORT=8000
URL=your-database-url
SECRET=your-secret
CLIENT_ID=your-google-client-id
BASE_URL=http://localhost:3000

Install and start the server:

cd server
npm install
npm start