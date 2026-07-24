Spotify Backend

This project is a backend API for a Spotify Clone built using Node.js, Express.js, and MongoDB. It provides APIs for user authentication, music upload, album management, and music streaming features.

Features

- User Registration & Login
- JWT Authentication
- Upload Songs
- Create Albums
- Fetch All Songs
- Store Files using ImageKit
- MongoDB Database Integration
- REST API Architecture

Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer
- ImageKit
- dotenv

Installation

Clone the repository

```bash
git clone https://github.com/priyanshugupta12012006-max/spotify-project.git
```

Move into the project

```bash
cd spotify-project
```

Install dependencies

```bash
npm install
```

Create a `.env` file in the root folder and add:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
```

Start the server

```bash
npm start
```

or

```bash
npm run dev
```

API Routes

Authentication

- POST /api/auth/register
- POST /api/auth/login

Music

- POST /api/music/upload
- GET /api/music

Album

- POST /api/music/album
- GET /api/music/albums

Project Structure

```
src/
│── controllers/
│── models/
│── routes/
│── middlewares/
│── services/
│── db/
│── app.js

server.js
package.json
```

Author

Priyanshu kumari
