# Raj_Dubey_3169793 NAGP DS and ML Assignment
Implementation of Data Science NB and Decision tree algos and QA chat bot using langchain

This project contains folders as below:
<ul>
  <li><a href="./DS">Data Science</a> </li>
  <li><a href="./LLM"> Machine Learning</a></li>
</ul>

# Data Science
This contains .ipnyb <a href="./DS/Heart_Disease_Predictor.ipynb"> notebook </a> file to for heart disease prediction using provided data set.

# Machine Learning
## Architecture Diagram
![Architecture Diagram](/LLM/QA_Chatbot.png)

## Deployment
Deployment of model that is created in <a href="./LLM/Raj_QnA_Chatbot.ipynb"> notebook </a> file,
<ol>
  <li>Serve this model with Fast API</li>
  FastAPI is a modern, high-performance web framework for building APIs with Python based on standard type hints. It comes with a lot of great features including development speed, runtime speed, and great community support, making it a great choice for serving chatbot agent.
<li>Create Docker file with dependencies</li>
<li>Build image using above docker file</li>
<li>Run image in dockerize environment as container</li>
<li>Expose container as service, so endoint can be called from UI</li>
<li>Secure endpoints with authentication mechanism e.g. jwt token</li>
<li>Develop UI for chat agent using any front end framework e.g. React, Angular or Streamlit.</li>
</ol>

# Screenshots
Screenshots are available below:
## 1. Install required packages
![Install required packages](/Screenshots/1-Install_Dependencies.png)

## 2. Loading_TinyLlamma_Model
![Install required packages](/Screenshots/2-Loading_TinyLlamma_Model.png)

## 3. Load Pdf Document
![Install required packages](/Screenshots/3-Load_Pdf_Document.png)

## 4. Generate embeddings and perform similarity search with pinecone vector DB
![Install required packages](/Screenshots/4-Generate_Embedding_and_Perform_Similarity_Search.png)

## 5. Refine search with LLM
![Install required packages](/Screenshots/5-Refine_Search_With_LLM.png)

## 6. Final answer by LLM
![Install required packages](/Screenshots/6-Final_Answer_By_LLM.png)
