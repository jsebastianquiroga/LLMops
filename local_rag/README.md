## Building a RAG Application using Open-Source Models

This guide provides instructions on running a local LLM on your computer and building a Retrieval Augmented Generation (RAG) system using open-source models. We focus on using the PHI3 model and experimenting with a Spanish book, "El Viejo y el Mar," to try the RAG and LangChain techniques.

### Instructions for Downloading and Using OLLAMA

1. **Installing OLLAMA**

    - **Step 1:** Go to the [OLLAMA website](https://www.ollama.com) and download the appropriate installer for your operating system.
    - **Step 2:** Follow the installation instructions provided on the website to set up OLLAMA on your machine.
    - **Step 3:** Once installed, open OLLAMA and verify the installation by running a test command:
      ```sh
      ollama --version
      ```
    - **Step 4:** Download and manage models using OLLAMA. For example, to download the PHI3 model, use:
      ```sh
      ollama download phi3
      ```

2. **Using OLLAMA**

    - **Step 1:** Launch OLLAMA and load the desired model:
      ```sh
      ollama load phi3
      ```
    - **Step 2:** Use OLLAMA to run your local LLM and interact with it:
      ```sh
      ollama run
      ```
    - **Step 3:** Integrate OLLAMA with your RAG system to handle tasks like generating embeddings, chaining components, and managing question-answering processes.

### Focus on the Content

For our case, we are using a Spanish book titled "El Viejo y el Mar" to experiment with the RAG and LangChain techniques. The aim is to build a system that can read and answer questions from the book using the PHI3 model.

### Key Steps in Building the RAG Application

1. **Installing OLLAMA**

    - **Step 1:** Install OLLAMA to run open-source models locally.
    - **Step 2:** Use OLLAMA to download and manage models like PHI3, Mixol, and others.

2. **Building the RAG System**

    - **Step 1:** Clone the repository to access the implementation details.
    - **Step 2:** Build a simple RAG system to read and answer questions from a PDF of "El Viejo y el Mar".
    - **Step 3:** Generate embeddings for context and questions to improve question-answering accuracy.
    - **Step 4:** Utilize LangChain to chain components like models, parsers, and retrievers.
    - **Step 5:** Implement streaming and batching techniques for faster processing of multiple questions simultaneously.

### Customization and Experimentation

- **Explore**: Customize the code to integrate other open-source models for diverse use cases.
- **Experiment**: Try different chaining and retrieval mechanisms to enhance your question-answering system.
- **Deploy**: Learn how to deploy open-source models locally for cost-effective and secure applications.
