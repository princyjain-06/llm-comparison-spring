# llm-comparison-spring/ LLM Comparison Engine

This repository contains the frontend of Spring Boot application that demonstrates the integration of multiple Large Language Models (LLMs) of Ollama including lamma, Gemma 2, and Deepseek, using the Spring AI library. The project also includes a React-based UI for comparing responses from different models.

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
│   https://github.com/princyjain-06/llm-comparison-spring-backend.git
│
├── .gitignore
└── README.md
```
# FEATURES

1.Integration with multiple Ollama models: (Gemma), 
(Deepseek),
(Llama)
2. REST API endpoints for interacting with each LLM
3. React-based user interface for comparing model responses side-by-side
3. Configurable prompts and model parameters.

# PREREQUISITES

1. Java 17 or higher
2. Maven 3.6 or higher
3. Node.js and npm (for the React UI)
4. Ollama installed locally
5. Pull the needed ollama models

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/princyjain-06/llm-comparison-spring.git
  
   ```
2. Build the Spring Boot application:
   ```bash
   mvn clean package -DskipTests
   ```   
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

## Acknowledgements

- [Spring AI](https://spring.io/projects/spring-ai)
- [Ollama](https://ollama.ai/)

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh

## Contact

For any questions or feedback, please check out:
- Gmail : princybadjatya06@gmail.com
- GitHub: https://github.com/princyjain-06/
- linkedIn : https://in.linkedin.com/in/princy-badjatya-066xyz

