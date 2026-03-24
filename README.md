# 🗺 Harshith's Portfolio
Welcome to my data portfolio! Here, I document a summary of my projects in the data field.

---

## Table of Contents
- [Machine Learning](#machine-learning)
- [Data Engineering](#data-engineering)
- [Data Analytics](#data-analytics)

---

# Machine Learning 

## Computer Vision
| Project Link | Tools | Description |
|---|---|---|
| [Real-Time Expression Detection](https://github.com/harshxth/Real-Time-Expression-Detection) | OpenCV, Keras, TensorFlow | CNN-based real-time facial expression recognition from video streams. |

## Traditional ML
| Project Link | Tools | Description |
|---|---|---|
| [Hospital LOS Prediction](https://github.com/Harshxth/Hospital-LOS-Prediction) | scikit-learn, pandas | ML model predicting hospital length of stay from 100k records. XGBoost achieved 0.3032-day MAE, beating baselines. |

## LLM & RAG
| Project Link | Tools | Description |
|---|---|---|
| [PDF RAG Chatbot](https://github.com/Harshxth/pdf-rag-chatbot) | LangChain, ChromaDB, Ollama, Streamlit, Docker | Fully local RAG pipeline to chat with multiple PDFs. Chunks documents into embeddings, retrieves semantically similar context, and generates grounded answers with page-level source citations. No API costs — runs entirely on-device via Ollama. |
| [Healthcare Research Agent](https://github.com/Harshxth/Healthcare-Research-Agent) | LangChain, OpenAI API, Streamlit, Docker | 4-Agent AI system searching PubMed to create medical research reports. |
| [CiteIQ](https://github.com/Harshxth/citeiq) | LangGraph, ChromaDB, LangSmith, HuggingFace Spaces | Production agentic RAG system with LangGraph multi-agent orchestration, hybrid retrieval, and LLM-as-judge self-evaluation (faithfulness + relevancy scoring). Processes clinical medical literature with 1.0 faithfulness scores. Deployed live at harshxth-citeiq.hf.space. |

---

## Data Engineering
| Project Link | Tools | Description |
|---|---|---|
| [Hospital Readmission Pipeline](https://github.com/Harshxth/hospital-readmission-pipeline) | Apache Airflow, BigQuery, GCS, Python, SQL | End-to-end GCP data pipeline for hospital readmission analysis and revenue insights. Implements Bronze → Silver → Gold medallion architecture in BigQuery, orchestrated via Cloud Composer. |

---

## Data Analytics 
*(PowerBI, Tableau, SQL analysis will push soon)*
