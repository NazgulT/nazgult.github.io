# 👋 Hi, I’m Naz

### AI Engineer | Data Scientist | Python Developer

I build **AI systems** that transform research ideas into scalable software solutions.

With a background in **Artificial Intelligence and Computer Science**, I specialize in designing, building, and deploying machine learning and LLM-powered applications.

---

## What I Do

* Build end-to-end ML & AI systems
* Develop LLM & Retrieval-Augmented Generation (RAG) applications
* Build evaluation and observability pipelines
* Design scalable APIs for AI inference
* Apply data science & machine learning to real-world problems

---

## Technical Skills

**Languages:** Python (Advanced), SQL, Java, C/C++, R    
**AI/ML:** LangChain, LangGraph, LlamaIndex, PyTorch   
**Agentic AI:** CrewAI, BeeAI, AutoGen   
**LLM Platforms and APIs:** OpenAI API, Ollama, Hugging Face, AWS Bedrock 
**Vector Databases and Retrieval:** ChromaDB, FAISS, Hugging Face Embeddings  
**Backend and Deployment:** FastAPI, FLask, REST APIs , GitHub Actions, CI/CD fundamentals
**Frontend prototyping:** Streamlit, Gradio  
**Evaluation and Observability:** RAGAS, LangSmith, LangFuse, Logging, MLFlow
**Tools:** Linux, Jupyter, Cursor, VS Code  

---

## Featured Projects

### Production-Ready RAG Assistant

**Tech:** Python, FastAPI, Chroma DB, Hugging Face Transformers, RAGAS, MlFlow

* Built a scalable, modular Retrieval-Augmented Generation (RAG) system with FastAPI for intelligent document Q&A, featuring advanced chunking, hybrid retrieval (semantic + BM25), cross-encoder reranking, and comprehensive evaluation using RAGAS metrics.
* Included MLflow tracking, ChromaDB storage, a Streamlit dashboard, and support for multiple document formats, processing 10,000+ chunks efficiently with 4 core evaluation metrics for answer quality assessment. 

