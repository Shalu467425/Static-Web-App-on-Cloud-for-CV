# Static-Web-App-on-Cloud-for-CV
Week # 1 Task of Cloud Computing Intership - Static Web App for CV


# 🌐 My Static Webpage on Azure

[![Azure Static Web Apps](https://img.shields.io/badge/Hosted%20on-Azure%20Static%20Web%20Apps-0078D4?logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/en-us/services/app-service/static/)
[![HTML5](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2025--08--09-orange)
[![Azure Deployment](https://github.com/USERNAME/REPO/actions/workflows/azure-static-web-apps.yml/badge.svg)](https://github.com/USERNAME/REPO/actions/workflows/azure-static-web-apps.yml)

A **personal static webpage** hosted on **Microsoft Azure Static Web Apps**.  
This project showcases my step-by-step process of creating and deploying a simple HTML/CSS website to the cloud.

---

## 🚀 My Deployment Process on Azure Static Web Apps

### **1. Creating the Website**
- I developed a basic webpage using **HTML** and **CSS**.
- The main entry file was `index.html`.
- All CSS and assets were stored in well-structured folders for easy management.

### **2. Uploading to GitHub**
1. Created a **new GitHub repository** specifically for this project.
2. Uploaded all project files (`index.html`, CSS, images).
3. Committed and pushed the files to the `main` branch.

### **3. Setting Up Azure Static Web App**
1. Logged in to [Azure Portal](https://portal.azure.com/).
2. Navigated to **Static Web Apps** → **Create**.
3. Configured:
   - **Subscription**: My Azure subscription
   - **Resource Group**: Created a dedicated group for this site
   - **Name**: Unique app name for Azure
   - **Plan type**: Free tier
   - **Region**: Closest to my expected visitors
4. Linked my GitHub repository directly from Azure.

### **4. Configuring Build & Deploy**
- Set **App location** to `/` (since `index.html` is in root folder).
- Left **Output location** empty (no special build process).
- Azure automatically created a **GitHub Actions workflow** to handle deployments.

### **5. Automatic Deployment**
- Every time I push to `main`, the GitHub Actions pipeline triggers and deploys the latest version.
- Deployment status is visible in both **Azure Portal** and the **GitHub Actions tab**.

---

## 📂 My Project Structure
- index.html
- styles.css
- profile.jpg


## 🛠 Tech Stack Used
- **HTML5** for structure
- **CSS3** for styling
- **Microsoft Azure Static Web Apps** for hosting


