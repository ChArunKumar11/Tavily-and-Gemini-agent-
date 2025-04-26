# Tavily-and-Gemini-agent-
Gemini-powered ReAct AI Agent with Tavily Search
This project builds a smart AI research assistant using:

Google Gemini 1.5 Flash as the language model

Tavily as the web search tool

LangChain and LangGraph for agent orchestration

Rich for beautiful terminal outputs

The agent:

Accepts up to 3 user questions at a time.

Dynamically searches the internet when needed using Tavily.

Generates responses based on live information and user queries.

Streams answers interactively in the terminal, showing when a tool (search) is being called.

🔥 Tech Stack
Google Generative AI (gemini-1.5-flash)

Tavily Web Search

LangChain

LangGraph

Python

Rich (for colorful terminal outputs)

🚀 How It Works
The user enters 1–3 questions.

The AI agent intelligently decides when to search the internet using Tavily.

The AI answers each question step-by-step, making multiple tool calls if needed.

All outputs are beautifully formatted for easy reading.

📋 How To Run
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Set your environment variables in a .env file:

ini
Copy
Edit
GOOGLE_API_KEY=your_google_generative_ai_key
TAVILY_API_KEY=your_tavily_key
Run the script and interact with the AI assistant!

✨ Features
Multi-turn conversational search and reasoning.

Real-time web results via Tavily.

Supports dynamic multiple prompts without restarting the script.

Beautiful, color-coded console experience.

