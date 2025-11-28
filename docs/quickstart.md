# 🚀 Quickstart – ModusFlow

Get ModusFlow running locally in under 2 minutes.

---

## 📦 Requirements

- Python 3.8+

---

## ⚙️ Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn api.main:app --reload
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Run a workflow(CLI)

```bash
modusflow run workflows/examples/simple_api.json
```
