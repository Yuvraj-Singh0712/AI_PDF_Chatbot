# <p align="center">
   [![Typing SVG](https://readme-typing-svg.demolab.com?font=algerian&size=40&pause=1000&color=F70000&background=9A80FF00&center=true&vCenter=true&width=435&lines=AI+PDF+CHATBOT)](https://git.io/typing-svg)
 </P>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:06B6D4&height=220&section=header&text=PDF%20Chatbot%20RAG&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38"/>
</p>


# 🚀 Live Notebook

Run the complete project directly in Google Colab without any local setup.

<p align="center">

<a href="https://colab.research.google.com/drive/1AaAcZWx2BSIhsmW8dfuLrbb-bptlw6ee?usp=sharing">
<img src="https://colab.research.google.com/assets/colab-badge.svg">
</a>

</p>


---

# 📖 About the Project

PDF Chatbot with RAG is an end-to-end Retrieval-Augmented Generation application that enables users to upload PDF documents and interact with them using natural language.

Instead of relying solely on the knowledge of a Large Language Model, the system first retrieves the most relevant sections of the uploaded document using semantic search and then generates an answer grounded entirely in that retrieved context.

This significantly reduces hallucinations while improving factual accuracy and allowing the chatbot to answer questions about completely unseen documents.

The project demonstrates the complete modern RAG pipeline used in production AI applications.

---

# 🎯 Objectives

- Build an end-to-end Retrieval-Augmented Generation pipeline.
- Understand vector embeddings and semantic search.
- Learn how modern AI chatbots retrieve information.
- Reduce hallucinations using retrieved context.
- Deploy an interactive chatbot interface.
- Demonstrate practical applications of Large Language Models.

---


# 🖼 Project Architecture

<p align="center">

```text
             Upload PDF
                  │
                  ▼
          Text Extraction
                  │
                  ▼
          Text Chunking
                  │
                  ▼
        Sentence Embeddings
                  │
                  ▼
             ChromaDB
                  │
        Similarity Search
                  │
                  ▼
          Retrieved Context
                  │
                  ▼
          Zephyr 7B LLM
                  │
                  ▼
         Grounded Response
```

</p>

---

# 🚀 Features

✅ Upload any PDF

✅ Semantic Search

✅ Retrieval-Augmented Generation (RAG)

✅ Context Grounded Responses

✅ Vector Database (ChromaDB)

✅ Source-aware Answers

✅ Beautiful Gradio Interface

✅ Runs on Google Colab

✅ Free GPU Compatible

---

# 🛠 Tech Stack

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Gradio](https://img.shields.io/badge/Gradio-FF7A00?style=for-the-badge&logo=gradio&logoColor=white)

![Transformers](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-00599C?style=for-the-badge)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

![ChromaDB](https://img.shields.io/badge/ChromaDB-9146FF?style=for-the-badge)

![PyPDF2](https://img.shields.io/badge/PyPDF2-E34F26?style=for-the-badge)

![BitsAndBytes](https://img.shields.io/badge/BitsAndBytes-FF6B00?style=for-the-badge)

</p>

---

# 💡 Key Highlights

- 📄 Upload any PDF document
- 🔍 Semantic Search instead of keyword search
- 🧠 Context-aware responses
- ⚡ Fast vector retrieval using ChromaDB
- 🤖 Zephyr-7B Language Model
- 📚 Sentence Transformers embeddings
- 🖥️ Google Colab compatible
- 🌍 Interactive web interface
- 📝 Source grounded answers
- 🚀 Beginner-friendly implementation

---

# 📂 Project Structure

```bash
PDF-Chatbot-RAG
│
├── app.py
├── requirements.txt
├── README.md
├── assets/
├── notebooks/
├── data/
├── chroma_db/
└── images/
```

---

# ⚙️ Installation

```bash
git clone https://github.com/Yuvraj-Singh0712/REPOSITORY.git
```

```bash
cd REPOSITORY
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

---

# 📊 RAG Workflow

```text
PDF
 │
 ▼
Extract Text
 │
 ▼
Chunk Text
 │
 ▼
Embeddings
 │
 ▼
Store in ChromaDB
 │
 ▼
User Question
 │
 ▼
Question Embedding
 │
 ▼
Similarity Search
 │
 ▼
Retrieve Context
 │
 ▼
Zephyr 7B
 │
 ▼
Answer
```

---

### 📂 Folder Description

| Folder | Description |
|---------|-------------|
| assets | Images and screenshots used in README |
| notebooks | Google Colab notebook |
| chroma_db | Stores vector embeddings |
| utils | Helper functions and utilities |
| data | Sample PDFs for testing |
| models | Embedding and model configurations |

---

# ⚙️ Working Principle

The chatbot follows the Retrieval-Augmented Generation workflow.

1. User uploads a PDF.
2. Text is extracted using PyPDF2.
3. The document is divided into overlapping chunks.
4. Each chunk is converted into embeddings.
5. Embeddings are stored in ChromaDB.
6. User asks a question.
7. Question is converted into an embedding.
8. ChromaDB retrieves the most similar chunks.
9. Retrieved context is sent to the language model.
10. The model generates a grounded response.

---

# 📦 Dependencies

- Python
- PyPDF2
- Sentence Transformers
- ChromaDB
- Transformers
- BitsAndBytes
- Torch
- Accelerate
- Gradio

---

# 📈 Future Improvements

- OCR Support
- Multi-PDF Chat
- Conversation Memory
- Citation Highlighting
- Streaming Responses
- Hybrid Search
- FAISS Support
- Docker Deployment
- Authentication
- Cloud Deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a new branch

3. Commit changes

4. Push the branch

5. Open a Pull Request


# 📜 License

Licensed under the MIT License.

---

# 👨‍💻 Author

## Yuvraj Singh

Artificial Intelligence & Machine Learning Enthusiast

Passionate about building intelligent applications using Machine Learning, Deep Learning, Generative AI, Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG).

This project demonstrates practical implementation of modern AI techniques including semantic search, vector databases, and grounded question answering over custom PDF documents.

## 🌐 Connect with Me

<p align="center">

<a href="https://github.com/Yuvraj-Singh0712">
<img src="https://img.shields.io/badge/GitHub-Yuvraj--Singh0712-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/yuvrajsingh0712">
<img src="https://img.shields.io/badge/LinkedIn-Yuvraj%20Singh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:yuvisingh0712@email.com">
<img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

<p align="center">

### ⭐ If you found this project useful, don't forget to star the repository!

Made with ❤️ by **Yuvraj Singh**

</p>
