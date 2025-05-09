# FlaskOps 🚀

A beginner-level project to learn DevOps using a basic Flask app with Docker and GitHub Actions.

---

## 🔧 What This Project Does

- Runs a simple Flask web app
- Uses a Docker container to package the app
- Automates Docker build using GitHub Actions (CI/CD basics)

---

## 📁 Files You’ll See

FlaskOps/
├── app.py # The Flask app
├── Dockerfile # Instructions to create Docker image
├── requirements.txt # Flask dependency
├── .github/
│ └── workflows/
│ └── main.yml # GitHub Actions workflow file
└── README.md # This file!


---

## ▶️ How to Run It Locally

docker build -t flaskops .
docker run -p 5000:5000 flaskops

Open your browser: http://localhost:5000

⚙️ GitHub Actions Workflow

When you push code to GitHub:

  It builds the Docker image.

  (Optional) You can later add tests or deployment steps.

Workflow file: .github/workflows/flaskops.yml

✅ Goal of This Project

Learn how to:

   Use Docker with Python

  Write a GitHub Actions workflow

   Practice real-world DevOps basics

 📚 Next Steps

  Add tests and run them in CI

  Push Docker image to Docker Hub

  Deploy app to a platform like Render or Railway

📄 License

This project is licensed under the MIT License.
