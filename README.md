# 🚀 Flask CI/CD Pipeline using Jenkins, Docker, and GitHub

This project demonstrates how to automate the deployment of a **Flask web application** using a **CI/CD pipeline** powered by **Jenkins**, **Docker**, and **GitHub**.

---

## 📌 Project Overview

- **App Framework**: Python Flask
- **CI/CD Tool**: Jenkins
- **Version Control**: Git & GitHub
- **Containerization**: Docker
- **Trigger**: GitHub Webhook

---

## 🛠️ Technologies Used

| Tool       | Purpose                                 |
|------------|------------------------------------------|
| Flask      | Lightweight web application              |
| GitHub     | Source code management                   |
| Jenkins    | CI/CD automation                         |
| Docker     | Containerizing the Flask app             |
| Webhooks   | Automatically trigger Jenkins pipelines  |

---

## 📂 Project Structure

```

Flask-CI-CD/
├── app/
│   └── app.py                  # Flask application
├── Dockerfile                  # Docker build file
├── jenkins\_pipeline.groovy     # Jenkins scripted pipeline (if applicable)
├── Jenkinsfile                 # Jenkins declarative pipeline
├── requirements.txt            # Python dependencies
└── README.md

````

---

## 🚀 CI/CD Pipeline Flow

1. **Code Push to GitHub**
2. **Webhook triggers Jenkins**
3. **Jenkins Pipeline**:
   - Pulls latest code
   - Installs dependencies
   - Builds Docker image
   - Pushes image to Docker Hub (optional)
   - Deploys container

---

## 🧪 How to Run Locally (Optional)

```bash
git clone https://github.com/abhi-gadge1773/Flask-CI-CD.git
cd Flask-CI-CD
pip install -r requirements.txt
python app/app.py
````

---

## 🐳 Docker Build & Run

```bash
docker build -t flask-ci-cd .
docker run -d -p 5000:5000 flask-ci-cd
```

Then visit: `http://localhost:5000`

---

## 🧰 Jenkins Setup

1. Install Jenkins on your server
2. Install necessary plugins: Git, Docker, Pipeline
3. Create a new Pipeline job
4. Use `Jenkinsfile` for configuration
5. Add GitHub Webhook to trigger on push

---


## 🙌 Author

**Abhijeet Gadge**
🔗 [LinkedIn](https://www.linkedin.com/in/abhijeetgadge/)
💻 [GitHub](https://github.com/abhi-gadge1773)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

```

