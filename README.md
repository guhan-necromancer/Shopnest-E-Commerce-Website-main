# Local Setup & Installation

# 1. Environment Configuration

Create `.env` file in `backend/`:
```env
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/shopnest
JWT_SECRET=your_jwt_secret_key_here
```

Create `.env` file in `frontend/`:
```env
REACT_APP_API_URL=http://localhost:5000
```

# 2. Install & Start Application

**Backend**:
```bash
cd backend
npm install
npm start
```

**Frontend**:
```bash
cd frontend
npm install
npm start
```

Access the application in your browser at `http://localhost:3000`.
