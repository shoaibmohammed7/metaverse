# Metaverse Project

This project is an innovative and immersive web development endeavor that aims to create a virtual space where users can explore and experience the possibilities of the metaverse. It combines cutting-edge technologies and creative design to provide a captivating and interactive user experience.


---

## Features

1. **Virtual Space Navigation**
   - Users can move around in virtual spaces using coordinates.

2. **Real-Time Communication**
   - Live events such as join, leave, and movement are broadcast to other users.

3. **Interactive WebSocket API**
   - A well-defined schema for client-sent and server-sent events ensures smooth communication.

4. **Error Handling**
   - Movement rejection based on collisions and boundaries.

5. **Test-Driven Development (TDD)**
   - Includes comprehensive tests to ensure reliability and maintainability of the codebase.


## Running the Project Locally. Setup and Installation  

1. Clone the repository:

   ```bash
   git clone <https://github.com/shoaibmohammed7/metaverse/>
   cd metaverse
   ```

2.Install dependencies for all components:

```bash
cd ../ws
npm install

cd ../http
npm install

cd ../frontend
npm install

```


Running the Project

1.Start the WebSocket server:

```bash
cd websocket-server
npm run dev

```

2. Start the HTTP server:

```bash
cd http-server
npm run dev
```

3. Start the frontend application:
```bash
cd frontend
npm run dev

```

4.Access the application in your browser at http://localhost:3001
