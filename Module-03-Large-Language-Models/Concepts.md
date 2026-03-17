# 📘 Week 3 – Concepts (LLMs & NLP)

## 🔹 1. Large Language Models (LLMs)

LLMs are AI models trained on massive text data to understand and generate human-like language.

### Key Capabilities:
- Text generation  
- Question answering  
- Summarization  
- Code generation  

---

## 🔹 2. Embeddings

Embeddings convert text into numerical vectors.

### Key Idea:
- Similar meaning → similar vectors  
- Enables semantic understanding  

### Example:
- "cat" ≈ "kitten" (high similarity)  
- "cat" ≠ "car" (low similarity)  

---

## 🔹 3. Cosine Similarity

Used to measure similarity between vectors.

- Value ranges: **-1 to 1**
- Closer to 1 → more similar  

---

## 🔹 4. Multimodal Embeddings

- Combine **text + images** into same vector space  
- Enables cross-modal search  

Example:
- "A cat" ↔ image of a cat  

---

## 🔹 5. RAG (Retrieval-Augmented Generation)

RAG combines:
- Retrieval → fetch relevant data  
- Generation → LLM generates answer  

### Benefits:
- Reduces hallucination  
- Uses real data  
- Improves accuracy  

---

## 🔹 6. Vector Databases

Used to store embeddings efficiently.

### Examples:
- FAISS  
- Pinecone  
- Weaviate  

---

## 🔹 7. Hybrid RAG

Combines:
- Keyword search (TF-IDF)  
- Semantic search (embeddings)  

---

## 🔹 8. TF-IDF

Measures importance of words in a document.

- TF → frequency in document  
- IDF → rarity across documents  

---

## 🔹 9. Topic Modeling (LDA)

Discovers hidden topics in text data.

### Example Topics:
- Sports  
- Finance  
- Health  

---

## 🔹 10. Transformers

Modern NLP models using attention.

### Key Feature:
- Self-attention → understands context  

---

## 🔹 11. BERT vs GPT

| Model | Use |
|------|-----|
| BERT | Understanding |
| GPT | Generation |

---

## 🔹 12. Base64 Encoding

Converts binary data into text format.

Used for:
- Image transmission  
- API communication  

---

## 🔹 13. Vision Models

LLMs that process images.

### Capabilities:
- Image description  
- Data extraction  
- OCR-like tasks  

---

## 🔹 14. Function Calling

LLMs return structured JSON output.

Used for:
- Chatbots  
- Automation  
- Backend integration  

---

## 🔹 15. PromptFoo (LLM Evaluation)

Used to test LLM outputs.

### Features:
- Assertions  
- Multi-model testing  
- CI/CD integration  

---

## 📌 Conclusion

- Understood NLP evolution  
- Learned embeddings & similarity  
- Explored RAG and vector search  
- Studied modern LLM architectures  