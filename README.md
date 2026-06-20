Persona-Adaptive Customer Support Agent
Features
Persona Detection
RAG using FAISS
Gemini Integration
Escalation Workflow
Streamlit UI
Setup
pip install -r requirements.txt
streamlit run app.py
Enter your Gemini API key in the sidebar.

Architecture
User Query -> Persona Detection -> FAISS Retrieval -> Gemini Response Generation -> Escalation Check -> UI Output
