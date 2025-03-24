# docker-compose
This project is a Full Stack CRUD demonstration containing a MySQL database, backend (Java/Spring Boot), and frontend (React). The entire stack is containerized using Docker and Docker Compose, making it easy to set up and deploy.

🔹 Prerequisites
📌 Docker & Docker Compose installed on your machine.

🔹 Project Structure

/backend      → Spring Boot backend  
/frontend     → React/Angular frontend  
/docker-compose.yml  → Configures and runs all services  

🔹 How to Run
1️⃣ Clone the repository

git clone https://github.com/yourusername/your-repo.git
cd your-repo

2️⃣ Run the application

docker-compose up -d --build

3️⃣  Access the services

Frontend: http://localhost:3000
Backend API: http://localhost:8080
