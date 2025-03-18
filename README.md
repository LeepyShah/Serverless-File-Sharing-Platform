# Serverless-File-Sharing-Platform
<h3>Project Description</h3>
<p>The Serverless File Sharing Platform allows users to securely upload and download files via a simple HTTP API.</p>
# 🌐 Serverless File Sharing Platform

## 🚀 Overview
This platform allows users to **upload and download files easily** securely using AWS services. It leverages:
- **AWS Lambda** for serverless computing
- **API Gateway** for managing API requests
- **Amazon S3** for scalable file storage

Users can interact with the platform using any HTTP client, like **Postman** or a web app.

---

## 🏗️ AWS Services Used
| **AWS Service**        | **Simplified Name**                 | **Description**                                   |
|------------------------|----------------------------------|-------------------------------------------------|
| 🚀 **AWS Lambda**      | **Serverless Compute Engine**   | Runs code without managing servers.             |
| 🌐 **API Gateway**     | **Request Manager**            | Handles API requests and routes them.           |
| ☁️ **Amazon S3**      | **Cloud Storage**              | Stores and retrieves files securely.            |
| 🔑 **IAM**            | **Access Control**             | Manages user roles and permissions.             |
| 📊 **CloudWatch**     | **Monitoring & Logging Service** | Tracks system performance and logs activities.  |

---
## Project Architecture:
![image](https://github.com/user-attachments/assets/42478c31-cfdd-4334-89bc-3fe90b843198)


## 🔧 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/serverless-file-sharing.git
   cd serverless-file-sharing
   ```
2. **Install Dependencies**
   ```bash
   npm install  # If using Node.js
   ```
3. **Deploy to AWS** (Using AWS SAM or Serverless Framework)
   ```bash
   serverless deploy
   ```

---

## 📡 API Endpoints
| Method | Endpoint               | Description                 |
|--------|------------------------|-----------------------------|
| `POST` | `/upload`              | Upload a file to S3        |
| `GET`  | `/download/{fileKey}`  | Download a file from S3    |
| `DELETE` | `/delete/{fileKey}` | Delete a file from S3      |

---

## 🎯 Features
✅ **Serverless architecture** – No need to manage servers.  
✅ **Secure file storage** – Uses AWS IAM roles for access control.  
✅ **Scalable** – Leverages S3 for unlimited storage.  
✅ **Easy API access** – Interact via Postman, web, or mobile apps.  

---

## 🏗️ Future Improvements
- **User authentication** (Cognito or Firebase) 🔑
- **File sharing with expiration links** ⏳
- **Web UI for easy file uploads** 🎨

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Contributing
Feel free to contribute! Open an issue or submit a pull request. 😊

---

