# Workshop Workflow

## Day 1

### Part 1: Introduction
- **What are LLMs, applications**
- **Difference and evolution from traditional NLPs, RNN, LSTMs, and Transformers**  
  [Transformer Explainer](https://poloclub.github.io/transformer-explainer/)
- **Prompt Engineering Techniques** (Advantages of a well-written prompt)
- **Prompt Demonstration:**  
  [Google AI Studio](https://aistudio.google.com/prompts/new_chat)
- **Tokenization:**  
  [OpenAI Tokenizer](https://platform.openai.com/tokenizer)
- **Types of Tokenization** (WordPiece, Byte-Pair Encoding, SentencePiece) and Demonstration:  
  [Tokenization Demo](https://github.com/pranalibose/Resume_Analyser/blob/main/tokenization-demo.ipynb)

#### Hands-on 1
[Preprocess Text](https://github.com/pranalibose/LangVisionWorkshop/blob/main/HO1_Text_Processing.ipynb)
- Preprocess resume text
- Tokenize and create embeddings

---

### Part 2: Hugging Face Platform
- **Create an account and access token**
- **Understand the utilities in the platform**

#### Hands-on 2
- Access HF API to get feedback on different resumes
- Add custom instructions to see the performance

### Part 3: Fine-Tuning
- **Why Fine-Tune?**
- **Process of Fine-Tuning**
- **LoRA (Low-Rank Adaptation)**

#### Hands-on 3
- [Fine-Tune a T5 Model for Resume Analysis](https://github.com/pranalibose/Resume_Analyser/blob/main/RA_fine_tuning.ipynb)
- Push onto Hugging Face Hub

---

### Part 4: Streamlit UI
#### Hands-on 4
- [Create a Simple UI using Streamlit](https://github.com/pranalibose/Resume_App)
- Integrate Fine-Tuned Model to Generate Responses

---

## Day 2

### Part 1: Query Resolution & Quiz
- Discuss questions from the previous day
- Conduct a quiz session

---

### Part 2: Retrieval-Augmented Generation (RAG)
- **What is RAG and its advantages?**
- **Comparison: RAG vs. Fine-Tuning**
- **RAG Architecture**
- **What are Vector Databases?**
- **Different Types of Searches**
- **FAISS and how it works**


### Part 3: Hands-on 1
- **RAG Implementation**
- **Integrate RAG and FAISS with the Fine-Tuned Model**

---

### Part 4: What’s Next?
- **Assignment:**
  - Develop an **app to summarize lengthy documents**
  - Take a document as input and choose the summary format (bullet points, short paragraphs)
  - Fine-tune a suitable LLM and integrate with a simple UI

- **Open Discussion**
- **Interview Question Bank**

