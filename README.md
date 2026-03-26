# 🚀 Real-Time Chat Platform
This project is a **Real-Time Chat Application** built using modern web technologies that enables users to communicate instantly within chat rooms.  
It follows an **event-driven architecture** to ensure seamless and real-time interaction between users. 

## Features
-  Real-time messaging using Socket.IO  
-  Multiple chat rooms support  
-  Persistent client-server connection  
-  Instant message broadcasting  
-  Dynamic and responsive UI with React  

##  Tech Stack
- **Frontend:** React, Next.js  
- **Backend:** Node.js, Express  
- **Real-time Communication:** Socket.IO  
##  Working
The application uses an **event-driven architecture** powered by Socket.IO.  
When a user opens the app, a persistent connection is established between the client and server.

Users can join specific chat rooms, and the backend manages room membership to ensure messages are shared only within the same room.

When a message is sent, it is emitted to the server and instantly broadcast to all users in that room.  
The frontend, built with React, dynamically updates the UI as new messages arrive, ensuring a smooth and real-time user experience.

## Key Learnings
- Understanding of real-time communication using WebSockets  
- Implementation of event-driven architecture  
- Full-stack development using React and Node.js  
- Managing multiple users and chat rooms efficiently
