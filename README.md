# Marvellous-SmartHire-AI-Mock-Interview-Agent

An AI-powered, text-based Mock Interview Agent built using Python and Llama 3.2 through Ollama. It conducts technical interviews, evaluates student answers using Large Language Models (LLMs), provides detailed feedback, calculates performance scores, and generates automated interview reports.

## Features

- **Full Interview Mode:** Conducts interviews covering multiple technical topics.
- **Topic-wise Interview:** Allows students to practice specific technical subjects.
- **AI Answer Evaluation:** Evaluates answers using Llama 3.2.
- **Intelligent Feedback:** Provides scores, missing technical points, improved answers, and interview suggestions.
- **Performance Analysis:** Calculates total and average interview scores.
- **Interview History:** Maintains question-wise answers and evaluation records.
- **Automated Report Generation:** Generates and saves detailed interview reports as text files.
- **Local LLM Integration:** Uses Ollama to run Llama 3.2 locally.

## Technologies Used

- Python
- Generative AI
- Large Language Models (LLMs)
- Ollama
- Llama 3.2 (1B)
- Prompt Engineering
- Requests Library
- AI Agents

## Project Architecture

The project consists of five Python files:

| File Name | Description |
|---|---|
| `main.py` | Main application, interview flow, and menu management. |
| `interview_agent.py` | AI agent responsible for answer evaluation, scoring, history, and report generation. |
| `llm_engine.py` | Connects Python with the locally running Llama 3.2 model through Ollama API. |
| `questions.py` | Contains technical interview questions categorized by topic. |
| `report_generator.py` | Generates and saves timestamped interview reports. |

## AI Interview Workflow

1. Student enters their name.
2. Selects Full Interview or Topic-wise Interview.
3. AI agent displays technical questions.
4. Student submits answers through text input.
5. Answers are evaluated by Llama 3.2 using prompt engineering.
6. AI generates scores, feedback, missing points, and improved answers.
7. Interview history and performance scores are maintained.
8. A final interview report is generated and saved automatically.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd Marvellous-SmartHire-AI-Mock-Interview-Agent
```

### 3. Install Python Dependencies

```bash
pip install requests
```

### 4. Install Ollama

Download and install Ollama:

https://ollama.com/

### 5. Download Llama 3.2 Model

Open the terminal and execute:

```bash
ollama pull llama3.2:1b
```

### 6. Start Ollama

Make sure the Ollama server is running locally. The application communicates with it through:

```text
http://localhost:11434/api/generate
```

### 7. Run the Project

```bash
python main.py
```

## Interview Topics

The question bank currently covers:

- Python
- Object-Oriented Programming (OOP)
- Machine Learning
- Deep Learning
- Transformers
- Large Language Models (LLMs)
- Retrieval Augmented Generation (RAG)
- AI Agents

## Interview Report

The system automatically creates a `reports` folder and saves timestamped interview reports containing:

- Student information
- Total questions asked
- Total and average scores
- Overall performance analysis
- Question-wise student answers
- AI-generated evaluations and feedback

## Concepts Implemented

- AI Agent Development
- Large Language Model Integration
- Prompt Engineering
- REST API Communication
- Automated Answer Evaluation
- Exception Handling
- Interview History and Memory
- Performance Scoring
- Automated Report Generation

## Future Enhancements

- Develop a Streamlit-based interactive web interface.
- Add voice-based interview functionality.
- Support dynamic question generation.
- Include multiple LLM models.
- Add interview history storage using a database.

## Author

**Diksha Kadu Vispute**


