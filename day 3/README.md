# Day 3: Function Calling and Agentic Systems with LangGraph  

Welcome to **Day 3** of this learning journey! This repository provides practical insights and hands-on code labs on building advanced systems that leverage Generative AI's ability to perform function calling and create agentic applications.  

Generative AI models excel at reasoning and logic but often require external tools to access real-time information or execute real-world actions. This day’s content focuses on equipping models with these capabilities, using tools such as the **Gemini API** and **LangGraph**, while providing practical examples like chat-driven database querying and a simulated cafe ordering system.  

## Overview  

### Key Topics  
1. **Function Calling with Gemini API**  
   - Automatic function calling for real-time interactions.  
   - SQL query generation and interaction with a database.  
   - Stateful conversations powered by database retrieval tools.  

2. **Building Agentic Systems with LangGraph**  
   - Using LangGraph to create stateful, graph-based applications.  
   - Simulating real-world tasks, such as a cafe ordering system.  
   - Maintaining context across conversations and automating user workflows.  

### Why Agents?  
Humans often rely on tools—books, search engines, calculators—to enhance decision-making. Similarly, Generative AI models can integrate external tools to:  
- Access real-time or domain-specific information (e.g., retrieving a customer's purchase history).  
- Suggest and perform real-world actions (e.g., sending an email, completing transactions).  

Agents extend the standalone capabilities of a Generative AI model by incorporating reasoning, logic, and access to tools, allowing the model to plan and execute tasks autonomously.  

---

## Contents  

### Notebooks  

#### **1. Function Calling with Gemini API**  
- **File:** `day-3-function-calling-with-the-gemini-api.ipynb`  
- **Description:**  
  - Implements automatic function calling in Generative AI systems.  
  - Creates a chat interface over a local database.  
  - Demonstrates SQL query generation and database interaction.  
  - Examples of stateful conversations to handle multi-step queries.  

#### **2. Building an Agent with LangGraph**  
- **File:** `day-3-building-an-agent-with-langgraph.ipynb`  
- **Description:**  
  - Creates **BaristaBot**, a simulated cafe ordering system.  
  - Demonstrates stateful, graph-based application building.  
  - Handles user interactions, maintains context, and manages a menu system.  
  - Provides a complete end-to-end ordering system.  

---

### Whitepaper  

#### **Title:** *Building Agents with Generative AI*  
- **Key Takeaways:**  
  - Generative AI models can use external tools to extend their capabilities.  
  - They can retrieve information (e.g., database lookups) or perform actions (e.g., API calls).  
  - Agents are self-directed systems that combine reasoning, logic, and tool access.  
  - Practical use cases include shopping recommendations, order processing, and task automation.  

---

## How to Use  

1. Start with the **Function Calling with Gemini API** notebook to learn how Generative AI models interact with databases through function calling.  
2. Proceed to **Building an Agent with LangGraph** to implement an agent-based system, BaristaBot, and explore the concepts of stateful interactions and graph-based logic.  
3. Read the **whitepaper** for a theoretical foundation and detailed exploration of Generative AI agents.  

---

## Requirements  

- **Languages and Frameworks:** Python, SQL.  
- **APIs:** Gemini API, LangGraph framework.  
- **Tools:** Jupyter Notebook, database software (e.g., SQLite).  
- **Recommended Knowledge:** Basics of Generative AI, Python programming, and SQL.  

---

## Contributing  

We welcome contributions! If you have ideas to improve the notebooks or whitepaper, feel free to open an issue or submit a pull request.  

---

**Dive in and explore how function calling and agentic systems are revolutionizing Generative AI!**  
