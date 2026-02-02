# Hotstar Clone – DevSecOps Project (Node.js)

This repository contains a Hotstar-style application created to practice DevOps and DevSecOps concepts using Node.js, Docker, and container security scanning.

---

## 📌 Project Purpose

The purpose of this project is to gain hands-on experience with:

- Containerizing a Node.js application using Docker
- Applying DevSecOps best practices
- Scanning Docker images for vulnerabilities
- Understanding CI/CD pipeline workflows
- Learning real-world DevOps practices

---

## 🛠 Tech Stack

- Node.js
- Docker
- Docker Scout
- Git & GitHub
- CI/CD (GitHub Actions – optional)

---

## 📁 Project Structure

Hotstar-DevOps-Project-NodeJS/  
├── Dockerfile  
├── package.json  
├── package-lock.json  
├── server.js  
├── public/  
├── views/  
└── README.md  

---

## 🚀 Getting Started

### Clone the Repository

git clone https://github.com/RKVankini/Hotstar-DevOps-Project-NodeJS.git  
cd Hotstar-DevOps-Project-NodeJS  

---

### Install Dependencies

npm install  

---

### Run the Application

npm start  

Open your browser and visit:  
http://localhost:8080  

---

## 🐳 Run Using Docker

### Build Docker Image

docker build -t hotstar-devsecops .  

---

### Run Docker Container

docker run -p 8080:8080 hotstar-devsecops  

---

## 🛡 Security Scan Using Docker Scout

docker scout quick hotstar-devsecops  

This command scans the Docker image and reports known vulnerabilities along with remediation insights.

---

## ⚙ CI/CD Integration

This project supports CI/CD pipelines using:

- GitHub Actions  
- GitLab CI  
- Jenkins  

Typical CI/CD stages include:

- Source code checkout  
- Dependency installation  
- Docker image build  
- Security scanning  
- Deployment  

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Dockerizing a Node.js application  
- Implementing DevSecOps security scanning  
- Understanding CI/CD pipeline stages  
- Following secure and scalable DevOps practices  
- Managing projects using GitHub  

---

## 📚 Reference

DevSecOps tutorial and blog:  
https://mrcloudbook.com/devsecops-ci-cd-deploying-a-secure-hotstar-clone-even-if-youre-not-a-pro/

---

## 👤 Author

Rama Krishna Vankini  
GitHub: https://github.com/RKVankini  

---

## 📜 License

This project is created for educational and learning purposes.
