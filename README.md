# llm-comparison-spring/ LLM Comparison Engine

This repository contains a Spring Boot application that demonstrates the integration of multiple Large Language Models (LLMs) of Ollama including lamma, Gemma 2, and Deepseek, using the Spring AI library. The project also includes a React-based UI for comparing responses from different models.

# Project Structure 
```
  llm-comparison-project/
│
├── frontend/           # React app (VS Code)
│   ├── src/
│   ├── package.json
│   └── README.md
│
├── backend/            # Java APIs for communicating with Ollama (IntelliJ)
│   ├── src/
│   ├── pom.xml or build.gradle
│   └── README.md
│
├── .gitignore
└── README.md
```
# FEATURES

1.Integration with multiple LLM providers: (GPT models)
  Anthropic (Claude models)
  Ollama (Local models)
2. REST API endpoints for interacting with each LLM
3. React-based user interface for comparing model responses side-by-side
3. Configurable prompts and model parameters.

# PREREQUISITES

1. Java 17 or higher
2. Maven 3.6 or higher
3. Node.js and npm (for the React UI)
4. Ollama installed locally
5. Pull the needed ollama models
   
### Frontend Setup

1. Navigate to the React UI directory:
   ```bash
   cd src/main/llm-comparison-ui
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the UI:
   ```bash
   npm run dev
   ```

npm run dev
