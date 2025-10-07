# 🌿 SmartGardener: AI-Powered Garden Maintenance Assistant

**SmartGardener** is an AI-driven garden maintenance application built with **Azure AI, TypeScript, Node.js, Python, and React**. It helps gardeners, landscapers, and home plant enthusiasts monitor and maintain healthy gardens using **computer vision, natural language AI, and cloud automation**.  

Users can upload images, describe issues via text or voice, and receive intelligent recommendations to improve plant health, optimise watering schedules, and manage their garden efficiently.

---

## 🌱 Key Features

*All features marked `[Pending]` are planned or in development.*

- **AI Plant Health Diagnosis** – Identify diseases, pests, and nutrient deficiencies. `[Pending]`
- **Plant Identification** – Automatically detect plant species from images. `[Pending]`
- **Flower Identification** – Identify flowers in your garden. `[Pending]`
- **Fruit Identification** – Detect fruits on trees or plants. `[Pending]`
- **Weed Identification** – Detect unwanted plants (weeds) in the garden. `[Pending]`
- **Weed Treatment Recommendations** – AI-generated suggestions for weed control. `[Pending]`
- **Lawn Identification** – Recognize grass types and lawn health status. `[Pending]`
- **Conversational Garden Assistant** – Chat with AI to get advice about your plants. `[Pending]`
- **Voice-Based Interaction** – Use speech input/output for queries. `[Pending]`
- **Smart Watering Scheduler** – ML-based recommendations for watering frequency. `[Pending]`
- **Seasonal & Daily Action Planner** – Sends daily action notifications based on weather and your garden. `[Pending]`
- **Weekly Gardening Tips** – Receive curated tips to improve harvest and garden health. `[Pending]`
- **Garden Plan Creation** – AI generates a custom plan for your garden layout and maintenance. `[Pending]`
- **Weather Data Integration** – Fetch weather for the user's location to personalise recommendations. `[Pending]`
- **Analytics Dashboard** – Power BI Embedded dashboard showing garden health trends. `[Pending]`
- **Responsible AI & Content Safety** – Filters AI responses and evaluates outputs. `[Pending]`
- **Observability & Monitoring** – Tracks performance, logs, and errors using Azure Monitor and App Insights. `[Pending]`
- **Customer Identity & Access Management (CIAM)** – Secure user registration, login, social logins, and profile management. `[Pending]`

---

## 🧱 Technology Stack

| Layer | Tools & Services |
|-------|-----------------|
| **Frontend** | React + TypeScript + CIAM SDK (Auth0 or Azure B2C) |
| **Backend** | Express.js + TypeScript API Gateway + Python (FastAPI AI Microservice) |
| **AI Services** | Azure OpenAI, Computer Vision, Speech, Custom ML Models |
| **Data & Storage** | Azure SQL, Blob Storage, Data Lake |
| **Infrastructure** | Terraform, Azure App Service, Azure DevOps Pipelines |
| **Security** | CIAM, Key Vault, Managed Identity |
| **Observability** | Azure Monitor, App Insights, Log Analytics |
| **Responsible AI** | Azure Content Safety + AI Studio Evaluation |
| **Analytics** | Power BI Embedded |

---

## 🌤️ Example User Flow

1. User signs in via **CIAM** (email/password, social login, or external identity). `[Pending]`
2. Uploads an image or speaks about a garden issue.
3. AI identifies plants, flowers, fruits, weeds, or lawn types and diagnoses health issues. `[Pending]`
4. AI provides daily actions and weekly tips based on weather and garden conditions. `[Pending]`
5. User receives notifications and can view progress on the **Power BI dashboard**. `[Pending]`
6. AI generates a customised garden plan for seasonal care. `[Pending]`

---

## 📂 Folder Structure

```
smart-gardener/
├─ backend/
│  ├─ src/
│  │  ├─ server.ts           # main backend entry point
│  │  ├─ routes/             # API routes (plants, auth, etc.)
│  │  ├─ controllers/        # route controllers
│  │  ├─ models/             # DB models or interfaces
│  │  └─ db.ts               # database connection
│  ├─ dist/                   # compiled JavaScript output
│  ├─ package.json
│  ├─ tsconfig.json
│  └─ .env                    # environment variables (not committed)
├─ frontend/
│  ├─ src/
│  │  ├─ App.tsx
│  │  ├─ components/         # React components
│  │  ├─ pages/              # page views
│  │  ├─ services/           # API calls to backend
│  │  └─ hooks/              # custom React hooks
│  ├─ public/                 # static assets
│  ├─ package.json
│  ├─ tsconfig.json
│  └─ .env                    # frontend environment variables
├─ README.md
└─ .gitignore
```

---

## Set Up

#### Create `.env` file:
```
PORT=5000
DB_HOST=localhost
DB_USER=postgres
DB_PASSWORD=yourpassword
DB_NAME=smart_gardener
JWT_SECRET=your_jwt_secret
```


## 🛠️ Development Commands

### Backend (Node.js + TypeScript)

| Command               | Description                                  |
|-----------------------|----------------------------------------------|
| `npm install`         | Install project dependencies                 |
| `npm run dev`         | Start backend server with auto-reload        |
| `npm run build`       | Compile TypeScript to JavaScript (`dist/`)  |
| `npm run start`       | Start compiled backend server (production)  |
| `npm run lint`        | Run ESLint on backend code                   |
| `npm test`            | Run unit tests                               |

### Frontend (React + TypeScript)

| Command               | Description                                  |
|-----------------------|----------------------------------------------|
| `npm install`         | Install project dependencies                 |
| `npm run dev`         | Start React dev server                        |
| `npm run build`       | Build production-ready frontend               |
| `npm run preview`     | Preview production build                      |
| `npm run lint`        | Run ESLint on frontend code                   |
| `npm test`            | Run unit tests                               |

---
