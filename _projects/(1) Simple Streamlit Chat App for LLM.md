---
name: Multi-Model LLM Chat Application
weight: 1
tools: [Python, Streamlit, OpenAI API, Anthropic API, Google Gemini, DeepSeek, LLM]
image: /images/chat_demo_1_select_model_option.gif
description: Built a versatile chatbot application supporting multiple LLM providers (GPT, Claude, Gemini, DeepSeek) with Streamlit web interface. Features custom bot creation, conversation history management, and both terminal and web interfaces.

---

# simple-multi-model-chat
Portfolio project showcasing a simple multi-model chatbot. Chat with LLMs from OpenAI (GPT), Anthropic (Claude), DeepSeek, and Google (Gemini). Includes both a terminal interface and a Streamlit web app, with options for custom bots and local chat history.

💻 **Code Base** [Code](https://github.com/FrozenOolong/simple-multi-model-chat)
🛠️ **Built With:** Python • Streamlit • LLM API • Local Deployment

## Key Features
- **Chatbot with selected model**: Use chat from various model selection from the dropdown in the sidebar: select from Claude and OpenAI models. You can see available model options on `utils.py`

    ![App Demo for select model on the sidebar](images/chat_demo_1_select_model_option.gif)

- **Simple chat interface**: User can type their questions and see model response.

    ![App Demo for chatting](images/chat_demo_2_chat_response.gif)

- **Custom Chatbot**: Ability to create custom chatbot - you can save custom system prompts for some commonly tasks, similar to custom GPT feature. Default example provided for email write, based on your prompt, it will generate a email response. You can see available custom chatbot under `custom_configs` folder. You can create a new chatbot on the side bar or create a similar JSON file.

    ![App Demo for chatting](images/chat_demo_3_manage_custom_chat.gif)

- **Locally Saved Historical Conversations**: All your conversations will be saved as JSON file under `conversations` folder. If the folder does not exist, it will auto create the folder. You can review your previous conversations, retrieve and continue the conversation, or manage the conversation history.

    ![App Demo for chatting](images/chat_demo_4_chat_history.gif)
