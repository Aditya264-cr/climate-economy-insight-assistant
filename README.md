# 🌍 Climate–Economy Insight Assistant

This project is our submission for the **Kaggle BigQuery AI Hackathon: Building the Future of Data**.  
It demonstrates how **BigQuery’s Generative AI, Vector Search, and Multimodal capabilities** can transform complex climate and economic datasets into **region-specific insights, forecasts, and decision-ready intelligence**.

---

## 🚀 Features
- **Executive Insights Card** → AI.GENERATE_TABLE generates structured region-specific summaries.  
- **10-Year Forecasting** → AI.FORECAST predicts climate/economic indicators.  
- **Multimodal Image Analysis** → AI-driven interpretation of satellite/regional images.  
- **Vector Search** → Semantic similarity between country-level climate/economic trends.  
- **Transparent Data Sources** → Every report cites official datasets (World Bank, NOAA, IEA).  
- **Export Options** → Save insights as CSV/JSON (PDF optional).  

---

## 📂 Project Structure
climate-insight-fusion-main/
│── public/                  # Static assets (favicon, robots.txt, etc.)
│
│── src/                     # Main source code
│   ├── components/          # Reusable UI and logic components
│   │   ├── climate/         
│   │   │   ├── ControlPanel.tsx         # Input controls for selecting indicators, region, and mode
│   │   │   ├── DataSources.tsx          # Displays dynamically fetched data sources
│   │   │   ├── ExecutiveInsights.tsx    # AI-generated executive summary and key recommendations
│   │   │   ├── ForecastVisualization.tsx# Forecast chart visualization (10-year trend)
│   │   │   ├── ImageAnalyzer.tsx        # Image analysis for region-based climate/economic visuals
│   │   │   ├── VectorSearch.tsx         # Semantic vector search for region-specific insights
│   │   ├── ui/                         
│   │   │   └── ClimateInsightEngine.tsx # Main orchestrator combining all climate modules
│   │
│   ├── hooks/               # Custom React hooks
│   │   ├── use-mobile.tsx   # Mobile responsiveness handling
│   │   └── use-toasts.tsx   # Notification system for errors/success
│   │
│   ├── lib/                 
│   │   └── utils.ts         # Utility functions
│   │
│   ├── pages/               # Page-level components
│   │   ├── Index.tsx        # Home page
│   │   └── NotFound.tsx     # 404 page
│   │
│   ├── services/            # Business logic + API/AI integrations
│   │   ├── bigqueryService.ts      # Handles BigQuery AI calls (AI.GENERATE, AI.FORECAST, etc.)
│   │   ├── errorService.ts         # Centralized error handling
│   │   ├── exportService.ts        # (Optional) Export/Report utilities
│   │   ├── imageService.ts         # Region-based image fetching/analysis
│   │   ├── realTimeService.ts      # Fetches live climate/economic data
│   │   ├── vectorSearchService.ts  # Embedding generation + semantic search
│   │   └── webSearchService.ts     # Web search integration for secondary analysis
│   │
│   ├── App.css              # Global styling
│   ├── App.tsx              # Root app component
│   ├── index.css            # Entry styles
│   ├── main.tsx             # React app entry point
│   └── vite-env.d.ts        # Vite environment type definitions
│
├── .gitignore
├── components.json
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── README.md
├── reference-original.html
├── reference-package.json
├── reference-server.js
├── tailwind.config.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts

---

## ⚙️ Tech Stack
- **Frontend:** React + Tailwind + Chart.js  
- **AI/Backend:** Google BigQuery AI (Generative AI, Vector Search, Multimodal)  
- **Deployment:** Replit / Vercel (demo-ready)  

---


