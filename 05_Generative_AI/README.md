# Generative AI (GenAI)

Generative AI refers to deep learning models that can generate high-quality text, images, code, and other content based on the data they were trained on.

## 1. Large Language Models (LLMs)
The backbone of modern GenAI (e.g., ChatGPT, Claude, LLaMA).
*   **Architecture:** Based on the Decoder part of the Transformer architecture.
*   **Training Stages:** 
    1.  **Pre-training:** Predicting the next word on massive internet datasets (Unsupervised).
    2.  **Fine-tuning (SFT):** Supervised Fine-Tuning on QA pairs to make it act like an assistant.
    3.  **RLHF (Reinforcement Learning from Human Feedback):** Aligning the model with human preferences for safety and helpfulness.
*   **Prompt Engineering:** Techniques to get better outputs (Few-shot prompting, Chain of Thought, ReAct).

## 2. Retrieval-Augmented Generation (RAG)
Solving LLM hallucinations and updating their knowledge without retraining.
*   **The Workflow:**
    1. Document Parsing & Chunking.
    2. Generating Embeddings using models like OpenAI's text-embedding-ada-002.
    3. Storing vectors in a Vector Database (Pinecone, ChromaDB, Weaviate).
    4. Upon a user query, searching for similar chunks.
    5. Passing the query + context chunks to the LLM to generate an answer.
*   **Frameworks:** LangChain, LlamaIndex.

## 3. Image Generation
*   **GANs (Generative Adversarial Networks):** A Generator creates images, a Discriminator tries to spot fakes. They learn by competing.
*   **Diffusion Models:** (State-of-the-Art)
    *   Forward Process: Gradually add noise to an image until it's pure static.
    *   Reverse Process: Train a neural network to denoise the image step-by-step.
    *   Examples: Stable Diffusion, DALL-E, Midjourney.

## 4. Advanced Agentic Architectures & Data Pipelines
For a deeper dive into modern production GenAI frameworks and systems, check out:
*   [Advanced Agentic Workflows, MCP, and Data Engineering](./Advanced_Agentic_Workflows_MCP_and_Data_Engineering.md) — Comprehensive guide covering **Model Context Protocol (MCP)**, **LangChain (LCEL)**, **LangGraph state machines**, and their connections to **Data Engineering (ETL/ELT, Lakehouses)** and **Data Science (embeddings, feature stores, evaluations)**.
