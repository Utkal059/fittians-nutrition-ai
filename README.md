# Fittians Nutrition AI 🥗🤖

An AI-powered nutrition and food tracking platform designed to help users monitor their diet, log meals, and analyze nutritional stats effortlessly.

---

## 🏗️ Project Architecture

```text
fittians-nutrition-ai/
├── backend/            # Backend services and API
├── mobile/             # React Native / Mobile client code
│   ├── services/       # API integration services (Food, Water, Dashboard, etc.)
│   ├── types/          # TypeScript interface definitions
│   └── utils/          # Helper utilities and dataset configurations
└── docker-compose.yml  # Containerization & orchestration setup
```

---

## 🚀 Features

- **AI Food Tracking:** Automatically parse and analyze meal data.
- **Water & Hydration Monitoring:** Track daily water intake and goals.
- **Dashboard Analytics:** Comprehensive view of daily nutrient intake and progress.
- **Modular Services:** Clean TypeScript architecture separating services, utilities, and UI components.

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [Docker](https://www.docker.com/) & Docker Compose

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Utkal059/fittians-nutrition-ai.git](https://github.com/Utkal059/fittians-nutrition-ai.git)
   cd fittians-nutrition-ai
   ```

2. **Run with Docker Compose:**
   ```bash
   docker-compose up --build
   ```

3. **Run Services Individually:**
   - **Backend:** Navigate to `backend/` and run `npm install && npm start`
   - **Mobile:** Navigate to `mobile/` and run `npm install && npm start`

---

## 👤 Author

- **Utkal Singh** - [@Utkal059](https://github.com/Utkal059)