# 🤖 Jenkins CI/CD Pipeline – GitHub → Maven → Tomcat (on EC2)

This project demonstrates a full CI/CD pipeline using Jenkins, Maven, and Apache Tomcat hosted on an AWS EC2 instance.

---

## 📌 Tech Stack

| Tool     | Purpose                       |
|----------|-------------------------------|
| Jenkins  | CI/CD Pipeline Orchestration  |
| GitHub   | Source code repository        |
| Maven    | Java build tool               |
| Apache Tomcat | Java app server         |
| AWS EC2  | Hosting Tomcat & deployment   |

---

## 🎯 Pipeline Workflow

1. ✅ Jenkins pulls source code from GitHub (Java + Maven project)
2. ✅ Builds a `.war` file using Maven
3. ✅ Copies the `.war` file to `/webapps/` directory on a remote EC2 Tomcat server
4. ✅ App is auto-deployed by Tomcat

---

## ⚙️ Jenkins Configuration

- Install Jenkins + Maven + Git plugins
- Add Maven 3 as a global tool in Jenkins settings
- Set up credentials for SSH deploy to EC2
- Create a Freestyle or Pipeline Job using the provided `Jenkinsfile`

---

## 🧪 Testing

- Use a sample Spring or Servlet-based Java app
- Access the app using:  
  `http://<EC2_PUBLIC_IP>:8080/<app-name>`

---

## 👨‍💻 Author

**Prashanth Kumar**  
Cloud DevOps Engineer | CI/CD Specialist  
📧 [Email](mailto:prashanthkumary123@gmail.com)  
🔗 [LinkedIn](#) | [GitHub](#)
