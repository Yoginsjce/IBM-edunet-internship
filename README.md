# IBM-edunet-internship
AI-powered College Admission Assistant using IBM Watsonx.ai and RAG to instantly answer student queries from official admission documents. Deployed on IBM Cloud with Granite LLM for accurate, real-time, and context-aware responses.

# 🎓 College Admission Agent (RAG Based)

## 📌 Problem Statement
The college admission process involves multiple queries related to eligibility, fees, course selection, and deadlines.  
Manual handling of these queries is time-consuming and can result in delays or inconsistent responses.  
This project aims to develop an **AI-powered College Admission Agent** using **Retrieval-Augmented Generation (RAG)**,  
which retrieves and summarizes admission policies, eligibility criteria, and FAQs from official sources to answer queries instantly.

---

## 🚀 Technology Used
- **IBM Cloud Lite Services**
  - Cloud Object Storage (Data storage)
  - Watsonx.ai Runtime (Model execution)
- **IBM Granite LLM** – Large Language Model for natural language understanding
- **RAG Pipeline** – Combines retrieval from documents with AI-generated responses
- **Python** – Backend integration
- **LangChain** (optional) – Retrieval and context management
- **Streamlit / Flask** – Web interface for user queries

---

## ✨ Features / Wow Factor
- Real-time **document-aware Q&A** using institutional data
- Supports **natural language queries** without requiring technical skills
- Retrieves the most **relevant, verified, and updated** admission details
- Scalable for **multiple institutions** with minimal setup changes
- **Fast, accurate, and transparent** responses for applicants

---

## 👥 End Users
- **Prospective Students** – Quick access to admission details
- **Parents/Guardians** – Clear understanding of fees and processes
- **College Admission Offices** – Reduced manual query handling
- **Counselors/Education Consultants** – Instant access to updated guidelines
- **International Applicants** – Accessible across time zones

---

## 📊 Results
- Successfully deployed an **AI-driven admission assistant** on IBM Cloud
- Integrated **RAG pipeline with Granite LLM** to retrieve answers from official documents
- Reduced **average query resolution time** from hours/days to seconds
- Provided **consistent and accurate** answers from verified data

---

## 🏗 System Architecture
```plaintext
User Query → Agent Lab (Granite LLM) → RAG Retrieval Layer → Document Database (COS) → Processed Answer
