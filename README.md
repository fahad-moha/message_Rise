# messageRise - Chat Application
messageRise in short MssRise is chat application build with the power of MERN Stack

![messageRise Registartion](https://github.com/fahad-moha/message_Rise/assets/134622803/e4c800bb-f42f-45ca-aa27-a4d2fd78684d)



## Installation Guide

### Requirements

- Node.js
- MongoDB

Make sure both Node.js and MongoDB are installed on your system and that MongoDB is running.

1. Clone the repository:

   ```bash
   git clone https://github.com/fahad-moha/message_Rise.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-app
   ```

3. Rename the `.env.example` files to `.env`:

   ```bash
   cd public
   mv .env.example .env
   cd ..
   cd server
   mv .env.example .env
   cd ..
   ```

4. Install the dependencies:

   ```bash
   cd server
   yarn
   cd ..
   cd public
   yarn
   ```

5. Start the development server:

   - For the frontend:

     ```bash
     cd public
     yarn start
     ```

   - For the backend:

     Open another terminal in the project folder and ensure that MongoDB is running in the background.

     ```bash
     cd server
     yarn start
     ```

6. Once the server is running, open your browser and navigate to `localhost:3000` to access the chat application.

