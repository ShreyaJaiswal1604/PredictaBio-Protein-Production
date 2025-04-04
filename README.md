# 🧬 Protify: Accelerating Protein Synthesis with AI

**PredictaBio** is a next-generation platform built during a hackathon to assist researchers in **rapidly optimizing protein production** using **Generative AI**, **Literature Mining**, and **LLM-powered analytics**. The platform intelligently extracts experimental protocols from scientific publications and guides researchers toward the most suitable production conditions for proteins such as *EGF*, *LIF*, and *FGF1*.

---

## 🚀 Hackathon Highlights

### 🎯 Objective

Develop an AI-powered assistant to:

- 🔍 Search and extract relevant literature based on protein names.
- 🧠 Use LLMs to identify and summarize key protein production parameters.
- 📊 Structure and filter the extracted insights to guide experimental decisions.
- 🤖 Enable real-time interaction via a chatbot using Retrieval-Augmented Generation (RAG).

---

## ✅ Features

| Feature | Description |
|--------|-------------|
| 🔬 **Protein-Based Search** | Enter a protein name and automatically retrieve scientific PDFs. |
| 📄 **Metadata & Content Extraction** | Extract metadata like protein name, publication title, and full content from PDFs. |
| 🧠 **LLM-Powered Parameter Mining** | Use Amazon Bedrock to extract 5 critical protein production parameters from unstructured documents. |
| 📊 **Structured Filtering** | View and filter papers by extracted attributes (host organism, yield, expression system, etc.). |
| 🤖 **Interactive Chatbot** | Ask detailed questions about selected PDFs with real-time answers powered by RAG. |
| 🌐 **Web Interface** | Built with **Lovable**, the front end offers clean navigation, dropdown filtering, and AI chat support. |

---
## 🔧 Architectural Overview

PredictaBio is composed of modular, cloud-ready components designed for scalability and ease of use:


---

## 🔍 Extracted Parameters

For each protein-related publication, the platform extracts:

- Host Organism  
- Expression System  
- Culture Conditions  
- Purification Techniques  
- Yield/Output Metrics

---

## 📸 Presentation Demo

👉 Click to access our presentation - [view the full hackathon walkthrough here](https://www.beautiful.ai/player/-OMSiU-9dqFjIIx2bRR5/PredictaBio-Accelerating-Protein-Synthesis-with-AI).

---

## 🛠 Tech Stack

| Layer         | Tools & Frameworks                             |
|---------------|-------------------------------------------------|
| **Frontend**   | Lovable UI, React-based components             |
| **Backend**    | Python, LangChain, Flask (optional)            |
| **LLM/AI**     | Amazon Bedrock (Claude), RAG architecture      |
| **Data Parsing** | PyMuPDF, PDFMiner, PDFPlumber               |
| **Storage**     | AWS S3 (PDFs), Pandas, JSON-based tables       |
| **Deployment**  | GitHub Codespaces, optional Streamlit frontend|

---

## 💡 Real-World Scenario

Imagine you're a researcher planning to express *FGF1* in E. coli. Instead of manually scanning dozens of papers:

1. 🔍 Search “FGF1” in PredictaBio.
2. 📄 Get instant access to curated, analyzed literature with key parameters.
3. 📊 Filter for papers using *E. coli* + *high yield* protocols.
4. 🤖 Ask our chatbot, “Which paper gives highest yield using E. coli for FGF1?”

➡️ In minutes, you're ready to experiment — backed by AI-driven insights.

---

## 📈 Future Enhancements

- 🧬 Integrate with PubMed & Semantic Scholar APIs  
- 🧠 Fine-tune domain-specific LLMs (bioBERT, SciBERT)  
- 🧪 Add confidence scores and suitability ratings per paper  
- 📦 Export filtered data as CSV/JSON for lab use  
- 🧬 Visual dashboards for cross-paper comparisons  

---

## 👩‍🔬 Built With Passion

Developed during [Hackathon Name] by a multidisciplinary team of:

- AI & ML Engineers  
- Bioinformatics Researchers  
- Full Stack Developers  

Special thanks to **Amazon Bedrock**, **Lovable**, and open-source biology tools for powering this innovation.

---

## 📬 Contact & Contributions

We welcome feedback, suggestions, and contributions!

🔗 [Project Website](https://github.com/YourRepoLink)  
📧 Email us at: `shreya.jais1604@gmail.com`  
💬 Let’s build the future of biotech research together!

