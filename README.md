# Prompt Engineering Lab

A comprehensive collection of 16-week Prompt Engineering and LLM application lab experiments, exercises, and outputs.

---

## 📚 Curriculum & Repository Structure

Each week is organized in its own dedicated subfolder containing the experiment source code, lab scripts, and execution outputs:

| Week | Topic | Description |
| :--- | :--- | :--- |
| **[week1](./week1)** | Basic Prompt Engineering | Introduction to prompt design and Groq/LLM API setup. |
| **[week2](./week2)** | Baseline vs. Enhanced Prompts | Comparing zero-context baseline prompts with structured, enhanced prompts. |
| **[week3](./week3)** | Iterative Refinement | Step-by-step prompt iteration to improve accuracy and tone. |
| **[week4](./week4)** | Diagnosing Prompt Failures | Analyzing ambiguity, hallucinations, and prompt failure modes. |
| **[week5](./week5)** | Zero-Shot vs. Few-Shot Classification | Evaluating sentiment classification performance with few-shot exemplars. |
| **[week6](./week6)** | Role-Based & Negative Prompting | Defining system personas and negative constraints to guide LLM behavior. |
| **[week7](./week7)** | Constraint Specification | Hard and soft constraint specification and iterative boundary testing. |
| **[week8](./week8)** | Structured Format Prompting | Enforcing markdown tables, bullet formats, and template guidelines. |
| **[week9](./week9)** | JSON / YAML Generation | Schema-enforced structured data extraction and parsing. |
| **[week10](./week10)** | Chain-of-Thought & Task Decomposition | Multi-step reasoning and sub-task decomposition techniques. |
| **[week11](./week11)** | Prompt Templates & Output Parsers | LangChain prompt templates, ChatGroq integration, and string parsers. |
| **[week12](./week12)** | RAG Data Indexing using FAISS | Text chunking, HuggingFace embeddings, and vector store creation. |
| **[week13](./week13)** | Retrieval Augmented Generation (RAG) | End-to-end RAG question answering over indexed documents. |
| **[week14](./week14)** | Building LLM Agents | Introduction to LLM agents using LangGraph and tool calling. |
| **[week15](./week15)** | Agent Workflows & Tools | Multi-tool integration, execution loops, and autonomous problem solving. |
| **[week16](./week16)** | Prompt Evaluation & Ethics | Bias testing, safety guardrails, hallucination evaluation, and ethics. |

---

## 🛠️ Setup & Prerequisites

Most labs require Python 3.10+ and standard LLM / LangChain packages.

```bash
pip install openai langchain langchain-community langchain-google-genai langchain-groq langgraph faiss-cpu python-dotenv pandas
```

Ensure you configure your environment variables (e.g. in a `.env` file) for required provider API keys:
- `OPENAI_API_KEY`
- `GROQ_API_KEY`
- `GOOGLE_API_KEY`
