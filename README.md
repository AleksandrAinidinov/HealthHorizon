# HealthHorizon 🩺

Comprehensive clinic management system designed to streamline appointment scheduling, doctor availability management, and patient record keeping. The platform enables healthcare providers to efficiently manage medications, monitor health metrics, and communicate with patients through an integrated AI-powered chatbot - all within a user-friendly, modern interface.

## 🚀 Features

- 🗓️ Schedule and manage patient appointments effortlessly
- 👨‍⚕️ Doctors can add and update their availability for patient booking
- 📋 Maintain detailed patient records including medical history and prescriptions
- 💊 View and manage medication information per patient
- 📊 Track and visualize key health metrics for patients
- 👤 User authentication with personalized dashboards for patients and staff
- 🤖 AI Chatbot available 24/7 to assist patients with questions and support
- 🔔 Reminders & notifications to encourage appointment attendance and health logging
- 📝 Daily logging of health metrics and notes for ongoing wellness tracking
- 💾 Local storage and backend API integration


## 🛠️ Tech Stack

- 🎨 **Frontend:** Next.js ⚛️ / TypeScript 🟦 / Tailwind CSS 💅
- 💅 **Styles & UI:** Framer Motion 🎥 / Lucide Icons 💠 / V0 + Aceternity UI 🎯
- 🧠 **Backend:** ASP.NET Core Web API ⚙️ / Entity Framework Core 💻 / SQL 🗃️ / Context Database 📚
- 🤖 **AI Chatbot:** OpenAI API ⚙️
- 🔐 **Authentication:** JWT Tokens 🪙


## 📦 Getting Started

### Clone the repo

```bash
git clone https://github.com/AleksandrAinidinov/HealthHorizon.git
cd HealthHorizon
```

### Frontend Setup
```bash
cd frontend
npm install --legacy-peer-deps
npm run dev
```
Open http://localhost:3000 in your browser to see the frontend.

### Backend Setup
```bash
cd backend/HealthHorizon_API
dotnet run
```
All API paths are available to at https://localhost:7132/scalar/v1.

## 🗝️ Environment Variables / API Keys
To use API keys or private configs, create environment variable files as follows.

### Frontend

- Copy `.env.example` to `.env.local` in `/frontend`
- Fill in your backend API URL and any keys

```env
NEXT_PUBLIC_API_URL=http://localhost:7132/api
NEXT_PUBLIC_EMAIL_API_KEY=your-email-api-key
OPENAI_ORG_ID=your-openai-org-id
OPENAI_PROJECT_ID=your-openai-project-id
OPENAI_BASE_URL=https://api.openai.com/v1/chat/completions



🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

1. Fork the project

2. Create your feature branch: git checkout -b feature/FeatureName

3. Commit your changes: git commit -m 'Add feature'

4. Push to the branch: git push origin feature/FeatureName

5. Open a pull request

## 📄 License
MIT License. See LICENSE for details.
Made with ❤️
