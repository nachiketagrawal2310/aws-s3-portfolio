# 💼 Portfolio Website - AWS S3 + GitHub Actions Deployment

This is my personal portfolio website built with HTML, CSS, and JavaScript, hosted on **Amazon S3** and deployed automatically via **GitHub Actions**. This setup allows for fast, secure, and scalable static hosting with continuous deployment directly from GitHub.

---

## 🚀 Live Demo

🌐 [View Website](http://my-portfolio-site-nachiket.s3-website.ap-south-1.amazonaws.com)

---

## 🧰 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript  
- **Hosting**: AWS S3 (Static Website Hosting)  
- **CI/CD**: GitHub Actions  
- **Automation**: `aws-actions/configure-aws-credentials`, `aws s3 sync`  

---

## 🔧 Features

- Responsive portfolio UI  
- Static site hosted on AWS S3  
- Automated deployment via GitHub Actions  
- Public access configured with S3 Bucket Policy  
- GitHub workflow triggers on every push to `main` branch  

---

## 📁 Folder Structure
├── index.html ├── styles.css ├── script.js ├── assets/ │ └── images, icons, etc. ├── .github/ │ └── workflows/ │ └── deploy.yml │ 


📦 Setup for Deployment

Create an S3 bucket with static website hosting enabled.
Make your bucket public (Bucket Policy).
Set up GitHub Secrets with your AWS credentials.
Push your code to the main branch — deployment is automatic!



📬 Contact

Feel free to reach out or check out more of my work:

💼 https://www.linkedin.com/in/nachiket-agrawal-49b326250/

🐙 https://github.com/nachiketagrawal
