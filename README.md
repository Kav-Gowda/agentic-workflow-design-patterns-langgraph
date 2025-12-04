# 📘 Agentic Workflow Design Patterns with LangGraph

This repository explores core agentic AI workflow design patterns using LangGraph, focusing on routing, parallel execution, multi-step reasoning, and modular pipeline construction. The project demonstrates how agentic systems can be built and orchestrated using open-source LLMs in a reproducible, Colab-friendly setup.

The notebook uses free Hugging Face models instead of paid APIs, making it ideal for portfolio work, experimentation, and demonstrating practical agentic system design without API keys or cost barriers.

---

## 🚀 Project Overview

This project implements several foundational agentic workflow patterns:

### 1. Routing Workflow  
A pattern where an agent analyzes user input and routes the request to the appropriate task:
- Task classification (summarize vs. translate)  
- Conditional branching using LangGraph  
- Modular, reusable nodes  

### 2. Parallel Execution Workflow  
A fan-out / fan-in pattern demonstrating:
- Running multiple translation nodes in parallel  
- Aggregating results into a combined output  
- Coordinating independent agent tasks inside one shared graph  

These reflect real-world agentic system requirements such as:
- Intelligent task routing  
- Multi-agent coordination  
- Combining outputs from parallel reasoning paths  

---

## 🧠 Why This Project Matters

Modern AI systems increasingly rely on agentic architectures, not single-prompt LLM calls.  
This project demonstrates capabilities important for AI/ML engineering roles:

- Multi-step reasoning workflows  
- Composable pipeline design  
- Open-source LLM integration  
- Parallel node execution  
- State management and orchestration  
- Debugging and visualization of agentic workflows  

These patterns are foundational for building scalable and reliable AI assistants, automation flows, and multi-agent applications.

---

## 📂 Repository Structure

    agentic-workflow-design-patterns-langgraph/
    ├── agentic_workflow_design_patterns_langgraph.ipynb   # Main notebook  
    ├── README.md                                          # Project documentation  
    ├── requirements.txt                                   # Python dependencies  
    ├── .gitignore                                         # Git ignore rules  
    └── LICENSE                                            # MIT license  

---

## 🛠️ Tech Stack

- LangGraph – workflow orchestration  
- LangChain Core – model + messaging abstractions  
- Hugging Face Transformers – open-source LLMs  
- FAISS – vector indexing (optional)  
- Python 3.10+  
- Google Colab – recommended runtime  

---

## ▶️ How to Run

Clone the repo:

    git clone https://github.com/<your-username>/agentic-workflow-design-patterns-langgraph.git
    cd agentic-workflow-design-patterns-langgraph

Open the .ipynb notebook in **Google Colab**, run the setup cell to install the required packages, and execute the workflow sections step-by-step.

---

## 📘 Workflows Included

### 🔹 Routing Agent  
- Classifies user input  
- Routes to summarize or translate  
- Demonstrates conditional edges  

### 🔹 Parallel Translation Agents  
- Executes French, Spanish, and Japanese translation nodes in parallel  
- Aggregates the results  
- Demonstrates fan-out / fan-in execution  

---

## 🧩 Future Extensions

- Memory-enhanced agents  
- Tool-calling examples  
- Multi-agent negotiation  
- RAG-based workflows  
- Evaluation and monitoring patterns  

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 💬 Author

**Kavitha Lingarajegowda**  
Agentic AI Engineering | Automotive AI | LLM Systems  
LinkedIn | Portfolio

---

