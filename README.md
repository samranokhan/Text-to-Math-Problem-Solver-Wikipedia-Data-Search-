# Text-to-Math-Problem-Solver-Wikipedia-Data-Search-
n interactive Streamlit app that solves complex math problems and retrieves factual data using Wikipedia — powered by LangChain, Groq LLM (Gemma2-9b-It), and Streamlit.

Features
Math Problem Solver

Converts natural language math queries into step-by-step solutions.
Uses LLMMathChain for accurate logical calculations.
Wikipedia Search

Retrieves concise summaries and information about any topic using WikipediaAPIWrapper.
Reasoning Tool

Handles logic-based or explanatory queries beyond simple math.
Streamlit Chat UI

Conversational interface with message history.
Tech Stack
Frontend: Streamlit
LLM Provider: Groq (Gemma2-9b-It)
Framework: LangChain
Data Source: Wikipedia API
How It Works
User enters a query (math problem or knowledge question).
Agent decides:
Solve math via Calculator (LLMMathChain)
Retrieve info via Wikipedia Tool
Perform reasoning via Reasoning Tool
Returns detailed, point-wise solution or factual summary.
