# 🦁 Zoo Tour Guide — AI Agent

An AI-powered multi-agent chatbot built for the **Gen AI Academy APAC Edition**.  
It acts as a virtual tour guide for zoo visitors, answering questions about animals in real time.

## 🚀 Built With
- Google Agent Development Kit (ADK)
- Vertex AI (Gemini)
- Google Cloud Run
- LangChain + Wikipedia API
- Python

## 🧠 How It Works
1. User sends a message to the Greeter agent
2. The prompt is saved to state using add_prompt_to_state tool
3. A SequentialAgent workflow kicks in:
   - Researcher Agent searches Wikipedia for animal facts
   - Formatter Agent turns the data into a friendly response
4. Final answer is streamed back to the user

## Cloud Deployment
Deployed on Google Cloud Run using ADK deploy command.

## 👤 Author
Anita Kumari
Gen AI Academy APAC Edition — Track 1: Build and Deploy AI Agents
