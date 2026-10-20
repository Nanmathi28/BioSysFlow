# 💊 Inventra – AI-Powered Smart Pharmacy Inventory Management System

Inventra is a full-stack Smart Pharmacy Inventory Management System developed to help pharmacies efficiently manage medicines, inventory, suppliers, stock levels, expiry monitoring, and AI-powered demand forecasting.

The application combines a modern React frontend, FastAPI backend, PostgreSQL database, and Machine Learning models to provide intelligent inventory management and better decision-making.

---

# Acknowledgement

This project was developed as part of the **IEEE Engineering in Medicine and Biology Society (IEEE EMBS) Internship Program**.

We sincerely thank the IEEE EMBS Internship Program, our mentors, and coordinators for providing us with the opportunity to work on a real-world healthcare project. The internship helped us gain practical experience in software development, database management, machine learning, and collaborative project development.

---

# 🚀 Live Demo

### Frontend

https://inventra-nanmathi.vercel.app

### Backend API

https://inventra-api-n1ae.onrender.com

### Swagger Documentation

https://inventra-api-n1ae.onrender.com/docs

---

# ✨ Features

## 🔐 Authentication

- User Registration
- Secure Login
- JWT Authentication
- Role-Based Access Control

### User Roles

- Admin
- Pharmacist
- Customer

---

## 💊 Medicine Management

- Add Medicines
- Update Medicines
- Delete Medicines
- Search Medicines
- Batch Tracking
- Manufacturer Details
- Medicine Categories
- Expiry Monitoring

---

## 📦 Inventory Management

- Real-Time Inventory Tracking
- Current Stock Monitoring
- Safety Stock Management
- Reorder Level Management
- Color-Coded Stock Status
- Batch-wise Inventory

---

## 🚚 Supplier Management

- Supplier Database
- Contact Information
- Supplier Reliability

---

## 📢 Alerts

- Low Stock Alerts
- Critical Stock Alerts
- Expiry Alerts
- Inventory Notifications

---

## 🛒 Order Management

- Customer Orders
- Order Tracking
- Order History

---

## 📊 Dashboard & Analytics

- Inventory Overview
- Stock Distribution
- Supplier Statistics
- Expiry Summary
- Interactive Charts

---

## 🤖 AI & Machine Learning

- Demand Forecasting
- Future Stock Prediction
- Smart Restocking
- Historical Demand Analysis

---

## 📄 Prescription Management

- Upload Prescriptions
- Prescription Records
- Medicine Request Tracking

---

# 🛠️ Technology Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Router

### Backend

- FastAPI
- SQLAlchemy
- PostgreSQL
- Alembic
- JWT Authentication
- Pydantic

### Machine Learning

- Scikit-learn
- Pandas
- NumPy

### Deployment

- Frontend – Vercel
- Backend – Render
- Database – PostgreSQL

---

# 📁 Project Structure

```text
inventra/
│
├── inventra_frontend/
│
├── inventra_backend/
│   ├── alembic/
│   ├── app/
│   │   ├── api/
│   │   ├── auth/
│   │   ├── config/
│   │   ├── database/
│   │   ├── ml/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── services/
│   │   └── utils/
│   ├── data/
│   ├── tests/
│   ├── requirements.txt
│   └── main.py
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Nanmathi28/inventra.git

cd inventra
```

## Backend Setup

```bash
cd inventra_backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt

alembic upgrade head

uvicorn main:app --reload
```

Backend:

```
http://127.0.0.1:8000
```

Swagger:

```
http://127.0.0.1:8000/docs
```

---

## Frontend Setup

```bash
cd inventra_frontend

npm install

npm run dev
```

Frontend:

```
http://localhost:5173
```

---

## Database Configuration

Create a `.env` file inside `inventra_backend`.

```env
DATABASE_URL=postgresql://username:password@localhost:5432/inventra_db

SECRET_KEY=your_secret_key

ALGORITHM=HS256

ACCESS_TOKEN_EXPIRE_MINUTES=60
```

---

# 🔮 Future Enhancements

- Barcode Scanner Integration
- OCR Prescription Recognition
- Email Notifications
- SMS Alerts
- Mobile Application
- Multi-Branch Pharmacy Support
- Supplier Performance Analytics
- Advanced AI Forecasting
- Sales Analytics Dashboard

---

# 👥 Authors

- Nanmathi Balachandran
- Arya Pandaram

---

# 📄 License

This project was developed for educational and academic purposes as part of the **IEEE EMBS Internship Program**.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
