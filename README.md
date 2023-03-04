# Live-Chat-App-using-Flask
Building a real time chat-application using  Flask and Flask-SocketIO

Flask is a lightweight framework used in Python to generate websites.
I am implementing the sockets in flask backend, (using Flask-SocketIO library) and the frontend code will be written in HTML and JavaScript

It enables a real-time communication between clients and a server using websockets. 
The application allows users to create or join chat rooms and send messages to other members in the room.

The code defines two routes: / and /room.

The / route renders a template for the home page where users can enter their name, create or join a room, and enter a room code if they choose to join an existing room.

The /room route renders a template for the chat room where users can send and receive messages.

The code uses Flask's session management to store information about the user's name and the room they have joined. 

The application runs on the localhost (i.e., http://127.0.0.1:5000) and users will need to open this URL in a web browser to access the application. 

The application is currently only accessible on the computer it is running on, and would need to be deployed to a publicly accessible web server to make it accessible to others over the internet.

Here's a video:

https://user-images.githubusercontent.com/114021638/222920583-4dccd8c7-a8db-47ec-b915-940e6c18f67f.mp4
