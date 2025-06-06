# 🧠 CrewAI Travel Advisor using Gemini

This project demonstrates the implementation of a **Travel Advisor Agent System** using [CrewAI](https://www.crewai.io/) in combination with **Gemini (Google AI)** to provide personalized travel planning through agent collaboration.

## 🚀 Project Overview
The objective of this project is to simulate a team of AI agents working collaboratively to offer users a comprehensive and interactive travel advisory experience. Each agent performs a specialized task, contributing to the final travel plan based on user input.

## ✨ Features
- 🤖 Multi-agent system powered by CrewAI  
- 🧭 Travel planning based on user preferences  
- 🌐 Integration with Gemini LLM for intelligent response generation  
- 🧩 Modular architecture using agents, tasks, and crew management  
- 📓 Jupyter Notebook-based prototype  

## 🧱 Components
1. **Agents**: Defined for roles like itinerary planner, budget advisor, and local guide.  
2. **Tasks**: Each agent is assigned a specific task aligned with its role.  
3. **Crew**: A group of agents working collectively on a mission.  
4. **LLM Integration**: Utilizes Gemini for prompt handling and content generation.

## 🛠️ Installation

### 📦 Requirements
```bash
pip install -r requirements.txt
```

Typical requirements:
- `crewai`  
- `langchain`  
- `google-generativeai`  
- `python-dotenv`  
- `ipykernel`  
- `notebook`  

Create a `.env` file and add your Gemini API key:
```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

## 📋 Usage
1. Launch Jupyter:
```bash
jupyter notebook
```
2. Open `CrewAI_Using_Gemini_Travel_advisor.ipynb`  
3. Run the notebook cells to:
   - Initialize agents  
   - Define tasks  
   - Assemble the crew  
   - Run the travel advisor system  

## 📌 Example Output
```
🧳 User Query: Plan a 5-day budget trip to Paris with cultural activities.  
📋 Output:
  - Day 1: Eiffel Tower, Louvre Museum  
  - Day 2: Montmartre walking tour  
  - ...  
💸 Budget Suggestion: $1200 including stay and meals
```

## 📚 Resources
- [CrewAI Documentation](https://docs.crewai.io/)  
- [Gemini API](https://ai.google.dev/)  
- [LangChain Docs](https://docs.langchain.com/)

## 🤝 Contributing
Feel free to fork this repository and contribute with ideas, bug fixes, or improvements!

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

## 🙋 Author
**Jagannath Panigrahi**  
🔗 [GitHub](https://github.com/Jaggu07-P) | 🌐 Data Analyst | AI Enthusiast
