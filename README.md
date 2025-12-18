# CSC360researchProject-RAGLLMs
This repository contains the code data and subsequent research paper created by Christopher Barbosa and Sean Jenkins for CSC 360 Modern Distributed Computing at ccny.  

Paper abstract:  

The field of large language models(LLMs) is fast growing and as the size of models increases so does the energy required to train and run them. Today, LLM systems geared towards inference and QnA generative interactions can be most prominently seen in models like GPT, Grok, etc. Retrieval augmented generation(RAG) is a tool that supplies the LLM with the ability to retrieve external information, aggregate it with its training solution and return a stronger more accurate response. However, this comes at a cost as models that utilize RAG to any extensive degree can perform very slow and require a lot of energy to compute. In this paper we use small models like gpt-2, and gemma3-4b; measuring the energy consumption, solution accuracy, and latency. We found that although the gemma-3-4b models was the most accurate it was also the most costly on energy. In the end we speculate towards the use of light-weight RAG based distributed VLM systems which have the capacity to provide both high accuracy and low energy consumption.  

The code we created in rag_energy_accuracy_benchmark can be run by simply cloning the file and running the imports and and dependencies as follow:  

`!pip install -q --upgrade langchain langchain_community openai faiss-cpu sentence-transformers transformers datasets tqdm matplotlib`

The research was conducted following an extensive literature review, the following is a github repo which housing papers and recent research in the field that we felt was useful for our purposes.
Github link to current research in the field: https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/research_updates/rag_research_table.md 
