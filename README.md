# MultiAgent with Autogen - An Agentic AI Approach

This repository demonstrates the implementation of a multi-agent system using Microsoft's Autogen framework, showcasing an agentic AI approach to problem-solving and task automation.

## 🎯 Project Overview

This project explores the creation and orchestration of multiple AI agents using Autogen, demonstrating how different agents can collaborate, communicate, and solve complex tasks together. The implementation is done using Jupyter Notebooks, making it interactive and easy to understand.

## 🤖 Agents and Their Roles

The multi-agent system includes several specialized agents:

1. **Assistant Agent**
   - Primary problem-solving agent
   - Handles general queries and task coordination
   - Provides strategic oversight

2. **Code Agent**
   - Specializes in code generation and review
   - Handles technical implementation
   - Performs code debugging and optimization

3. **User Proxy Agent**
   - Acts as an interface between human users and other agents
   - Validates and approves critical decisions
   - Manages task flow and delegation

## 🔄 Orchestration Process

The agents work together through the following orchestration flow:

1. **Task Initiation**
   - User input is received through the User Proxy Agent
   - Initial task analysis and breakdown

2. **Task Distribution**
   - Tasks are assigned to specialized agents
   - Concurrent processing when possible

3. **Collaboration & Execution**
   - Inter-agent communication for complex tasks
   - Real-time feedback and adjustments
   - Solution verification and validation

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/md-junaid79/MultiAgent-with-Autogen-.git
   cd MultiAgent-with-Autogen-
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup environment**
   - Configure your OpenAI API key
   - Install Jupyter Notebook if not already installed
   ```bash
   pip install jupyter
   ```

4. **Run the notebooks**
   ```bash
   jupyter notebook
   ```

## 📘 Usage Examples

The Jupyter notebooks in this repository contain detailed examples and demonstrations of:
- Agent initialization and configuration
- Inter-agent communication patterns
- Task execution workflows
- Error handling and recovery
- Advanced orchestration scenarios

## 🛠️ Technical Requirements

- Python 3.8+
- Autogen library
- OpenAI API key
- Jupyter Notebook

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

- GitHub: [@md-junaid79](https://github.com/md-junaid79)

## ⭐ Acknowledgements

- [Microsoft Autogen](https://github.com/microsoft/autogen)
- Special thanks to the Autogen community

---

*Note: This is a research/educational project demonstrating the capabilities of agentic AI systems using Autogen.*
