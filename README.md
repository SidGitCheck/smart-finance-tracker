# 💰 Smart Student Finance Assistant (Offline ML)

A smart, privacy-focused finance tracker that uses **Machine Learning** to automatically categorize Indian student expenses (e.g., "Pav Bhaji", "Uber", "Xerox").

## 🚀 Demo picture 
demo.jpeg file contains the expected picture

## ✨ Features
- **Hybrid AI Brain:** Combines a custom dictionary for 100% accuracy on Indian terms ("Jio", "Chai") with a Logistic Regression model for generic inputs.
- **Offline First:** All data stays in `LocalStorage`. No servers, no APIs.
- **Analytics:** Visualizes spending habits with Chart.js.
- **Management:** Add, Delete, Reset, and Export data to CSV.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Dark Mode), JavaScript (ES6+)
- **ML:** Python (Scikit-Learn) for training, JS for inference.
- **Charts:** Chart.js

## 🧠 How it works
1. **Training:** Trained on a dataset of 3,000+ student transactions.
2. **Inference:** The app tokenizes input, calculates vector dot products, and predicts the category instantly in the browser.