[visit rag repository](https://github.com/NazgulT/rag-assistant)


### Small Language Model Evaluation Dashboard

**Tech:** Python, FastAPI, Ollama

* Implemented a small language model (SLM) evaluation dashboard that runs entirely offline using **Ollama** as the local inference backend. * Benchmarked multiple small models (2–5B parameters) across three phases: raw inference performance, structured output validation, and temperature variance analysis. Results are written to CSV and exposed via a REST API for a React dashboard.
* The following SLMs were benchmarked (the list is expanding): phi3-mini, gemma2-2b, qwen2.5-3b, llama3.2-3b

[visit slm repository](https://github.com/NazgulT/slm-evaluation-dashboard/tree/main)

### End-to-End Machine Learning Pipeline - Time - Series Forecasting and Model Evaluation

**Tech:** Python, Scikit-learn, Pandas, XGBoost, LSTM, SARIMAX, Prophet

* Built a complete ML workflow from data ingestion to evaluation
* Compared multiple models using cross-validation
* Implemented experiment tracking & reproducibility

[visit time-series repository](https://github.com/NazgulT/caribbean-climate-forecasting)


### YouBot: AI-powered YouTube Video Summarizer and Q&A 

**Tech:** LangChain, FAISS, Streamlit, HuggingFace Transformers

* Designed a RAG system using LangChain and HF embeddings
* Implemented request validation & logging
* Developed an AI chatbot for document querying and a separate pipeline for video transcript analysis

[visit youbot repository](https://github.com/NazgulT/rag-youtube-summarizer)

---

## Currently working on
### Conversational Agent with Memory + Guardrails 

**Tech:** LangChain, LangGraph, LangSmith, Redis, ChromaDB, FastAPI, Pydantic, LangChain Embeddings, OpenAI API

* Implementing a multi-turn customer support agent with short-term (buffer) and long-term (vector database) memory, topic guardrails and fallback handling. Logs every failure to LangSmith. 

### Real-Time Streaming AI Assistant with Source Attribution Framework

* Working on a real-time AI response system using FastAPI and SSE to stream LLM-generated answers token-by-token to users. Building a citation and traceability framework that injects inline source references (document title, page, chunk ID) into generated responses. 

---

## Education

**MSc Artificial Intelligence** - University of Edinburgh, UK (2017)  
**BSc Computer Science** - University College Dublin, Ireland (2013)

---

## Let’s Connect

* 💼 LinkedIn: *([https://www.linkedin.com/in/nazgult/](https://www.linkedin.com/in/nazgult/))*
* 🌐 GitHub Profile: *([https://github.com/NazgulT](https://github.com/NazgulT))*
* 📧 Email: *(nazgul.tazhigaliyeva@gmail.com)*

---

⭐ *I’m actively seeking opportunities to contribute to AI-driven products and engineering teams.*


## Certifications

* [IBM RAG and Agentic AI Specialization](https://coursera.org/share/c13d9f188df6687d4481859090381d4b), Coursera [2026]
* [IBM Data Science Specialization](https://coursera.org/share/1a420574d7ed5b04fd69e73af7afde92), Coursera [2025]
* [Blockchain Basics](https://coursera.org/share/d4f39cabe4462fc98bfbf4f7108c992f), Coursera [2021]
* [R Programming](https://coursera.org/share/bc9f5c987d6f991a830d53c35866ea3c), Coursera [2021]

## Previous Projects

* [Time-Series Forecast](https://github.com/NazgulT/caribbean-climate-forecasting.git)
    Time-Series EDA + Forecasting - Predicting Caribbean Climate for 2026 - 2027. The four different popular ML models (SARIMAX, XGBoost, LSTM and Prophet) were trained on Caribbean temperature anomalies and precipitation spanning 1980 - 2025, with Prophet outperforming the rest with MAE = 0.17C. The data was obtained from the NOAA historical dataset.
* [Recommender System + Streamlit](https://github.com/NazgulT/movie_recom)
    The AI-powered movie recommender uses SVD collaborative filtering on the MovieLens 100K dataset to predict personalized movie ratings. It delivers top-N recommendations with confidence scores and generates creative taglines using Hugging Face FLAN-T5 offline. An interactive Plotly network graph visualizes user taste. Built with Streamlit.

## Work Experience

**Instructor @ Computer Science Department, Nazarbayev University _[2018 - Present]_**
<ul>
  <li>Designed and taught <i> Data Structures and Algorithms, Programming for Scientists and Engineers, Programming Languages, Research Methods</i> using C, C++, Python, Java  to over 1000 undergraduate students. </li>
  <li>Created syllabi, coding assignments and exams aligned with industry trends.</li>
  <li>Provided one-on-one guidance during office hours to troubleshoot technical and coding issues.</li>
  <li>Served on curriculum committees for Research Methods, hiring committees, and organised LT&T coding workshops to enhance student participation at competitions.</li>
</ul>

**Research Assistant (Robotics and Machine Learning) @ Robotics and Mechatronics Department, Nazarbayev University _[2014 - 2018]_**
<ul>
  <li>Assisted in design, implementation and testing of robotic systems, focusing on areas such as robot manipulation, control algorithms and human-robot interaction.  </li>
  <li>Gathered and processed experimental data such as sonsor reading, simulation outputs utilizing tools like MATLAB and ROS.</li>
  <li>Performed comprehensive reviews of current Machine Learning, Aritificial Intelligence and Robotics literature and contributed to research publications, research and grant proposals.</li>
  <li>Maintained robotics lab equipment and hands-on guidance to undergraduate students in courses like Microcontrollers, Electrical and Electronic Circuits, Robotics and Research Methods.</li>
</ul>


**Project Engineer Intern @ Microsoft _[2013]_**

* Developed enterprise components and automated workflows using C# and SharePoint.
* Queried and validated structured datasets using SQL.

  
## Research Projects @ Nazarbayev University

- SLIRS: Sign Language Interpreting Robotic System [2016]
- Adaptive Control Architecture for Humanoid Robotics based on Recurrent Neural Networks [2015]
- Development of an Intelligent Assistive Robot Manipulation System for Improving the Quality of Life of Disabled People [2015]
  

## Relevant Publications
1. Tazhigaliyeva, Nazgul, et al. "Cyrillic manual alphabet recognition in RGB and RGB-D data for sign
language interpreting robotic system (SLIRS)." Robotics and Automation (ICRA), 2017 IEEE
International Conference on. IEEE, 2017.
2. Tazhigaliyeva, Nazgul, et al. "SLIRS: Sign language interpreting system for human-robot interaction."
2016 AAAI Fall Symposium Series. 2016.
3. Folgheraiter, Michele, Nazgul Tazhigaliyeva, and Aibek Niyetkaliyev. "Adaptive joint trajectory
generator based on a chaotic recurrent neural network." Development and Learning and Epigenetic
Robotics (ICDL-EpiRob), 2015 Joint IEEE International Conference on. IEEE, 2015.

## Extracurricular

* Secured more than \$100,000 in scholarships for academic achievements.
* Authored influential research publications in AI and HRI, accumulating 50+ citations.
* Volunteered with a local school’s Robotics Club, facilitating student participation in international robotics competitions.

