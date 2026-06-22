# ReAct Web Research Agent

This project implements a ReAct (Reasoning + Acting) Agent that combines an LLM with Tavily Web Search to research a given topic and generate a structured report.

## Features

- Generates research questions using OpenAI GPT
- Searches the web using Tavily Search API
- Collects and organizes information
- Generates a structured research report
- Demonstrates the ReAct design pattern

## Technologies Used

- Python
- OpenAI API
- Tavily Search API

## Workflow

1. User enters a topic.
2. LLM generates research questions.
3. Tavily searches the web for answers.
4. Results are collected.
5. A final report is generated.

## Files

- `react_agent.py` – Main agent implementation
- `report.md` – Assignment explanation
- `requirements.txt` – Required libraries
