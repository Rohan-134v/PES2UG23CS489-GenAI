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

## Contents Overview

### Unit 1
This section deals with the foundational assignments and introductory implementations of GenAI architectures. 
* **Assignments:** Core course assignments assessing early concepts.
* **LangChain:** Initial explorations into building LLM applications using the LangChain framework.
* **MOE & RAG:** Introductory notebooks demonstrating Mixture of Experts models and Retrieval-Augmented Generation systems.

### Unit 2
This section builds on the first unit with more advanced techniques and deeper explorations into prompting and framework utilization.
* **Prompt Engineering:** Techniques for structuring and optimizing prompts to get better outputs from large language models.
* **Advanced Prompting:** A deeper dive into complex prompting strategies.
* **Advanced Frameworks:** Continued work on LangChain, MoE, and RAG architectures with more complex use cases.

## Prerequisites and API Keys

To run the notebooks in this repository, you will need active API keys for Google Gemini and LangChain (LangSmith). 

It is highly recommended to store these keys in a `.env` file in the root directory of this project to keep them secure. Do not commit your `.env` file to version control.

### 1. Getting a Google Gemini API Key
You need a Gemini API key to access Google's foundational models.
1. Go to Google AI Studio: https://aistudio.google.com/app/apikey
2. Sign in with your Google account.
3. Click on the **Create API key** button.
4. Copy the generated key.
5. Add it to your `.env` file or environment variables as:
   `GOOGLE_API_KEY="your_gemini_api_key_here"`

### 2. Getting a LangChain (LangSmith) API Key
LangSmith is used for tracing and debugging LangChain applications.
1. Go to LangSmith: https://smith.langchain.com/
2. Sign up or log in.
3. Navigate to the **Settings** page (usually a gear icon in the bottom left).
4. Go to the **API Keys** section and click **Create API Key**.
5. Give your key a name, create it, and copy the string.
6. Add it to your `.env` file or environment variables. You will also need to enable tracing:
   `LANGCHAIN_API_KEY="your_langchain_api_key_here"`
   `LANGCHAIN_TRACING_V2="true"`

## Getting Started

1. Clone this repository to your local machine:
   `git clone https://github.com/Rohan-134v/PES2UG23CS489-GenAI.git`
2. Navigate to the project directory:
   `cd PES2UG23CS489-GenAI`
3. Create a `.env` file in the root directory and add your API keys as shown in the section above.
4. Install the required dependencies. (Ensure you have `langchain`, `langchain-google-genai`, `python-dotenv`, and `jupyter` installed).
5. Launch Jupyter Notebook or Jupyter Lab and open the desired notebook to run the cells.
