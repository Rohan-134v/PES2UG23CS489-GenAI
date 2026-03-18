# Generative AI Coursework 

This repository contains my coursework, assignments, and practical implementations for the Generative AI course at PES University. The focus of this repository is on building and understanding various GenAI concepts through hands-on Jupyter Notebooks, covering topics like Retrieval-Augmented Generation (RAG), Mixture of Experts (MoE), LangChain, and Prompt Engineering.

## Repository Structure

    PES2UG23CS489-GenAI/
    ├── Unit1/
    │   ├── Assignment1_PES2UG23CS489.ipynb
    │   ├── Assignment2_PES2UG23CS489.ipynb
    │   ├── LangChain.ipynb
    │   ├── PES2UG23CS489_MOE.ipynb
    │   ├── PES2UG23CS489_RAG.ipynb
    │   └── l.txt
    ├── Unit2/
    │   ├── Advanced_prompt.ipynb
    │   ├── LangChain.ipynb
    │   ├── PES2UG23CS489_MOE.ipynb
    │   ├── PES2UG23CS489_RAG.ipynb
    │   └── PromptEng.ipynb
    └── README.md

## Detailed File Descriptions

### Unit 1: Foundations of Generative AI
This directory contains introductory implementations and foundational assignments.

* **`Assignment1_PES2UG23CS489.ipynb`**: Initial assignment covering fundamental Generative AI concepts and basic API interactions.
* **`Assignment2_PES2UG23CS489.ipynb`**: Second assignment focusing on practical implementations and extending early course topics.
* **`LangChain.ipynb`**: Introduction to the LangChain framework, covering basic LLM initialization, prompts, and simple chains.
* **`PES2UG23CS489_MOE.ipynb`**: Exploratory notebook demonstrating the architecture, gating networks, and routing mechanisms of Mixture of Experts (MoE).
* **`PES2UG23CS489_RAG.ipynb`**: Implementation of a foundational Retrieval-Augmented Generation (RAG) pipeline to enhance LLM responses with external context.

### Unit 2: Advanced Techniques and Frameworks
This directory builds upon the basics with more complex prompting strategies and advanced framework utilization.

* **`PromptEng.ipynb`**: Practical exercises on foundational prompt engineering strategies to structure and guide LLM behavior effectively.
* **`Advanced_prompt.ipynb`**: Deep dive into advanced prompting paradigms such as Few-Shot prompting, Chain-of-Thought (CoT), and role-playing architectures.
* **`LangChain.ipynb`**: Advanced LangChain implementations, exploring complex retrieval chains, memory components, and potentially custom agents.
* **`PES2UG23CS489_MOE.ipynb`**: Further exploration of Mixture of Experts, focusing on complex routing or applied use cases beyond the basics.
* **`PES2UG23CS489_RAG.ipynb`**: Advanced RAG techniques, exploring optimized text chunking strategies, embedding models, and vector store integration.

## Prerequisites and API Keys

To run the notebooks in this repository, you will need active API keys for Google Gemini and LangChain (LangSmith). 

It is highly recommended to store these keys in a `.env` file in the root directory of this project to keep them secure. Do not commit your `.env` file to version control.

### 1. Getting a Google Gemini API Key
You need a Gemini API key to access Google's foundational models.
1.  Go to Google AI Studio: https://aistudio.google.com/app/apikey
2.  Sign in with your Google account.
3.  Click on the **Create API key** button.
4.  Copy the generated key.
5.  Add it to your `.env` file or environment variables as:
    `GOOGLE_API_KEY="your_gemini_api_key_here"`

### 2. Getting a LangChain (LangSmith) API Key
LangSmith is used for tracing and debugging LangChain applications.
1.  Go to LangSmith: https://smith.langchain.com/
2.  Sign up or log in.
3.  Navigate to the **Settings** page (usually a gear icon in the bottom left).
4.  Go to the **API Keys** section and click **Create API Key**.
5.  Give your key a name, create it, and copy the string.
6.  Add it to your `.env` file or environment variables. You will also need to enable tracing:
    `LANGCHAIN_API_KEY="your_langchain_api_key_here"`
    `LANGCHAIN_TRACING_V2="true"`

## Getting Started

1.  Clone this repository to your local machine:
    `git clone https://github.com/Rohan-134v/PES2UG23CS489-GenAI.git`
2.  Navigate to the project directory:
    `cd PES2UG23CS489-GenAI`
3.  Create a `.env` file in the root directory and add your API keys as shown in the section above.
4.  Install the required dependencies. (Ensure you have `langchain`, `langchain-google-genai`, `python-dotenv`, and `jupyter` installed).
5.  Launch Jupyter Notebook or Jupyter Lab and open the desired notebook to run the cells.
