# RealTime_ChatApp

A simple yet efficient real-time chat application built using Node.js and Socket.IO. The application allows users to join chatrooms, interact with other participants, and leave the room while maintaining a seamless and interactive experience.


Features:
--------

Landing Page:
--------------
The landing page provides the following options:

- Display Name: Enter your display name, which will appear in the chatroom.
- Room Selection: Choose the chatroom you want to join from a dropdown or text input field.


Chatroom
--------

- Once you select a display name and chatroom, you will be redirected to the chatroom page.
- Multiple users can join the same room simultaneously and interact in real time.
- Messages sent in the chatroom are instantly broadcasted to all members of the room using Socket.IO for real-time communication.
- Each chatroom is isolated, ensuring that messages are confined to the respective room.


Leaving the Room
----------------
- You can leave the chatroom at any time by clicking the Leave Room button.
- Upon leaving:
- Your display name and messages will no longer appear in the chatroom.
- All your chat data will be cleared from the room.


Additional Features
-------------------
- Buttons on the landing page showcase additional information about My skills and projects.


Tech Stack
----------
- Node.js: Used as the backend runtime environment for server-side functionality.
- Socket.IO: Facilitates bi-directional communication between the server and clients in real time.


Installation & Setup
-------------------

Follow the steps below to set up the application locally on your system:

Clone the Repository
- git clone https://github.com/SUYASHHAGARWAL/RealTime_ChatApp.git  
- cd RealTime_ChatApp  
- Install Dependencies - npm install 
- Run the Server - npm start  

Access the Application
- http://localhost:3000 



How It Works
-----------
- Landing Page: Choose your display name and the room you'd like to join.
- Join Room: Enter the selected chatroom to interact with other participants.
- Real-Time Updates: All messages are instantly updated for all users in the room.
- Leave Room: Exit the room when done; your chats will not persist.