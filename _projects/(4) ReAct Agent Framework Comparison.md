---
name: ReAct Agent Framework Comparison
category: GenAI
weight: 0
tools: [Python, FastAPI, React, TypeScript, Vite, Tailwind CSS, SQLite, LangGraph, Anthropic, OpenAI, Google Agent SDK, Docker]
image: /images/react_agent_demo_1_chat_agents_compare.png
description: A full-stack web application to compare AI agent frameworks side-by-side. Run up to 3 different agents (LangGraph, Google Agent ADK, OpenAI Agent SDK, and Anthropic Claude) simultaneously with the same prompt and see how they perform with trace visualization and performance metrics.

---

# Agent Framework Comparison

A full-stack web application to compare AI agent frameworks side-by-side. Run up to 3 different agents simultaneously with the same prompt and see how they perform.

💻 **Code Base** [GitHub Repository](https://github.com/FrozenOolong/agent-framework-comparison)

🛠️ **Built With:** React • TypeScript • FastAPI • Python • Docker • LangGraph • Anthropic • OpenAI • Google Agent SDK

---

## Overview

This project enables developers and decision-makers to evaluate different AI agent frameworks in real-time. Compare LangGraph, Google Agent ADK, OpenAI Agent SDK, and Anthropic Claude (manual ReAct loop setup) side-by-side with identical inputs and tools.

---

## Key Features

### Core Capabilities
- **Multi-Agent Comparison**: Run 1-3 agents in parallel and compare responses side-by-side
- **Customizable System Prompts**: Edit system prompts per conversation for tailored agent behavior
- **Agent Trace Visualization**: Expandable view of reasoning steps (Thought → Action → Observation)
- **Wikipedia Search Tool**: All agents share a common Wikipedia search tool
- **Performance Metrics**: Token count, latency, and step count per agent
- **Session Management**: Persistent conversations with follow-up question support
- **Chat History**: Local SQLite database stores all conversations for later review
- **Dark/Light Theme**: Toggle between themes

### Supported Agent Frameworks
- **[LangGraph](https://docs.langchain.com/oss/python/langchain/agents)**: ReAct agent implementation
- **[Google Agent ADK](https://google.github.io/adk-docs/get-started/python/)**: Google AI SDK agent with function calling
- **[OpenAI Agent SDK](https://openai.github.io/openai-agents-python/)**: OpenAI Agents SDK implementation
- **Anthropic Claude**: Custom ReAct implementation (loop + tool calling) without using any framework as baseline comparison

---

## Demo

### Chat Interface - Compare Multiple Agents Side by Side
![Chat Interface](/images/react_agent_demo_1_chat_agents_compare.png)

### Agent Step Tracing - View Reasoning Process
![Agent Step Tracing](/images/react_agent_demo_2_agent_call_steps_tracing.png)

### Follow-up Questions - Test Session Management
![Agent Follow Up Chat](/images/react_agent_demo_3_chat_follow_up_questions.png)

### Dark Mode Support
![Dark Mode](/images/react_agent_demo_4_dark_mode.png)

---

## Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** - Fast development server and build tool
- **Tailwind CSS** - Utility-first styling with dark/light theme
- **Axios** - HTTP client for API requests
- **React Context API** - State management

### Backend
- **FastAPI** - Modern Python web framework
- **SQLite** - Local database for conversation persistence
- **LangGraph** - LangGraph agent implementation
- **LiteLLM** - Unified LLM interface
- **Anthropic** - Claude integration
- **OpenAI Agent SDK** - OpenAI Agents SDK
- **Google Agent SDK** - Google Agent ADK

### Deployment
- **Docker** & **Docker Compose** - Containerized deployment with automatic setup