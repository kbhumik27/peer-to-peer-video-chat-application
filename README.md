
# 📹 SANKET(Peer-to-Peer Video Chat Application)

A seamless **peer-to-peer video and text chat application** built with **Flask**, **Flask-SocketIO**, **HTML**, **CSS**, and **WebRTC**. This application enables direct communication between users without relying on a central server, demonstrating the power of decentralized, real-time communication.

---

## ✨ Features

- **🔗 Direct Peer-to-Peer Communication**: Connect with other users directly, bypassing the need for a central server.
- **💬 Text Chat**: Real-time messaging with an intuitive, responsive interface.
- **📹 Video Chat**: Engage in real-time video calls powered by WebRTC.
- **⚡ Real-Time Communication**: Instant message and video updates using WebSocket technology.
- **🎨 User-Friendly Interface**: Designed with HTML/CSS for an interactive and modern experience.

---

## 📖 Problem Statement

Traditional chat applications often rely on centralized servers for communication, introducing delays, privacy concerns, and scalability challenges. This application addresses these issues:

- **No Central Server**: Direct peer-to-peer communication eliminates server dependency.
- **Real-Time Messaging and Video**: Leverages WebRTC and Flask-SocketIO for instantaneous interaction.
- **Lightweight and Scalable**: Ideal for small-scale applications without heavy server overhead.

---

## 💡 Solution Overview

This application combines the following technologies for a robust peer-to-peer experience:

- **Flask** for handling HTTP requests and backend logic.
- **Flask-SocketIO** for WebSocket-based real-time communication.
- **WebRTC** for secure peer-to-peer video calling.
- **HTML/CSS** for building an intuitive user interface.

---

## 🛠️ Tech Stack

**Frontend**:
- HTML
- CSS
- WebRTC (for video calls)

**Backend**:
- Flask
- Flask-SocketIO

---

## 🚀 Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/peer-to-peer-video-chat.git
cd peer-to-peer-video-chat
```

### Step 2: Create and Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Run the Application
```bash
python app.py
```
The application will run at [http://localhost:5000](http://localhost:5000).

---

## 🎥 Usage

1. Open your browser and navigate to [http://localhost:5000](http://localhost:5000).
2. Enter your **username** to join the chat.
3. Use the chat interface to:
   - **Send messages** in real-time.
   - **Start a video call** with another user.
4. Disconnect anytime by closing the tab or clicking the disconnect button.

---

## ⚙️ Configuration

Customize settings in the `config.py` file:
```python
# config.py
SECRET_KEY = 'your_secret_key'
```
- **`SECRET_KEY`**: Used for session management.



---

## 🌟 Features Highlight: Video Chat

The video chat functionality uses **WebRTC** for establishing peer-to-peer video connections:

- **Secure Communication**: Data streams are encrypted for privacy.
- **High-Quality Video**: Automatic bitrate adjustment for smooth streaming.
- **Cross-Platform**: Works on modern web browsers (e.g., Chrome, Firefox, Edge).

---

## 🤝 Contributing

We welcome contributions to enhance this project! Follow these steps to contribute:

1. **Fork** the repository.
2. Create a feature branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add new feature"
    ```
4. Push the branch:
    ```bash
    git push origin feature-branch
    ```
5. Submit a **Pull Request**.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 🙏 Acknowledgments

- [Flask](https://flask.palletsprojects.com/) for the backend framework.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io/) for real-time communication.
- [WebRTC](https://webrtc.org/) for peer-to-peer video chat capabilities.
- HTML/CSS for crafting the user interface.

---

> **🚀 Ready to connect?** Launch the app and experience real-time peer-to-peer communication like never before!
```# 📹 Peer-to-Peer Video Chat Application

A seamless **peer-to-peer video and text chat application** built with **Flask**, **Flask-SocketIO**, **HTML**, **CSS**, and **WebRTC**. This application enables direct communication between users without relying on a central server, demonstrating the power of decentralized, real-time communication.

---

## ✨ Features

- **🔗 Direct Peer-to-Peer Communication**: Connect with other users directly, bypassing the need for a central server.
- **💬 Text Chat**: Real-time messaging with an intuitive, responsive interface.
- **📹 Video Chat**: Engage in real-time video calls powered by WebRTC.
- **⚡ Real-Time Communication**: Instant message and video updates using WebSocket technology.
- **🎨 User-Friendly Interface**: Designed with HTML/CSS for an interactive and modern experience.

---

## 📖 Problem Statement

Traditional chat applications often rely on centralized servers for communication, introducing delays, privacy concerns, and scalability challenges. This application addresses these issues:

- **No Central Server**: Direct peer-to-peer communication eliminates server dependency.
- **Real-Time Messaging and Video**: Leverages WebRTC and Flask-SocketIO for instantaneous interaction.
- **Lightweight and Scalable**: Ideal for small-scale applications without heavy server overhead.

---

## 💡 Solution Overview

This application combines the following technologies for a robust peer-to-peer experience:

- **Flask** for handling HTTP requests and backend logic.
- **Flask-SocketIO** for WebSocket-based real-time communication.
- **WebRTC** for secure peer-to-peer video calling.
- **HTML/CSS** for building an intuitive user interface.

---

## 🛠️ Tech Stack

**Frontend**:
- HTML
- CSS
- WebRTC (for video calls)

**Backend**:
- Flask
- Flask-SocketIO

---

## 🚀 Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/peer-to-peer-video-chat.git
cd peer-to-peer-video-chat
