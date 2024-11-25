

---

# Social Media Application

This is a **real-time social media application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) with additional real-time features powered by **Socket.IO**. The application allows users to share posts, interact through likes and comments, and engage in real-time chat functionality.

## Features

- **Post Creation:** Users can create posts to share their experiences and thoughts.
- **Interactive Features:** Like and comment on posts to engage with others.
- **Real-Time Chat:** Chat with friends using an integrated real-time messaging feature.
- **Responsive Design:** Fully responsive UI for seamless use across devices.
- **Secure Authentication:** User authentication with JWT for secure login and data privacy.
- **Scalable Architecture:** Separation of client, server, and socket functionalities for efficient development and scaling.

## Project Structure

The project is organized into three main directories:

1. **Client:**
   - Built with React.js for a dynamic and responsive user interface.
   - State management using Redux.
   - Axios for API communication with the server.

2. **Server:**
   - Back-end REST API built with Node.js and Express.js.
   - MongoDB as the database for storing user data, posts, and chat history.
   - Secure JWT-based authentication.

3. **Socket:**
   - Real-time communication using Socket.IO.
   - Enables real-time chat and notifications for likes, comments, and friend requests.

## Tech Stack

### Front-End
- **React.js**
- **Redux** (for state management)
- **Material-UI** (for styling)
- **Axios** (for API integration)

### Back-End
- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose** (for database modeling)
- **JWT** (for authentication)

### Real-Time Features
- **Socket.IO** (for real-time updates and messaging)

## Installation

Follow the steps below to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mandeep32/Social-Media-Application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd social-media-application
   ```

3. Install dependencies for all folders:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   cd ../socket
   npm install
   ```

4. Start the development servers:
   - **Client:** `npm start` (inside the `client` folder)
   - **Server:** `npm start` (inside the `server` folder)
   - **Socket:** `npm start` (inside the `socket` folder)

5. Access the application at `http://localhost:3000`.

## Screenshots

Include screenshots of the application to showcase:
- The homepage
- A post with likes and comments
- The real-time chat interface

## Future Enhancements

- Add group chat functionality.
- Implement advanced search and filter options for posts.
- Integrate push notifications for real-time updates.
- Add profile customization features for users.

## License

This project is licensed under the MIT License. Feel free to use and modify the code.

---
