# llm-comparison-spring/ LLM Comparison Engine

This repository contains a Spring Boot application that demonstrates the integration of multiple Large Language Models (LLMs) of Ollama including lamma, Gemma 2, and Deepseek, using the Spring AI library. The project also includes a React-based UI for comparing responses from different models.

FEATURES

1.Integration with multiple LLM providers: (GPT models)
  Anthropic (Claude models)
  Ollama (Local models)
2. REST API endpoints for interacting with each LLM
3. React-based user interface for comparing model responses side-by-side
3. Configurable prompts and model parameters.

PREREQUISITES

1. Java 17 or higher
2. Maven 3.6 or higher
3. Node.js and npm (for the React UI)
4. Ollama installed locally
5. Pull the needed ollama models
   
Backend Setup
Clone the repository:

git clone https://github.com/navinreddy20/SpringAIwithModels.git

Configure your API keys in application.properties or via environment variables:

spring.ai.openai.api-key=your_openai_key
spring.ai.anthropic.api-key=your_anthropic_key
# Other configuration properties...
Build the Spring Boot application:

mvn clean package -DskipTests
Frontend Setup
Navigate to the React UI directory:

cd src/main/llm-comparison-ui
Install dependencies:

npm install
Build the UI:

npm run dev
