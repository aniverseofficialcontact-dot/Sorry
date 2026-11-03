# 100 Ways to Say Sorry 💖

An interactive rotating wheel of 100 apologies, transitioning smoothly from cool indigo hues to warm golden accents. 

---

## 🌟 Features
- **HTML5 Web Version (`index.html`)**: Interactive web canvas animation, mobile-responsive, high-DPI (Retina) scaled, and ready for deployment on **Vercel** or **Render**.
- **Desktop Python Version (`apology_wheel.py`)**: Local desktop GUI built with `turtle` & `tkinter`.
- **Flask Server (`app.py`)**: Optional Python backend for deploying as a web service on Render.

---

## 🚀 Deployment Instructions

### Option 1: Deploy on Vercel (Recommended - Free & Fast)

1. **Via Vercel Dashboard**:
   - Push this repository to GitHub.
   - Go to [Vercel](https://vercel.com/) and click **Add New > Project**.
   - Import your GitHub repository.
   - Vercel will automatically detect `index.html` (or `vercel.json`). Click **Deploy**.

2. **Via Vercel CLI**:
   - Open your terminal in this directory and run:
     ```bash
     npx vercel
     ```
   - Follow the prompts to deploy instantly.

---

### Option 2: Deploy on Render

#### Method A: Static Site (Recommended - 100% Free)
1. Push your code to GitHub.
2. Go to [Render Dashboard](https://dashboard.render.com/) and click **New > Static Site**.
3. Connect your repository.
4. Set the following details:
   - **Name**: `100-ways-to-say-sorry`
   - **Publish directory**: `.` (or leave blank)
5. Click **Create Static Site**.

#### Method B: Web Service (Python Flask)
1. Go to [Render Dashboard](https://dashboard.render.com/) and click **New > Web Service**.
2. Connect your repository.
3. Set the following details:
   - **Runtime**: `Python 3`
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app:app`
4. Click **Create Web Service**.

---

## 💻 Running Locally

### Web Version (Browser)
Simply open `index.html` in your web browser, or run with Python Flask:
```bash
pip install -r requirements.txt
python app.py
```
Then visit `http://localhost:5000` in your browser.

### Desktop Python Version
```bash
python apology_wheel.py
```
