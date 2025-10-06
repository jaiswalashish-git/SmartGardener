# 🌿 SmartGardener: AI-Powered Garden Maintenance Assistant
SmartGardener is an AI-driven cloud application designed to help homeowners, landscapers, and urban gardeners maintain healthy, thriving gardens through intelligent insights and automation.
Powered by Azure AI and cloud-native technologies, the app combines computer vision, natural language understanding, and machine learning to diagnose plant issues, recommend maintenance actions, and automate garden care schedules.
Users can simply upload a plant photo, speak about a problem, or chat with an AI garden assistant to receive tailored advice — from identifying diseases and pests to predicting the next optimal watering date.
# 🌱 Key Features
* **AI Plant Health Diagnosis** – Upload a photo and let Azure Computer Vision and custom ML models detect plant diseases, pests, or deficiencies.
* **Conversational Garden Assistant** – Ask natural questions like “Why are my rose leaves turning yellow?” — powered by Azure OpenAI and Semantic Kernel.
* **Voice-Based Interaction** – Describe garden issues or receive spoken tips through Azure Speech Services.
* **Smart Watering Scheduler** – Predict watering needs using an ML model trained on weather, soil type, and past activity.
* **Seasonal Maintenance Planner** – Logic App integration sends reminders for pruning, fertilising, or harvesting.
* **Garden Analytics Dashboard** – View plant health trends, AI accuracy, and maintenance cost insights in Power BI.
* **Responsible AI & Content Safety** – All AI responses are filtered and evaluated using Azure Content Safety and AI Studio Evaluation.
* **End-to-End Observability** – Integrated Application Insights, Log Analytics, and custom Power BI reports for transparency and performance tracking.
# 🧱 Technology Stack
Layer	| Tools & Services
--- | ---
Frontend | React + TypeScript + MSAL.js (Azure AD Auth)
Backend | Express.js API Gateway + Python (FastAPI ML Service)
AI Services | Azure OpenAI, Computer Vision, Speech, ML Workspace
Data & Storage | Azure SQL, Blob Storage, Data Lake
Infrastructure | Terraform, Azure App Service, Azure DevOps
Security | Azure AD, Key Vault, Managed Identity
Observability | Azure Monitor, App Insights, Log Analytics
Responsible AI | Azure Content Safety + AI Studio Evaluation
Analytics | Power BI Embedded
# 🌤️ Example User Flow
User signs in via Microsoft Entra ID.
Uploads an image or speaks to describe a garden issue.
The app invokes Azure Computer Vision and OpenAI models to analyse and explain the problem.
AI generates actionable insights (e.g., “This looks like fungal leaf spot. Try neem oil and reduce watering.”).
Recommendations and reminders are stored in Azure SQL and scheduled using Logic Apps.
The Power BI dashboard visualises garden health over time.
# 🧠 What You’ll Learn (Hands-On Skills)
Integrating multiple Azure AI services (Vision, OpenAI, Speech, ML) into a unified app
Building secure, cloud-native web apps using React, Express, and Python
Deploying with Terraform, Azure App Service, and DevOps pipelines
Implementing observability and Responsible AI practices
Designing AI orchestration workflows using Semantic Kernel and Logic Apps
# 🪴 Why This Project Matters
SmartGardener showcases the complete lifecycle of an intelligent Azure application — from design to deployment — covering modern engineering themes like:
* AI + Cloud integration
* Security and governance
* Responsible AI implementation
* Observability and continuous improvement
* It’s an ideal portfolio or interview project for aspiring Microsoft Solution Engineers and AI Cloud Architects.
