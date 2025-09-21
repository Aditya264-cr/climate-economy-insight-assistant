# 🌍 Climate–Economy Insight Assistant:

This project is our submission for the **Kaggle BigQuery AI Hackathon: Building the Future of Data**.  
It demonstrates how **BigQuery’s Generative AI, Vector Search, and Multimodal capabilities** can transform complex climate and economic datasets into **region-specific insights, forecasts, and decision-ready intelligence**.

---

## 🚀 Features:
- **Executive Insights Card** → AI.GENERATE_TABLE generates structured region-specific summaries.  
- **10-Year Forecasting** → AI.FORECAST predicts climate/economic indicators.  
- **Multimodal Image Analysis** → AI-driven interpretation of satellite/regional images.  
- **Vector Search** → Semantic similarity between country-level climate/economic trends.  
- **Transparent Data Sources** → Every report cites official datasets (World Bank, NOAA, IEA).  
- **Export Options** → Save insights as CSV/JSON (PDF optional).  

---

## 📂 Project Structure:
<img width="339" height="780" alt="Screenshot 2025-09-21 152845" src="https://github.com/user-attachments/assets/c9ff20d2-825e-4a33-9e82-4bbe52932a04" /> `climate-insight-fusion-main`, is organized into several key directories to ensure a clean, maintainable, and scalable codebase. This structure follows best practices for a React application built with TypeScript.

---

##  `src`

This is the main application source directory, housing all the components, hooks, services, and pages.

-   **`components/`**: Contains reusable UI components, grouped logically by feature or purpose.
    -   `climate/`: Holds specific components related to the climate-insight functionality.
    -   `ui/`: Stores generic, presentational UI components.
-   **`hooks/`**: Custom React hooks for encapsulating and reusing stateful logic.
-   **`lib/`**: Contains utility functions and third-party library integrations.
-   **`pages/`**: Defines the main routes and corresponding page components of the application.
-   **`services/`**: Handles all API calls and business logic related to data fetching and manipulation. Each file is dedicated to a specific service.
-   **`App.tsx`, `index.tsx`, `main.tsx`**: The main entry points and root components of the application.

---

## `public`

This directory is for static assets that need to be served directly, such as `robots.txt` and other files that don't need to be processed by the build tool.

---

## **Configuration Files**

The root directory also includes various configuration files essential for the project's development and build processes:

-   `package.json`: Manages project dependencies and scripts.
-   `tsconfig.json`: TypeScript compiler configuration.
-   `vite.config.ts`: Vite build tool configuration.
-   `.gitignore`: Specifies files and directories to be ignored by Git.
-   `eslint.config.js`: ESLint configuration for code linting.
-   `tailwind.config.ts`: Tailwind CSS configuration.
---

## ⚙️ Tech Stack:
- **Frontend:** React + Tailwind + Chart.js  
- **AI/Backend:** Google BigQuery AI (Generative AI, Vector Search, Multimodal)  
- **Deployment:** Replit / Vercel (demo-ready)  

---
## 📊 BigQuery AI Integration:
This project demonstrates the direct application of BigQuery AI inside a working prototype:

- **Forecasting:** AI.FORECAST predicts CO₂ emissions and economic indicators.
- **Text Generation:** AI.GENERATE and AI.GENERATE_TABLE produce structured summaries and insights.
- **Semantic Search:** ML.GENERATE_EMBEDDING + VECTOR_SEARCH power similarity matching for historical and contextual data.
- **Multimodal Fusion:** BigQuery object tables integrate structured (numerical) + unstructured (images, reports) data.
All BigQuery calls are modularized inside src/services/bigqueryService.ts for clarity.
---
## 🌍 Data Sources:
The prototype connects with reliable, publicly available datasets including:

- 🌐 World Bank Climate Indicators
- 🌐 NOAA GSOD Weather Records
- 🌐 IEA Energy & Emissions Data
- 🌐 UN Data & Regional Statistics 
Each generated report cites its sources for trust and transparency.
---
## Prototype created using Lovable AI:
-> [https://climate-insight-fusion.lovable.app/]

---

## 🏆 Competition Context:

This project was developed as part of the **Kaggle BigQuery AI Hackathon: Building the Future of Data.** It addresses the challenge of making **climate + economic data** actionable through **Generative AI, Vector Search, and Multimodal capabilities**, proving how BigQuery AI can extend SQL beyond rows and columns into **real-time, decision-ready intelligence.**

---
## Image:
<img width="1589" height="878" alt="Screenshot 2025-09-21 160017" src="https://github.com/user-attachments/assets/0fa7b9e2-5726-499c-b51b-2740596b4246" />

---
