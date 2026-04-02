# Video-Call-Website-
This project is a simple video calling web application built using Python (Flask), Socket.IO, and WebRTC. It allows two users to connect and communicate via real-time video and audio directly in the browser.
🚀 Features
	•	📹 Real-time video calling
	•	🎤 Audio communication
	•	🔁 Peer-to-peer connection (WebRTC)
	•	⚡ Fast signaling using Socket.IO
	•	🌐 Browser-based (no installation required)

⸻

🛠️ Technologies Used
	•	Backend: Python, Flask, Flask-SocketIO
	•	Frontend: HTML, CSS, JavaScript
	•	Real-Time Communication: WebRTC
	•	Server: Eventlet (for async handling)

project structure
video-call-app/
│
├── app.py                # Flask backend (signaling server)
├── requirements.txt      # Dependencies
│
├── templates/
│   └── index.html        # Main frontend page
│
├── static/
│   └── script.js         # WebRTC + Socket logic

  
How It Works
	1.	User opens the website
	2.	Browser requests camera & microphone access
	3.	WebRTC creates a peer connection
	4.	Flask server exchanges:
	•	Offer
	•	Answer
	•	ICE candidates
	5.	Direct video/audio stream starts between users

⸻

🔒 Requirements
	•	Modern browser (Chrome, Edge, Firefox)
	•	Camera & microphone enabled
	•	Internet connection

⸻

🚧 Limitations
	•	Works best for 2 users (no room system yet)
	•	No authentication system
	•	No TURN server (may fail on strict networks)

⸻

🌟 Future Improvements
	•	Multi-user video rooms
	•	Chat messaging feature
	•	Screen sharing
	•	User authentication
	•	Call recording
	•	Deployment on cloud (AWS / Render)
