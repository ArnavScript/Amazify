# 🛒 Amazify  

Amazify is an AI-powered counterfeit detection platform built under **Amazon HackOn with Amazon – Season 4**.  
It strengthens product authenticity verification across the Amazon ecosystem by analyzing seller-submitted images and descriptions to prevent fraudulent listings.

---

## 📌 Table of Contents  

- [Overview](#overview)  
- [Problem Statement](#problem-statement)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [System Workflow](#system-workflow)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Screenshots](#screenshots)  
- [Future Scope](#future-scope)  
- [Contributors](#contributors)  
- [License](#license)  

---

## 📖 Overview  

Counterfeit products negatively impact customer trust and brand reputation. Amazify addresses this by introducing an automated verification layer that evaluates product authenticity before it is published on the Amazon platform.

Sellers upload a product description along with multiple images. These inputs are processed using an image-processing-based ML model that generates an **authenticity score**. Products exceeding the defined threshold are approved, while suspicious items are rejected.

---

## ❗ Problem Statement  

Manual verification of millions of products is inefficient and error-prone. The Amazon ecosystem needs an intelligent and scalable mechanism to detect counterfeit products early in the product lifecycle.

Amazify provides an automated AI-powered solution to reduce fraudulent listings and improve platform trust.

---

## ✨ Features  

- 🧠 AI-Based Image Processing Model  
- 📸 Multi-Image Upload Support  
- ✅ Automated Product Verification  
- 👤 Seller Admin Dashboard  
- 📊 Authenticity Scoring System  
- ⏳ Status Tracking (Verified / Rejected / Pending)  

---

## 🛠 Tech Stack  

| Layer     | Technologies Used            |
|----------|-----------------------------|
| Frontend | HTML, CSS, JavaScript       |
| Backend  | PHP                         |
| Database | MySQL                       |
| Server   | XAMPP (Apache, MySQL)       |
| ML       | Image Processing Model      |

---

## 🔄 System Workflow  

1. Seller signs up / logs in.  
2. Seller uploads product details and images.  
3. ML model processes data.  
4. Authenticity score is generated.  
5. Product status is decided using a threshold.  
6. Seller views result on dashboard.  

---

## ⚙ Installation  

### ✅ Prerequisites  

- XAMPP  

---

### 🚀 Setup Steps  

1. Install XAMPP.  
2. Copy the `Amazify` folder to:  

### Screenshots

# Login Page
![Login Page](images/log-in.png)

