
                                       
                                       🔄 Sync Code: Real-Time Collaborative Code Editor

Code together. Debug together. Ship faster — together.

Sync Code is a powerful and intuitive real-time collaborative code editor built for developers and teams. Whether you're working remotely or side-by-side, Sync Code empowers seamless and instant collaboration.

🚀 Features
👥 Real-time Collaboration: Multiple users can join a room and edit code together.

⚡ Instant Sync: Code updates appear across all clients in real time.

📋 Room ID Copy: Easily copy room ID to share with others.

🚪 Join/Leave Room: Users can leave and rejoin rooms without losing progress.

🌈 Syntax Highlighting: Supports various programming languages.

🖌️ Theme Options: Choose a theme based on your preference.

🔔 User Presence Indicator: Join and leave notifications in real-time.

🛠️ Tech Stack
Frontend: React.js, CodeMirror, React-Toastify

Backend: Node.js, Express.js, Socket.io

Others: Docker, PM2, .env configuration

🧩 Prerequisites
🔧 For Docker:
Docker (v25.0.4)

Docker Compose (v1.29.2)

🔧 For Local Setup:
Node.js (v20.11.1)

npm (v10.2.4)

pm2 (v5.3.1)
Install using: npm i -g pm2

📌 Note: Node version managed using nvm (v0.39.7)

🐳 Running with Docker (Recommended)
Install Docker

Pull Docker Image

bash
Copy
Edit
docker pull mohitur/code-editor
Run the Container

bash
Copy
Edit
docker run -p 8000:8000 -p 3000:3000 -p 5000:5000 mohitur/code-editor
Visit http://localhost:3000

Create Room, copy Room ID and share

Join as another user (incognito or new browser)

💡 Tip: If using Linux/WSL2, add sudo to Docker commands.

🛠️ Build and Run Your Own Docker Image
Clone the repo:

bash
Copy
Edit
git clone https://github.com/SagarKumarSah923/collab-code-editor.git
cd collab-code-editor
Edit .env and docker-compose.yml (replace your Docker username).

Build & run:

bash
Copy
Edit
docker-compose up -d
Open http://localhost:3000 and follow the steps above.

💻 Running Locally (Dev Mode)
Clone and navigate:

bash
Copy
Edit
git clone https://github.com/SagarKumarSah923/collab-code-editor.git
cd collab-code-editor
Install dependencies:

bash
Copy
Edit
npm install
Create .env from example.env and fill required credentials.

Start the frontend:

bash
Copy
Edit
npm start
Start the backend:

bash
Copy
Edit
npm run server:dev
# OR using PM2
pm2 start server.js
Open http://localhost:3000 and start collaborating!

🛑 To stop:

bash
Copy
Edit
Ctrl + C  # for regular server
pm2 stop server.js  # if using pm2
📹 Project Video
👉 Watch Project Demo

🧪 Future Scope
🔒 Authentication and Authorization

💬 In-room Chat

📁 Code Saving and Download

📊 Collaborative Terminal

🧠 AI-Powered Suggestions (Copilot-like)

🤝 Open Source Contributions Welcome!
🔧 Steps to Contribute
bash
Copy
Edit
# Fork the repository
git clone https://github.com/YOUR_USERNAME/collab-code-editor.git
cd collab-code-editor

# Create a new branch
git checkout -b feature/your-feature-name

# Make your changes and commit
git add .
git commit -m "Your meaningful commit message"

# Push your branch
git push origin feature/your-feature-name
Then, create a Pull Request from your forked repo.
📌 Note: Always use your own branch for contributing.

🙋‍♂️ About Me
I’m Sagar Kumar Sah, a tech enthusiast and B.Tech CSE student passionate about building collaborative tools for developers.

💼 LinkedIn

💻 GitHub

📌 License
This project is licensed under the MIT License.
