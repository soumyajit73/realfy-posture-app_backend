# Realfy Posture App – Backend

This is the backend code for the Realfy Posture App, which processes video frames and performs posture detection and analysis.

---

## 🚀 Tech Stack Used

- Python 3.10
- FastAPI (web API framework)
- Mediapipe (pose detection)
- OpenCV
- Uvicorn (ASGI server)

---

## 🛠 Setup Instructions (Run Locally)

1. Clone the repository:
    ```
   git clone https://github.com/soumyajit73/realfy-posture-app_backend
    ```

2. (Optional) Create and activate a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate     # Windows
    ```

3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

4. Run the FastAPI server:
    ```
    uvicorn app:app --reload
    ```

5. The backend will run at:
    ```
    http://127.0.0.1:8000
    ```

---

## 🌐 Deployed Backend API

https://realfy-posture-app-backend.onrender.com/

---

## ⚠️ Notes

- The backend is hosted on **Render’s free tier**, which may go to sleep when idle. This can cause **20–30 seconds delay** on the first request while the server wakes up.
- You might sometimes see a **502 Bad Gateway** error if the server is waking up or under load. Wait a few seconds and refresh, or try again.
- For the smoothest experience, you can **run the backend locally** using the instructions above.
  
---

## 🎥 Demo Video

https://drive.google.com/drive/folders/1ntz97dV1T0pvDuvKzlhxmjId_-9wDavZ?usp=drive_link

---
