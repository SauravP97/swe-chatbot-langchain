# Chatbot for SWE Interviews in LangGraph :pager: :hourglass_flowing_sand:

The repository holds the implementation of Chatbot designed to answer Software Engineering and Coding Interview questions. The chatbot tries to answer the question related to this topic. If the question asked is out of context then the chatbot responds with an exception message.

The entire ChatBot architecture is built on [LangGraph.js](https://github.com/langchain-ai/langgraphjs/). A library for building stateful, multi-actor applications with LLMs, used to create agent and multi-agent workflows by [LangChain](https://github.com/langchain-ai).

![Chatbot](/media/chatbot.png)

## ChatBot architecture

The architecture comprises of multiple nodes/agents doing a specific task and talking to each other via edges and shared state.

![Architecture Design](/media/arch.png)

## Installing Dependencies:

    - Install Typescript: npm install typescript
    - Install Dotenv: npm install dotenv
    - Install LangChain libraries: 
        - npm install langchain
        - npm install @langchain/community  
        - npm install @langchain/core
        - npm install cheerio
        - npm install @xenova/transformers