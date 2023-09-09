# MERN App with Auth, Likes, Dark Mode

A MERN stack (MongoDB, Express, React, Node.js) application with user authentication, like functionality, and dark mode.

## Features

- **User Authentication**: Registration, login, and session management.
- **Likes**: Users can like posts or comments.
- **Dark Mode**: Provides a dark mode for an improved user experience in low light environments.
- **Material-UI (MUI)**: UI design using the MUI library.

## Installation and Running

1. **Install dependencies**:

```bash
yarn install
```

2. **Run the server (backend)**:

First, navigate to the server directory:

```bash
cd server
```

Then, run the server using `nodemon`:

```bash
nodemon index.js
```

3. **Run the client (frontend)**:

Open a new terminal/tab and navigate to the client directory:

```bash
cd client
```

Start the frontend application:

```bash
yarn start
```

## Configuration

**.env file**: Ensure you have a `.env` file in the root directory of the server with the necessary environment variables, for example:

```
MONGO_URL = mongodb+srv://<nameDatabse>:<password>@cluster0.szwgcwl.mongodb.net/?retryWrites=true&w=majority
JWT_SECRET = 'somesuperhardstringtoguess'
PORT = 3001
```

## Contributing

If you wish to contribute to the project, please create a Pull Request.

## License


---

Hope this helps! Adjust it as per the specific details and requirements of your project.