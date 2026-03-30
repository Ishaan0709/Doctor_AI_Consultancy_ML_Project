🏥 Personalized Doctor AI Agent

An AI-powered medical consultation system that predicts the appropriate medical department based on symptoms and evaluates patient risk using machine learning models.

🚀 Overview

This project is designed to simulate a smart medical assistant that helps users:

Identify the relevant medical department
Assess risk severity (0–100 score)
Provide real-time AI-based guidance
Assist in emergency decision-making
🧠 Features
🔍 Symptom-based department prediction
📊 Risk scoring system with severity classification
⚡ Real-time consultation interface using Streamlit
🤖 AI chatbot for personalized medical guidance
🚨 Emergency rule-based overrides for critical cases
🏗️ Tech Stack
Programming Language: Python
Frontend/UI: Streamlit
Machine Learning: Scikit-learn
Data Handling: Pandas
AI Integration: LangChain, OpenAI API
🤖 Machine Learning Models Used

The system is trained on doctor-curated datasets using:

Logistic Regression (LR)
Random Forest (RF)
Gradient Boosting (GB)
Support Vector Regressor (SVR)
K-Nearest Neighbors (KNN)
📊 Risk Score System
Generates a risk score from 0 to 100
Categorizes patients into severity levels:
🟢 Low Risk
🟡 Medium Risk
🔴 High Risk
🖥️ Application Interface
Built using Streamlit
Provides:
Structured symptom input
Instant predictions
Dynamic AI responses
User-friendly dashboard
⚙️ How It Works
User inputs symptoms
ML models analyze the input
System predicts:
Medical department
Risk score
AI agent provides:
Guidance
Suggestions
Emergency alerts (if needed)
📦 Installation
# Clone the repository
git clone https://github.com/your-username/personalized-doctor-ai-agent.git

# Navigate to project folder
cd personalized-doctor-ai-agent

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
📁 Project Structure
├── data/
├── models/
├── app.py
├── requirements.txt
├── utils/
└── README.md
🎯 Future Improvements
🧬 Integration with real-time health datasets
📱 Mobile app version
🧑‍⚕️ Doctor feedback loop for continuous learning
🌍 Multi-language support
⚠️ Disclaimer

This project is for educational and research purposes only.
It is not a substitute for professional medical advice.

👩‍💻 Author

Mehak,Ishaan Sharma
