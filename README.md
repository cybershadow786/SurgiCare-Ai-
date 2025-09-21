# **SurjiCare – AI-Powered Skin Treatment Assistant**

SurjiCare is a smart web-based assistant designed to provide quick treatment guidance for **minor skin injuries** such as **scars, cuts, burns, and scratches**.  
The system uses an **AI model** integrated with a **Flask backend** to analyze images of the affected area and give **first-aid suggestions**, **healing tips**, and **recommended treatments**—all from a simple and user-friendly web interface.

> ⚠️ **Disclaimer:** SurjiCare is intended for **basic guidance only** and is **not a replacement for professional medical care**. Always seek help from a certified healthcare provider for serious injuries.

---

## 🚀 Features
- **Injury Detection** – Identifies scars, cuts, burns, and scratches from uploaded images.  
- **Treatment Advice** – Suggests first-aid steps and care instructions.  
- **Healing Tips** – Provides tips to reduce infection risk and promote faster healing.  
- **User-Friendly Interface** – Clean and responsive design for all devices.  
- **Flask Backend** – Handles image processing and AI analysis.

---

## 🛠️ Tech Stack

| Component   | Technology Used |
|-------------|------------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend**  | Python (Flask) |
| **AI/ML**    | Image Classification Model (e.g., TensorFlow / PyTorch / OpenCV) |
| **Hosting**  | Render / Railway / Heroku (or any Flask-compatible service) |


---

## ⚡ Installation & Setup

Follow these steps to run **SurjiCare** locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/SurjiCare.git
cd SurjiCare
```
### 2️⃣ Create & Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Application
```bash
python app.py
```

### The app will be available at:
➡️ ```bash http://127.0.0.1:5000/```

### 🌐 Deployment

- To deploy SurjiCare online:

- Push the repository to GitHub.

- Use a Flask-compatible hosting service such as:

- Render

- Railway

- Heroku

** Ensure the following files are included: **

- requirements.txt

- Procfile (if using Heroku)

- runtime.txt (optional for Python version)

### 💡 Future Improvements

- Add support for real-time camera input.

- Implement multi-language support for global users.

- Add database integration to track treatment history.

### 🤝 Contributing

Contributions are welcome!
If you’d like to improve SurjiCare:

Fork the repository.

- Create a new branch (feature/YourFeature).

- Commit your changes.

- Submit a pull request.
