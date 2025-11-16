# 🔐 Login Page with JavaScript + Google Sheets

A clean and modern **Login & Signup system** built using **HTML, CSS, and JavaScript**, with **Google Sheets** working as a free backend using **Google Apps Script (Web App API)**.

---

## 🚀 Features

* Responsive Login & Signup UI
* JavaScript form validation
* Google Sheets used as database
* Google Apps Script as backend API
* No hosting or server required
* Simple, lightweight, and beginner-friendly

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Google Sheets
* Google Apps Script (Web App)
* GitHub Pages

---

## 📡 How It Works

1. User fills Login/Signup form
2. JavaScript sends data to Google Apps Script URL
3. Apps Script writes the data to Google Sheets
4. Login validation checks the sheet data
5. UI shows success/failure messages

---

## 📁 Folder Structure

```
/project
   ├── index.html
   ├── login.html
   ├── style.css
   ├── script.js
   └── apps_script.gs
```

---

## ⚙️ Setup Instructions

### 1. Create Google Sheet

* Make a new sheet
* Add columns: Name, Email, Password, Timestamp

### 2. Add Apps Script Code

* In Google Sheet → Extensions → Apps Script
* Paste your script
* Deploy → Web App → "Anyone" access
* Copy the Web App URL

### 3. Add API URL in script.js

```
const apiURL = "YOUR_WEB_APP_URL";
```

### 4. Upload Project to GitHub

* Create a new repository
* Upload all files
* Commit changes

### 5. Host on GitHub Pages

* Go to Settings → Pages
* Source: main branch
* Folder: /root
* Save and wait 1 minute
* Your website will go live

---

## 🧪 Live Demo

Add your GitHub Pages link here.

---

## 🚧 Future Improvements

* Password Encryption
* Session Handling
* Forgot Password System
* Admin Dashboard using Sheets

---

## 👤 Author

**Darshil Ramani**
BCA Student – Geetanjali College, Rajkot
