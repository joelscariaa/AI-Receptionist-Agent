AI RECEPTIONIST AGENT

============================================================

PROJECT OVERVIEW

An AI-powered virtual receptionist designed to automate appointment scheduling, customer interactions, and business inquiries through natural conversations. The system combines conversational AI with backend automation to provide a seamless receptionist experience for businesses.

FEATURES

- Appointment Scheduling
- Customer Information Collection
- Conversational AI Support
- Automated Record Management
- FAQ Handling
- Real-Time Customer Assistance

TECH STACK

Frontend:
- VAPI Voice Interface

Backend:
- Python
- FastAPI

AI Model:
- Google Gemini API

Data Management:
- Pandas
- Excel Storage

Deployment:
- Uvicorn
- Ngrok

INSTALLATION

1. Clone Repository

git clone https://github.com/your-username/AI-Receptionist-Agent.git
cd AI-Receptionist-Agent

2. Create Virtual Environment

python -m venv venv

Windows:
venv\Scripts\activate

Linux/Mac:
source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt

ENVIRONMENT VARIABLES

Create a .env file:

GEMINI_API_KEY=your_gemini_api_key

RUN APPLICATION

uvicorn main:app --reload

Default Server:
http://127.0.0.1:8000

NGROK SETUP

ngrok http 8000

WORKFLOW

1. Customer contacts AI receptionist.
2. AI greets customer.
3. Customer requests appointment.
4. AI collects booking details.
5. Appointment is stored automatically.
6. AI confirms appointment.

FUTURE IMPROVEMENTS

- Google Calendar Integration
- Email Notifications
- WhatsApp Integration
- PostgreSQL/MySQL Support
- CRM Integration
- Multi-language Support

USE CASES

- Hospitals
- Clinics
- Salons
- Educational Institutions
- Corporate Offices
- Service Centers

AUTHOR

[Your Name]

B.Tech Artificial Intelligence & Machine Learning
Christ University, Bangalore

LICENSE

This project is intended for educational, research, and portfolio purposes.

If you found this project useful, consider giving it a star on GitHub.
