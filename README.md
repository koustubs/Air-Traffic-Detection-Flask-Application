# ✈️ Air Traffic Detection - Flask Application

## 🚀 Overview

This Flask-based web application simulates **air traffic detection** by identifying the closest pair of aircraft using a basic AI model (Logistic Regression). It visualizes aircraft positions on a canvas and calculates the shortest distance between them.

## 🎯 Features

- Generate random aircraft positions dynamically
- Identify the **closest pair** of aircraft using the closest pair algorithm
- Send data to an AI model to predict collision risk
- Real-time distance and aircraft info updates
- Beautiful and interactive front-end with dark theme UI

## 🛠️ Tech Stack

- **Backend:** Flask (Python), scikit-learn, NumPy, Matplotlib
- **Frontend:** HTML, CSS, JavaScript
- **AI Model:** Logistic Regression for collision risk prediction

## 🚀 Setup & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/air-traffic-flask-app.git
   cd air-traffic-flask-app
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```

4. **Access the application:**
   - Open your browser
   - Go to: http://127.0.0.1:5000
   - You should see the dark-themed radar interface

## 🧠 AI Model Integration

The application uses a Logistic Regression model to predict collision risks:
- Takes aircraft positions and calculates distances
- Predicts risk based on distance thresholds
- Displays real-time warnings for dangerous situations

## 🎮 How to Use

1. Click "Generate Aircraft" to create random aircraft positions
2. Click "Find Closest Pair" to identify potential collision risks
3. Watch the AI model assess the situation in real-time
4. Observe color-coded warnings (red for danger, yellow for caution)
