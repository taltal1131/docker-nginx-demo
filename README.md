# 🐳 Docker Nginx Demo

This is a simple demo project showing how to run a static website using **Nginx inside Docker**.  
Great for beginners in DevOps, Docker, and web deployment!

---

## 📂 Project Structure

.
├── Dockerfile # Nginx Docker image
├── index.html # Static homepage
└── README.md

yaml
Copy
Edit

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/taltal1131/docker-nginx-demo.git
   cd docker-nginx-demo
Build the Docker image:

bash
Copy
Edit
docker build -t nginx-demo .
Run the container:

bash
Copy
Edit
docker run -d -p 8080:80 nginx-demo
Open in browser:
Visit http://localhost:8080

🔧 Technologies Used
Docker 🐳

Nginx 🌐

HTML

📄 License
This project is open-source and free to use under the MIT License.

<p align="center"> 🚀 Built with ❤️ by <a href="https://github.com/taltal1131">taltal1131</a> </p> ```
