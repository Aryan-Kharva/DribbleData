# 🏀 DribbleData  

DribbleData is a web application that allows users to explore NBA statistics through **interactive charts, filters, and summaries**.  
It also features a **custom-built AI chatbot** that answers basketball-related queries using the OpenAI API.  

---

## 📖 More About This Project  
- Developed as a **team project** for our class, combining interests in basketball and data visualization  
- Lets users explore **NBA stats** with interactive visualizations and search tools  
- Includes an **AI-powered chatbot** trained to answer basketball-related queries  
- Demoed at our final showcase — I presented the chatbot integration and explained how it was built  

---

## 💡 My Contributions  
- Implemented the **entire chatbot feature** (frontend + backend) using the OpenAI API  
- Led the **frontend development**, designing a clean, responsive UI  
- Assisted teammates with debugging and integration across other modules  

---

## ✨ Key Features  
- 🤖 AI chatbot powered by OpenAI  
- 📊 Player & team statistics visualized with charts  
- 🔍 Dynamic filters and dropdowns for categories, seasons, and teams  
- 🎨 Clean, responsive UI (HTML, CSS, JavaScript + Flask)  
- 👥 Collaborative development with modularized frontend/backend logic  

---

## ⚙️ Tech Stack  
- **Backend:** Python, Flask, SQLAlchemy, nba_api  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite  
- **AI:** OpenAI GPT API  
- **Other:** dotenv, Werkzeug  

---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.9+  
- pip (Python package manager)  
- OpenAI API key  
- Secret key for Flask sessions  

## Installation  

# #1. Clone this repo  

   git clone https://github.com/yourusername/dribbledata.git
   cd dribbledata

# #2. Create and activate a virtual environment

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


# #3. Install dependencies

pip install -r requirements.txt


Set up environment variables in a .env file:

OPENAI_API_KEY=your_openai_api_key_here
SECRET_KEY=your_flask_secret_key_here


# #4. Run the app

python app.py

Visit in your browser:

http://127.0.0.1:5000/


## Challenges

Managing async responses from the OpenAI API and rendering them in the chat window

Troubleshooting deployment bugs and external API data inconsistencies


## What I Learned

Integrating real-time AI tools into web applications

Managing state across asynchronous operations

Sharpened frontend design skills

Gained experience with team collaboration and version control
