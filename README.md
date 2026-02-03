# 📝 AI Blog Generator using LangChain & LangGraph

This project is about building an **AI-based blog generator** using **LangChain** and **LangGraph**, following the **Orchestrator–Worker approach**.

Instead of generating a blog in one go, the system breaks the work into smaller tasks and handles them step by step, just like a team would.

## 🌱 What This Project Does

The project creates blogs by organizing the work between multiple AI agents:
- One part understands the topic
- Another creates the blog outline
- Another writes the content
- Another improves and formats the final output

An **Orchestrator** controls the entire flow and decides which worker should run at each step.

## 🧠 Why Orchestrator–Worker?

This pattern makes the system:
- Easier to understand
- Easier to modify or expand
- More reliable and structured

Each worker focuses on a single responsibility, while the orchestrator keeps everything in sync.

## 🛠️ Tools & Technologies

- Python
- LangChain
- LangGraph
- Large Language Models (LLMs)

## ✨ Key Highlights

- Step-by-step blog creation
- Clear separation of tasks
- Flexible and modular design
- Ideal for learning multi-agent workflows

## 📌 Who This Is For

- Developers learning LangChain & LangGraph
- Anyone exploring AI agent workflows
- Content automation experiments
- Students and researchers

## 🚧 Project Status

This project is mainly built for learning and experimentation and may evolve over time.

## 🤝 Contributions

Feel free to explore, experiment, and improve the project.

---

### 👋 About the Project

This project was created to better understand how **LangChain**, **LangGraph**, and **orchestrator-based AI systems** work together in real-world use cases.
