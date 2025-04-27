# agrismart-ai
smart agriculture assistent for farmer
folder stracture
agrismart-ai/
│
├── backend/
│   ├── auth-service/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── src/
│   │       ├── controllers/
│   │       ├── models/
│   │       ├── routes/
│   │       └── app.js
│   │
│   ├── weather-service/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── src/
│   │       └── app.js
│   │
│   ├── community-service/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── src/
│   │       ├── controllers/
│   │       ├── models/
│   │       ├── routes/
│   │       └── app.js
│   │
│   └── news-service/
│       ├── Dockerfile
│       ├── package.json
│       └── src/
│           ├── controllers/
│           ├── models/
│           ├── routes/
│           └── app.js
│
├── ml-services/
│   ├── crop-recommendation/
│   │   ├── Dockerfile
│   │   ├── requirements.txt
│   │   └── app.py
│   │
│   ├── disease-detection/
│   │   ├── Dockerfile
│   │   ├── requirements.txt
│   │   └── app.py
│   │
│   └── fertilizer-recommendation/
│       ├── Dockerfile
│       ├── requirements.txt
│       └── app.py
│
├── frontend/
│   ├── user-portal/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── (React app files)
│   │
│   └── admin-portal/
│       ├── Dockerfile
│       ├── package.json
│       └── (React app files)
│
├── database/
│   └── mongo-init/
│       └── init.js  (Optional: for initial collections)
│
├── docker-compose.yml
├── README.md
└── .env (environment variables)
