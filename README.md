# AI Health & Fitness Plan Generator 

This is an AI-powered personal health assistant that creates **fully personalized** fitness and meal plans based on your:

- **Body type**
- **Activity level**
- **Dietary preference**
- **Fitness goals**

Built using [Agno](https://github.com/agno-agi/agno), [Google Gemini](https://ai.google.dev/), and deployed with [Streamlit](https://streamlit.io/).

---

## Features

1. Personalized Fitness Plan  
2. Goal-based Nutrition Guidance  
3. Supports Keto, Low Carb, Vegetarian, and Balanced diets  
4. Automatically tailors workouts for weight loss, muscle gain, flexibility, and endurance  
5. Stylish and responsive UI  
6. Gemini-powered smart agent planning

---

##  Demo

> Live Streamlit Demo Link: https://fitness-coach-ai-agent.streamlit.app/ 

---

## Tech Stack

- **Language**: Python 3.10+
- **UI**: Streamlit
- **AI Agent Framework**: [Agno](https://github.com/agno-agi/agno)
- **LLM Model**: Google Gemini (via `google-generativeai`)

---

## Secure Your API Key

This project uses Google Gemini for AI generation. Add your API key in `.streamlit/secrets.toml`:

```toml
[google]
api_key = "your-google-api-key-here"
