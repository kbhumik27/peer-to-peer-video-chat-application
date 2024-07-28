# peer-peer-chat-application
a peer to peer chat application built using flask,html and css
Peer-to-Peer Chat Application
Peer-to-Peer Chat Application is a simple and efficient chat application that enables direct communication between users without the need for a central server. Built using Flask for the backend and HTML/CSS for the frontend, this application demonstrates the fundamentals of peer-to-peer communication in a web-based chat environment.

Features
Direct Messaging: Send and receive messages directly between peers.
User-Friendly Interface: Intuitive and responsive chat interface built with HTML and CSS.
Real-Time Communication: Utilizes Flask-SocketIO for real-time messaging.
Problem Statement
Traditional chat applications often rely on central servers to handle message exchanges, which can introduce delays and scalability issues. This peer-to-peer chat application addresses the following challenges:

Central Server Dependency: Eliminates the need for a central server by enabling direct communication between users.
Scalability: Demonstrates a lightweight approach to chat systems that can be scaled for small groups without server overhead.
Real-Time Messaging: Provides real-time message delivery and interaction.
Proposed Solution
This chat application uses Flask to handle HTTP requests and WebSocket communication via Flask-SocketIO to facilitate real-time messaging between peers. HTML and CSS are used to create a simple, yet effective user interface.

Tech Stack
Frontend:

HTML
CSS
Backend:

Flask (Python web framework)
Flask-SocketIO (WebSocket for real-time communication)
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/peer-to-peer-chat-application.git
cd peer-to-peer-chat-application
Create and Activate a Virtual Environment

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Run the Application

bash
Copy code
python app.py
The application will start running on http://localhost:5000.

Usage
Access the Chat Application

Open your web browser and navigate to http://localhost:5000 to access the chat application.

Connect and Chat

Enter your username and connect to the chat.
Use the chat interface to send and receive messages in real-time.
Configuration
You can configure the application settings by editing the config.py file:

python
Copy code
# config.py
SECRET_KEY = 'your_secret_key'
"SECRET_KEY": Set a secret key for Flask session management.
Contributing
We welcome contributions to improve the Peer-to-Peer Chat Application! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Flask: Flask Documentation
Flask-SocketIO: Flask-SocketIO Documentation
HTML/CSS: Basic HTML and CSS for front-end design.
