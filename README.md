# Rag_literature Project

The Rag_literature project employs Retrieval-Augmented Generation (RAG) technology to systematically extract structured data from scientific literature concerning enzyme kinetics. The ultimate goal is to assemble a comprehensive enzyme kinetics database conducive to deep learning research on enzymes. If proven successful, this methodology could extend to other domains requiring precise data extraction.

This project utilizes tools like ([langchain](https://www.langchain.com/)) and ([ollama](https://ollama.com/)) to construct a localized RAG environment. Initial tests in Jupyter notebooks have shown promise but require further refinement to meet our stringent data quality standards.

# Getting Started
Below are the steps to set up the environment, prepare your data, and download the necessary models to begin using or improving the Rag_literature project.

# Environment Setup
```
conda create -n rag_literature python==3.10
```
```
conda activate rag_literature  
```
```
pip install -r requirements.txt
```  

# Data Preparation
Gather the enzyme kinetics literature you intend to analyze and place it in a designated folder.  

Note: I use "pmid" to refer to the literature, but you can adjust it in the code  

# Model Downloads
```
ollama pull llama2:7b
```
```   
ollama pull nomic-embed-text    
```
Note: Different models may yield varying outputs, so consider experimenting with alternatives to find the best fit for your data.

# Starting the Project
Launch the Notebook

# Contribution
If you're interested in contributing to the improvement of this project, please feel free to make suggestions, submit pull requests, or open issues on our GitHub repository.   
Your input is invaluable in making Rag_literature a robust tool for scientific research.  
