We are building a college-level full-stack Data Science project called:

"PatientSeg — Patient Segmentation & Healthcare Analytics Platform"

I am not an experienced programmer, so you must work step-by-step and explain what you are doing clearly. Do NOT generate the entire project at once.

TECHNOLOGY STACK:

Frontend:
- React
- Vite
- Tailwind CSS

Backend:
- Python
- FastAPI
- Uvicorn
- SQLAlchemy
- Pydantic

Database:
- MySQL 8.0

Data Science:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Machine Learning:
- K-Means clustering
- Elbow Method
- Silhouette Score
- PCA

Charts:
- Recharts

Version control:
- Git
- GitHub

PROJECT PURPOSE:

The application will allow users to:
1. Insert patient data through a web form.
2. Store patient data in MySQL.
3. View patient records.
4. Analyze patient data using Python.
5. Segment patients using K-Means clustering.
6. Visualize the segments and healthcare analytics through a web dashboard.
7. Search and filter patient records.
8. Eventually upload CSV data and export analytical results.

IMPORTANT MEDICAL DATA RULE:

This is an educational Data Science project. Use only synthetic or properly de-identified data. Do not build the system as a medical diagnosis or treatment recommendation system.

FINAL PROJECT STRUCTURE SHOULD EVENTUALLY BE:

patient-segmentation-healthcare-analytics/
├── frontend/
├── backend/
├── data/
├── ml/
├── README.md
└── .gitignore

PHASE 1 ONLY:

For now, ONLY set up the project foundation.

Do NOT build the ML model yet.
Do NOT build the dashboard yet.
Do NOT build authentication yet.
Do NOT add unnecessary features.

PHASE 1 TASKS:

1. Inspect the existing project directory.

2. Create the initial folder structure:
   frontend/
   backend/
   data/
   ml/

3. Create a proper .gitignore that prevents:
   - Python virtual environments
   - node_modules
   - .env files
   - Python cache files
   - IDE files
   - generated temporary files
   - database credentials
   - patient/private data

4. Create backend Python environment setup instructions.

5. Create backend/requirements.txt containing only the packages currently needed for the initial FastAPI backend.

6. Create a minimal FastAPI application with:
   - GET /
   - GET /api/health

7. The /api/health endpoint should return JSON similar to:
   {
       "status": "healthy",
       "service": "PatientSeg API"
   }

8. Configure CORS correctly for future React development.

9. Create a basic frontend React + Vite application.

10. Make a simple initial frontend page showing:
    "PatientSeg"
    "Patient Segmentation & Healthcare Analytics"
    and a simple indication that the frontend is running.

11. Do NOT connect MySQL yet. We will do database setup in Phase 2.

12. Do NOT install or use K-Means yet.

13. Make sure the frontend and backend can be run independently.

14. Provide exact Windows CMD commands for installing dependencies and running both applications.

15. At the end, provide a checklist of tests I should perform.

IMPORTANT:
- Do not assume packages are already installed.
- Do not overwrite unrelated existing files.
- Keep the implementation beginner-friendly.
- Do not use hardcoded passwords or API keys.
- Do not put secrets into GitHub.
- Explain every file you create.
- If something fails, stop and explain the error rather than hiding it.
- Do not proceed to Phase 2 until I explicitly tell you that Phase 1 works.

At the end of your response, clearly state:
"PHASE 1 COMPLETE — WAITING FOR USER TESTING"
