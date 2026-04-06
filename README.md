🩺 Medical Image Analysis AI Agent
A Streamlit-based web application that leverages Gemini 3 Flash and Agno (Phidata) agents to analyze medical images (X-rays, MRIs, CT scans) and provide research-backed diagnostic insights.

🌟 Features
Multimodal Analysis: Uses Gemini 3 Flash to "see" and interpret medical images.

AI Agentic Research: Integrated with DuckDuckGo Tools to fetch real-time 2026 clinical guidelines and treatment protocols.

Structured Reporting: Generates professional reports including:

Image Type & Anatomical Region identification.

Detailed Key Findings.

Differential Diagnosis with confidence levels.

Patient-friendly explanations with analogies.

Streamlit UI: A clean, sidebar-driven interface for easy image uploads.

🛠️ Tech Stack
Language: Python 3.10+

AI Framework: Agno (formerly Phidata)

Model: Google Gemini 3 Flash (via Google AI Studio)

Frontend: Streamlit

Search Tool: DuckDuckGo Search

🚀 Getting Started
1. Prerequisites
A Google AI Studio API Key. Get it here: Google AI Studio

2. Installation
Clone the repository and install the dependencies:

Bash
git clone https://github.com/your-username/medical-image-ai.git
cd medical-image-ai
pip install -r requirements.txt
3. Environment Setup
Create a .env file or export your API key:

Bash
export GOOGLE_API_KEY='your_api_key_here'
4. Running the App
Bash
streamlit run streamlit_app.py
📂 Project Structure
Plaintext
├── .streamlit/
│   └── secrets.toml       # (Optional) For local API key storage
├── streamlit_app.py       # Main application code
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
⚠️ Medical Disclaimer
IMPORTANT: This application is for educational and research purposes only.

It is not intended to be used as a primary diagnostic tool.

The AI may hallucinate or misinterpret medical imagery.

Always consult with a board-certified radiologist or medical professional for clinical diagnosis.

Privacy Note: On the Google AI Studio Free Tier, images uploaded may be used by Google to improve their models. Do not upload sensitive patient data.
