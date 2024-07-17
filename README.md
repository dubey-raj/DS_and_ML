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
