🚀 NASA Space Biology Dashboard

 🧬 Challenge Statement
 
Advancing Human Space Exploration through Space Biology Analytics This project addresses the critical need for a comprehensive platform that enables researchers to explore, analyze, and understand the effects of space travel on terrestrial biology. By integrating experimental datasets and machine learning models, the dashboard provides actionable insights into biological responses under spaceflight conditions.
  
 🌌 Overview
 
The dashboard is a web-based interface that allows users to interactively explore space biology datasets, visualize relationships between entities via knowledge graphs, and access AI-driven summaries of relevant scientific literature. It serves as a centralized tool for biologists, data scientists, and space researchers to investigate and interpret complex spaceflight experimental data efficiently.
  
🔧 Key Features
 
- AI Article Summarization: Integrates with OpenAI API to generate concise, scientifically accurate summaries of external research articles.
 
- Search Functionality: Enables users to query datasets and literature efficiently, supporting both keyword and semantic search.
 
- Knowledge Graph Visualization: Depicts relationships among biological entities, experiments, and outcomes, facilitating rapid insight generation.
 
- Interactive Dashboard: Provides a user-friendly interface for data exploration, model interaction, and visualization of analytical results.

🛠️ Setup and Execution
 
Prerequisites
- Node.js (latest stable version)
- Python 3.11+
- Docker (optional, for containerized deployment)
- OpenAI API key
 
 Frontend Setup
 `git clone https://github.com/Nadeem1221/Nasa-space-biology.git cd Nasa-space-biology npm install npm start ` 
Backend Setup (AI Service)
 `cd ai_service python -m venv .venv source .venv/bin/activate       Windows: .venv\Scripts\activate pip install -r requirements.txt export OPENAI_API_KEY="your_openai_api_key" uvicorn api:app --host 0.0.0.0 --port 8000 ` 
Docker Deployment (Optional)
 
Frontend:
 `cd frontend docker build -t nasa-frontend . docker run -p 3000:3000 nasa-frontend ` 
Backend:
 `cd ai_service docker build -t nasa-backend . docker run -e OPENAI_API_KEY="your_openai_api_key" -p 8000:8000 nasa-backend `  
🏗️ Technical Architecture

✅ Compliance with Submission Requirements

1. Complete Project Folder– Fully functional dashboard including frontend and backend.
 
2. README.md– Includes project title, challenge statement, overview, key features, setup instructions, technical architecture, AI workflow, and team members.
 
3. Dependency Management– `requirements.txt` and `package.json` provided for reproducible deployment.

WEBSITE URL: https://9ade42f9-37c5-4f20-9546-84e21d591dcb-00-2ivwj5teacrto.sisko.replit.dev/