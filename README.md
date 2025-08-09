# Static-Web-App-on-Cloud-for-CV
Week # 1 Task of Cloud Computing Intership - Static Web App for CV


# 🌐 My Static Webpage on Azure

[![Azure Static Web Apps](https://img.shields.io/badge/Hosted%20on-Azure%20Static%20Web%20Apps-0078D4?logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/en-us/services/app-service/static/)
[![HTML5](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2025--08--09-orange)

A clean and responsive static webpage hosted on **Microsoft Azure Static Web Apps**.  
This project demonstrates the deployment of a simple HTML/CSS website to the cloud for free.

## 🚀 Deployment Process on Azure Static Web Apps

### **1. Prepare Your Project**
- Create your website using HTML & CSS.
- Make sure you have an `index.html` file (this is the default entry point).
- Place all your assets (CSS, images, etc.) in the same directory or organized in subfolders.

### **2. Push Code to GitHub**
1. Create a GitHub repository.
2. Upload all your project files.
3. Commit and push changes.

### **3. Create Azure Static Web App**
1. Go to [Azure Portal](https://portal.azure.com/).
2. Search for **"Static Web Apps"** and click **Create**.
3. Fill out:
   - **Subscription**: Your Azure subscription
   - **Resource Group**: Create or select an existing one
   - **Name**: Choose a unique app name
   - **Plan type**: Free
   - **Region**: Choose closest to your audience
4. Click **Sign in with GitHub** to connect your repo.

### **4. Configure Build Settings**
- **App location**:
  - `/` if `index.html` is in the root folder.
  - `folder_name` if it’s in a subfolder.
- **Output location**: Leave empty (no build process).

### **5. Deploy**
- Azure creates a GitHub Actions workflow to auto-deploy on every commit.
- Wait for deployment to finish (check GitHub Actions tab).
- Visit your assigned Azure URL.


## 📂 Project Structure
index.html
styles.css
profile.jpg



## 🛠 Tech Stack
- **HTML5**
- **CSS3**
- **Microsoft Azure Static Web Apps**


> 💡 *Tip:* Every time you push to the `main` branch, Azure automatically redeploys 
